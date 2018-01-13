# CryptoBot for Discord
A bot for [Discord](https://discordapp.com/) that provides utilities for cryptocurrency traders. Run it in your Discord server and users can call various commands that fetch current information from crypto-exchanges like Binance. CryptoBot uses Node.js and the [Node Binance API wrapper](https://github.com/jaggedsoft/node-binance-api). 

## Bot Setup
Install the latest versions of Node.js and the [Node Binance API wrapper](https://github.com/jaggedsoft/node-binance-api). Clone or download this repository. Replace the token in the `auth.json` with the your own token genereated from the [app section of your Discord account](https://discordapp.com/developers/applications/me). Add the bot to your server.

When you're ready, navigate to this repo and run:
```
node bot.js
```

Your bot should be ready to go.


## Commands

`!help` provides a list of commands available to the user
`!vol <MARKET>` returns the current 24-hour volume of a specified market on Binance 

