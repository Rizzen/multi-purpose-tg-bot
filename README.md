Multi-purpose Telegram Bot
======
**Multi-purpose Telegram Bot** is a telegram bot inside a ASP.NET Core app.

The main idea of this bot is use of a architecture where bot uses filters and corresponding hadlers to handle updates recieved from Telegram.

That way you don't need to have single handler that handles all kinds of messages.
What you have are **the** router and many filters that decide what handler will handle new recieved message. Thus handlers have only one responsibility - get some information from a message and do something with it.

### Third party libraries
* [Telegram.Bot library](https://github.com/TelegramBots/Telegram.Bot)

### License 
* [MIT License](https://github.com/admiralWoop/multi-purpose-tg-bot/blob/master/LICENSE)
