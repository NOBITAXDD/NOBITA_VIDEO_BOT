# Telegram Video Player Bot [![Mentioned in Awesome](https://awesome.re/mentioned-badge-flat.svg)](https://github.com/tgcalls/awesome-tgcalls)
![GitHub Repo stars](https://img.shields.io/github/stars/AsmSafone/VideoPlayerBot?color=blue&style=flat)
![GitHub forks](https://img.shields.io/github/forks/AsmSafone/VideoPlayerBot?color=green&style=flat)
![GitHub issues](https://img.shields.io/github/issues/AsmSafone/VideoPlayerBot)
![GitHub closed issues](https://img.shields.io/github/issues-closed/AsmSafone/VideoPlayerBot)
![GitHub pull requests](https://img.shields.io/github/issues-pr/AsmSafone/VideoPlayerBot)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/AsmSafone/VideoPlayerBot)
![GitHub contributors](https://img.shields.io/github/contributors/AsmSafone/VideoPlayerBot?style=flat)
![GitHub repo size](https://img.shields.io/github/repo-size/AsmSafone/VideoPlayerBot?color=red)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/AsmSafone/VideoPlayerBot)
![GitHub](https://img.shields.io/github/license/AsmSafone/VideoPlayerBot)
[![Bot Updates](https://img.shields.io/badge/VideoPlayerBot-Updates%20Channel-green)](https://t.me/Thenavya)
[![Bot Support](https://img.shields.io/badge/VideoPlayerBot-Support%20Group-blue)](https://t.me/navyasupport)

An Telegram Bot By [@Navya](https://t.me/WTF_NAVYA) To Stream Videos in Telegram Voice Chat.

## Main Features

- Supports Live Streaming.
- Supports YouTube Streaming.
- Supports Live Radio Streaming.
- Supports Video Files Streaming.
- Supports YouTube Live Streaming.
- User Account Protection (PM Guard)

## Deploy Own Bot

### Railway (Recommended)


[![Deploy+on+Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https://github.com/Navya-developer/VideoPlayerBot&envs=API_ID,API_HASH,BOT_TOKEN,STRING_SESSION,UPDATES_CHANNEL,SUPPORT_GROUP,SUDO_USERS,REPLY_MESSAGE,ASSISTANT_NAME)


### Heroku (Don't Complain)
<p><a href="https://heroku.com/deploy?template=https://github.com/Navya-Developer/VideoPlayerBot"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="200""/></a></p>

## Commands (Set In Botfather)
```sh
start - Start The Bot
help - Show Help Message
play - Start Audio Streaming
stream - Start Video Streaming
pause - Pause The Current Stream
resume - Resume The Paused Stream
endstream - Stop Streaming & Left VC
```

## Config Vars
1. `API_ID` : User Account Telegram API_ID, get it from my.telegram.org
2. `API_HASH` : User Account Telegram API_HASH, get it from my.telegram.org
3. `BOT_TOKEN` : Your Telegram Bot Token, get it from @Botfather XD
4. `SESSION_STRING` : Pyrogram Session String of User Account, get it from [@genStr robot](http://t.me/NAVYaSG_BoT) or [![genStr](https://img.shields.io/badge/repl.it-genStr-yellowgreen)](https://repl.it/@AsmSafone/genStr)
5. `ASSISTANT_NAME` : Your Video Player's assistant username without @.
6. `SUPPORT_GROUP` : Support Group username without @ [Leave this if you don't have one]
7. `UPDATES_CHANNEL` : Updates Channel username without @ [Leave this if you don't have one]
8. `SUDO_USERS` : ID of Users who can use Admins commands (for multiple users seperated by space)
9. `REPLY_MESSAGE` : A reply to those who message the USER account in PM. Leave it blank if you do not need this feature.

## Requirements
- Python 3.6 or Higher.
- Latest [FFmpeg Python](https://www.ffmpeg.org/).
- [Telegram API key](https://docs.pyrogram.org/intro/quickstart#enjoy-the-api).
- Pyrogram [String Session](http://t.me/NAVYaSG_BoT) Of The Account.
- The User Account Needs To Be An Admin In The Group / Channel.

## Self Host
```sh
$ git clone -b main https://github.com/AsmSafone/VideoPlayerBot
$ cd VideoPlayerBot
$ sudo apt-get install python3-pip ffmpeg
$ pip3 install -U pip
$ pip3 install -U -r requirements.txt
# <create .env variables appropriately>
$ python3 main.py
```

## License
```sh
VideoPlayerBot, Telegram Video Chat Bot
Copyright (c) 2021  Asm Safone <https://github.com/AsmSafone>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>
```

## Credits

- [Me](https://github.com/Navya-Developer) for [Noting](https://github.com/Navya-Developer/VideoPlayerBot) 😬
- [Navya](https://github.com/SUSHILxPLAYER) for [Pyrogram](https://github.com/pyrogram/pyrogram) ❤️
- [Shubhi](https://github.com/SUSHILxMUSIC) for [pytgcalls](https://github.com/MarshalX/tgcalls) ❤️
- And Thanks To All [Contributors](https://github.com/navya-Developer/VideoPlayerBot/graphs/contributors)! ❤️
