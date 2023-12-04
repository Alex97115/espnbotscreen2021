# MMA Event Bot
Made this bot as a fiverr mission.

------------------------------------
**Overview:**

This Discord bot fetches the upcoming MMA fight card screenshots for UFC, Bellator, PFL, ONE FC, and Glory Kickboxing from various sources like espn onefc and glory.

------------------------------------
**Installation:**

1. Ensure you have [Node.js](https://nodejs.org/en/) installed for running the bot.

2. Install Puppeteer:
   ```bash
   npm i puppeteer
Install Discord.js:

bash
Copy code
npm install discord.js
Copy your bot token into the config.json file. You can also change the bot command prefix in the same file.

The bot takes approximately 10 to 15 seconds to retrieve the screenshot. Avoid spamming the bot.
If the bot encounters an error, restart it.
Usage:

!ufc : Fetches the next UFC fight card.
!bellator : Fetches the next Bellator fight card.
!pfl : Fetches the next PFL fight card.
!one : Fetches the next ONE FC fight card.
!glory : Fetches the next Glory Kickboxing fight card.
This bot accesses the links using the Puppeteer headless browser.

Dependencies:

Discord.js
Puppeteer