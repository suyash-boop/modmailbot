# ✨ Updating the bot

**Before updating the bot, always take a backup of your `db/data.sqlite` file.**

To update the bot, follow these steps:
1. Shut down the bot
2. Take a backup of your `db/data.sqlite` file
    * If you're using a different supported database, take database backups from there
3. Download the latest version of the bot from https://github.com/Dragory/modmailbot/releases/latest
4. Extract the new version's files over the old files
5. Read the [CHANGELOG](https://github.com/Dragory/modmailbot/blob/master/CHANGELOG.md) to see if there are any config changes you have to make
    * Especially note changes to supported Node.js versions!
6. Start the bot:
    * If you're using `start.bat` to run the bot, just run it again
    * If you're running the bot via command line, first run `npm ci` and then start the bot again

👉 If you run into any issues, **[join the support server for help!](https://discord.gg/vRuhG9R)**