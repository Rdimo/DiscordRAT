<p align="center">
<img src="https://img.shields.io/github/languages/top/Rdimo/DiscordRAT?style=flat-square" </a>
<img src="https://img.shields.io/github/last-commit/Rdimo/DiscordRAT?style=flat-square" </a>
<img src="https://img.shields.io/github/stars/Rdimo/DiscordRAT?color=333333&label=Stars&style=flat-square" </a>
<img src="https://img.shields.io/github/forks/Rdimo/DiscordRAT?color=333333&label=Forks&style=flat-square" </a>
</p>
</p>
<p align="center">
<a href="https://github.com/Rdimo/DiscordRAT#setting-up-the-rat">Setting up the RAT</a> |
<a href="https://github.com/Rdimo/DiscordRAT#commands">Commands</a> |
<a href="https://github.com/Rdimo/DiscordRAT#credits">Credits</a> |
<a href="https://Cheataway.com">Discord</a>
</p>

#### DiscordRAT was made by
Love ❌ code ✅

## ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ 🌟Star This Repository If You Liked This DiscordRAT!

### 🔰・Features
* ` Slash Commands!`
* ` 25+ Malicious Commands`
* ` Buttons and Dropdowns/selection menus`
* ` Easy to setup and use`
* ` Up-to-date/modern version of https://github.com/Sp00p64/DiscordRAT`

### 🤖・Commands
```
> kill
kills all inactive sessions

> exit
stop the program on victims pc

> info
gather info about the user

> startkeylogger
start a key logger on their pc

> stopkeylogger
stop the key logger

> KeyLogDump
dumb the keylogs

> tokens
get all their discord tokens

> windowstart
start the window logger

> windowstop
stop window logger

> webcam
takes a video of their webcam

> screenshot
take a screenshot

> MaxVolume
set their sound to max

> MuteVolume
set their sound to 0

> Wallpaper
Change their wallpaper

> Shell
run shell commands on their pc

> Write
Make the user type what ever you want

> Clipboard
get their current clipboard

> AdminCheck
check if DiscordRAT has admin perms

> IdleTime
check for how long your victim has been idle for

> BlockInput
Blocks user's keyboard and mouse

> UnblockInput
UnBlocks user's keyboard and mouse

> MsgBox
make a messagebox popup on their screen with a custom message

> Play
Play a chosen youtube video in background

> Stop_Play
stop the video

> AdminForce
try and bypass uac and get admin rights

> Startup
Add the program to startup
```
### 📁・Setting up the RAT
1. Start off by ofc installing [python](https://www.python.org/)
2. do `git clone https://github.com/Rdimo/DiscordRAT.git` and open a cmd in the same directory and type `pip install -r requirements.txt`
3. Now time to get the bot token, follow this guide [here](https://www.writebots.com/discord-bot-token) on how to do that
4. After you got your token you need to enable intents for the bot
<img alt="Intents" src="https://cdn.discordapp.com/attachments/828047793619861557/888421741590884372/Screenshot_2021-09-17_154808.png">

5. Go into main.py
   - go to where it says `token = 'BOT_TOKE_HERE'` (line 35)
     - Replace `BOT_TOKE_HERE` with your bot token that you got from the [developer page](https://discord.com/developers)
       - go to where it says `g = [GUILD_ID_HERE]` (line 36)
         - Replace `GUILD_ID_HERE` with the id of your server that you want the bot to be in ([server id?](https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID))
6. Now your ready to invite your bot to your server, go to the the [developer page](https://discord.com/developers) and go to the page `OAuth2` and enable these options
<img alt="OAuth2" src="https://cdn.discordapp.com/attachments/905814376043401249/906199066965336094/unknown.png">

7. now copy the given url and paste it in your browser to invite the bot to your server
8. When your done with all of that, simply open **build-exe.bat** and enter a name for the exe and now your done!

---

### 🎉・Credits
Although this discord rat was created by me (Rdimo#6969) the original is https://github.com/Sp00p64/DiscordRAT and credits goes to him and his discord rat. His is quite old and uses message event to execute his commands so thought I would do slash commands and added/improved/removed some commands aswell. Additionally some code for the commands belong to him

---

|⚠️・this Discord rat was made for educational purposes・⚠️|
|-------------------------------------------------|
By using DiscordRAT, you agree that you hold responsibility and accountability of any consequences caused by your actions
