### Telegram Radio Player V2
An Telegram Bot to Play Radio/Music in Channel or Group Voice Chats.

  </a>
</p>
<p align="center">
  <a href="https://github.com/DarkAngel1234-tech/RadioPlayerV2/stargazers">
    <img src="https://img.shields.io/github/stars/DarkAngel1234-tech/RadioPlayerV2?style=social">

  </a>
  
  <a href="https://github.com/DarkAngel1234-tech/RadioPlayerV2/fork">
    <img src="https://img.shields.io/github/forks/DarkAngel1234-tech/RadioPlayerV2?label=Fork&style=social">

  </a>  
</p>


<details><summary>Special Features</summary>
<p>
<pre>
- Playlist, queue, 24x7 radio stream
- Loop one track when there is only one track in the playlist
- Automatically downloads audio for the first two tracks in the playlist to ensure smooth playing
- Show current playing position of the audio
- Control with buttons and commands
- Download songs from youtube as audio
</pre>
</p>
</details>

Deploy to Heroku (The Easy Way)

<details><summary>Deploy To Heroku</summary>
<p>
<br>

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/DarkAngel1234-tech/RadioPlayerV2)
</a>
</p>
</details>


<details><summary>Heroku Vars</summary>
<p>
<pre>
1. `API_ID` : Get From @MT_MyTelegramOrg_Bot
2. `API_HASH` : Get From @MT_MyTelegramOrg_Bot
3. `BOT_TOKEN` : Get it From @Botfather
4. `SESSION_STRING` : Generate From [MT_Session_Replit](https://replit.com/@CYBERDUDE3/String-Gen-1#main.py).
5. `CHAT` : ID of Channel/Group where the bot plays Music/Radio.
6. `LOG_GROUP` : Group to send Playlist, if CHAT is a Group.
7. `ADMINS` : ID of users who can use admin commands.
8. `STREAM_URL` : Stream URL of radio station to stream when the bot starts or with /radio command.

- Enable the worker after deploy the project to Heroku.
- Bot will starts radio automatically in given `CHAT` with given `STREAM_URL` after deploy. 
- 24x7 Music even if heroku restarts, radio stream restarts automatically.  
- To play a song just send the audio file to Bot or reply to an audio with `/play` to start playing it in the voice chat.
- To download audio you can use `/song` command to the bot.
- Use `/help` to know about other commands & its usage.
</pre>
</p>
</details>

<details><summary>Requirements</summary>
<p>
<pre>
- Python 3.6 or higher.
- A
  Telegram API key 👉 https://docs.pyrogram.org/intro/quickstart#enjoy-the-api
  and a Telegram account.
- [FFmpeg Python 👉 https://www.ffmpeg.org/
- Telegram String Session 👉 http://t.me/MT_UserSession_BoT of the account.
- Userbot Needs To Be Admin In The Channel or Group.
- Must Start A Voice Chat In Channel/Group Before Running The Bot.
</pre>
</p>
</details>

<details><summary>Run On VPS (The Hard Way)</summary>
<p>
<pre>
$ git clone 👉 https://github.com/DarkAngel1234-tech/RadioPlayerV2
$ cd RadioPlayerV2
$ sudo apt-get install ffmpeg
$ pip3 install -U pip
$ pip3 install -U -r requirements.txt
```
Edit **config.py** with your own values.

$ python3 main.py
</pre>
</p>
</details>

<details><summary>License</summary>
<p>
<pre>
RadioPlayerV2, Telegram Voice Chat Userbot
Copyright (C) 2021  Asm Safone

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
</pre>
</p>
</details>

<details><summary>credit</summary>
<p>
<br>
👨‍💼Asm Safone - Developer
👨‍💻DarkAngel1234-tech
👨‍💻Mrk YT

<img src="https://telegra.ph/file/5544537e87a05e0785147.jpg" width="200" height="200"><br> <img src="https://badgen.net/badge/Name/DarkAngel/FF33FF?icon=awesome&labelColor=0080FF"></a>
<img src="https://badgen.net/badge/Skills/Python/purple?icon=terminal&labelColor=red"></a> <a href="https://github.com/DarkAngel1234-tech"><img src="https://badgen.net/badge/Follow%20on%20/Github/80FF00?icon=github&labelColor=black"></a>
<a href="https://youtube.com/channel/UCmGBpXoM-OEm-FacOccVKgQ"><img src="https://img.shields.io/badge/YouTube-Channel-FF3333.svg?logo=youtube&logoColor=FF3333"></a>
<a href="https://telegram.dog/DarkAngel1234"><img src="https://img.shields.io/badge/Telegram-Link-blue.svg?logo=telegram"></a>

                                                          
<img src="https://telegra.ph/file/9e831d15da94deb56ef4c.jpg" width="200" height="200"><br>
<img src="https://badgen.net/badge/Name/Mrk YT/FF33FF?icon=awesome&labelColor=0080FF"></a>
<img src="https://badgen.net/badge/Skills/😞/purple?icon=terminal&labelColor=red"></a>
<a href="https://telegram.dog/MRK_yt"><img src="https://img.shields.io/badge/Telegram-Link-blue.svg?logo=telegram"></a>
<a href="https://github.com/MRK-YT"><img src="https://badgen.net/badge/Follow%20on%20/Github/80FF00?icon=github&labelColor=black"></a>
<a href="https://youtube.com/channel/UCmGBpXoM-OEm-FacOccVKgQ"><img src="https://img.shields.io/badge/YouTube-Channel-FF3333.svg?logo=youtube&logoColor=FF3333"></a>
<a href="https://Instagram.com/mrk_yt_"><img src="https://badgen.net/badge/Follow%20on%20/Instagram/80FF00?icon=Instagram&labelColor=black"></a>                                                                                                        

[![Open Source? Yes!](https://badgen.net/badge/Oᴘᴇɴ%20Sᴏᴜʀᴄᴇ%20%3F/Yᴇs/yellow?icon=github)](https://github.com/MRK-YT/Pro-Auto-Filter-Bot-V2)
[![Ask Me Anything !](https://img.shields.io/badge/🤔%20Ask%20Me-Anything-1abc9c.svg)](https://telegram.dog/Mrk_Yt)
[![Report Bugs!](https://badgen.net/badge/🐞%20Report%20/Bugs/red)](https://telegram.dog/mrk_yt)
[![Join Channel !](https://badgen.net/badge/🔊%20Join%20/Channel/Black)](https://telegram.dog/mo_Tech_yt)

Join Our [Telegram Group](https://www.telegram.dog/Mo_Tech_Group) For Support/Assistance And Our [Channel](https://www.telegram.dog/Mo_Tech_YT) For Updates.   
   
Report Bugs, Give Feature Requests There..   
Do Fork And Star The Repository If You Liked It.
</a>
</p>
</details>


