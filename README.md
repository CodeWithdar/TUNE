[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/eritislami/evobot)

# 🎵 Tune (Discord Music Bot)
> Tune is a bot made using discord.js [discordjs.guide](https://discordjs.guide)

## Installation

1. How to obtain a Discord Bot Token **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**
2. YouTube Data API v3 Key **[Guide](https://developers.google.com/youtube/v3/getting-started)**  
3. SoundCloud doesn't provide API anymore**
4. Node.js v12.0.0 or newer

---

## 🔎 Making The Project

After installation finishes you can use `node index.js` to start the bot.

```
Type (npm i) in console
```

🚨🚨 **Commiting your token to be accessed by others or making it public is strictly prohibited.So, dont share your token in any cost or use .gitignore to hide secrets** 🚨🚨

```json
{
  "TOKEN": "",
  "YOUTUBE_API_KEY": "",
  "SOUNDCLOUD_CLIENT_ID": "",
  "MAX_PLAYLIST_SIZE": 10,
  "PREFIX": "/",
  "PRUNING": false,
  "STAY_TIME": 30,
  "LOCALE": "en",
  "support_server": "",
  "DEFAULT_VOLUME": 100
}
```

Currently available locales are:

• English (en)
• French (fr)
• Spanish (es)
• Turkish (tr)
• Korean (ko)
• Brazilian Portuguese (pt_br)
• Simplified Chinese (zh_cn)
• Traditional Chinese (zh_tw)

## 📝 Features & Commands

> Note: The default prefix is '/'

* 🎶 Using YouTube Url

`/play https://www.youtube.com/c/Vevo`

* 🔎 Playing music via Name

`/play FatRat Fire`

* 🔎 Search and play

`/search Imperial March Trap Remix by Goblins from Mars`

