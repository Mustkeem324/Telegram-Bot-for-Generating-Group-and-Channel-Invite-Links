# Telegram-Bot-for-Generating-Group-and-Channel-Invite-Links

This Telegram bot allows users to generate invite links for groups and channels, as well as retrieve information about users, channels, and groups.

## Prerequisites

- Python 3.x
- `telebot` library
- `python-dotenv` library

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your_username/telegram-bot.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Set up environment variables:
   
Create a `.env` file in the project root and add your Telegram bot token:

```plaintext
TOKEN=<your_bot_token>
```

## Usage

1. Run the bot:

```bash
python bot.py
```

2. Interact with the bot in your Telegram group or channel using the following commands:

- `/invite`: Generate an invite link for the current group or channel.
- `/info <username or channel/group ID>`: Retrieve information about a user, channel, or group.
- `/geninvite <username or channel/group ID>`: Generate an invite link for the specified channel or group.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to fork this repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
