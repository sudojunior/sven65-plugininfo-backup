# discord-channel-backup

A backup repository for an information channel.

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

[MIT](https://choosealicense.com/licenses/mit/)

## Run Instructions

- `npm install`
- (create and configure `config.json` file)
- `npm start`
