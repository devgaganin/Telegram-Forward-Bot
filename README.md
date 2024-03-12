# Telegram Forwarder Bot

This Telegram bot facilitates the forwarding of messages from one channel to another. It ensures that both the source and destination channels have administrative privileges for successful message forwarding. Additionally, it supports authorization and cancellation commands for enterprise and production-level use.

## Features

- **Message Forwarding**: Seamlessly forward messages from the old channel to the new channel.
- **Authorization Control**: Utilize `/auth` and `/unauth` commands to manage user access to the bot.
- **Cancellation Support**: Employ the `/cancel` command to halt ongoing message forwarding.

## Setup

1. **Fork the repo**: For the repo with your own name.
2. **Fill Bot Token and User ID**: In the `main.js` file, replace `botToken` with your bot token and `ownerUserId` with your ID.
3. **Deploy the Bot**: Deploy the bot by clicking the following link:
   [![Deploy on Heroku](https://img.shields.io/badge/Deploy%20on%20Heroku-4e5d71?style=for-the-badge&logo=heroku)](https://heroku.com/deploy)

## Usage

### Authorization Commands

- `/auth <user_id>`: Authorize a user to access the bot.
- `/unauth`: Revoke authorization for a user.

### Message Forwarding

1. Start the bot.
2. Provide the source channel ID, destination channel ID, start message ID, and end message ID when prompted.
3. The bot will forward messages from the specified range.

### Cancellation Command

- `/cancel`: Cancel ongoing message forwarding.

## Contact

- **Website**:  [![Website](https://img.shields.io/badge/Visit%20Website-4e5d71?style=for-the-badge&logo=dev.to)](https://devgagan.in)
- **Telegram**:  [![Telegram](https://img.shields.io/badge/Join%20Telegram-4e5d71?style=for-the-badge&logo=telegram)](https://t.me/dev_gagan)
- **YouTube**:  [![YouTube](https://img.shields.io/badge/Watch%20on%20YouTube-4e5d71?style=for-the-badge&logo=youtube)](https://youtube.com/@dev_gagan)

## Dependencies

- [node-telegram-bot-api](https://www.npmjs.com/package/node-telegram-bot-api): Library to interact with the Telegram Bot API.

## License

This project is licensed under the [MIT License](LICENSE).
