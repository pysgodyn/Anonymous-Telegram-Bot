# Anonymous Telegram Bot
This project is a Telegram bot. The bot itself acts as a secure wall between other users and yourself, making you anonymous while providing text replies to the other users. The idea behind this bot is for people who own public channels and don't want to expose their private profiles to everybody.

It has been developed using **Python v3.5** and [*Python Telegram Bot*](https://python-telegram-bot.readthedocs.io/en/stable/) v11.1.0
> Python2.7 release [here](https://github.com/fndh/Anonymous-Telegram-Bot/releases/tag/b784a13)

# How to set it up
1. First you will need a bot token, which you can obtain from the [@BotFather](https://t.me/BotFather).
2. Make sure you have installed the [*Python Telegram Bot*](https://python-telegram-bot.readthedocs.io/en/stable/) library (v11.1.0).
3. Download this project and edit the file **config.txt**
   * Add your bot token
   * Add the system path to the folder
   * Add your telegram user ID. It is a unique identifier that can be found in your profile
4. Launch AnonymousForwardBot.py
5. Start your bot by sending a /start command in Telegram

# How to use it
1. When a user messages the bot you are hosting, the bot will forward their message to you. This step works for all kind of messages, be it images, audio, stickers, text, ... you name it.
2. You can choose to ignore the message or reply to it. If you choose to reply to the forwarded message, the bot will send the text to the user at the other end of the conversation.

# Future improvements

- [x] Updated to Python v3
- [ ] Allow non-text replies
- [ ] Implement multi-column keyboard in owner /help messages

You can find the changelog [here](https://github.com/fndh/Anonymous-Telegram-Bot/wiki/Changelog)

# Contact
You can contact me via Telegram &rarr; [@Fndh_Anonymous_Bot](https://t.me/Fndh_Anonymous_Bot)
