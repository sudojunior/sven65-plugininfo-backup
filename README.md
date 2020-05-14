# angelisawizard-backup

A backup repository for a streamer's assets.

## Configuration

| Key                   | Type             | Description |
| --------------------- | ---------------- | ----------- |
| `!webhook.*`          | `Object`         |             |
| `webhook.id`          | `string`         |             |
| `webhook.token`       | `string`         |             |
| `defaultPayload?=!{}` | `WebhookMessage` |             |
| `!files=[]`           | `string[]`       |             |

-   `!` = required
-   `?` = optional

## License

Rights to the files `config.example.json` and `post.js` belong to myself under UNLICENSE.

Rights to all files under `./images/*` belong to AngelisaWizard, this repository hosts a backup for their content and the means to repost it in the event it is unrecoverable.

## Run Instructions

- `npm install`
- (create and configure `config.json` file)
- `npm start`