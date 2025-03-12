<p align="center">
<img src="https://img95.pixhost.to/images/1083/472612217_8876.jpg" width="350" height="350"/>
</p>
<h1 align="center">🤖 LBot - WhatsApp Bot 🤖</h1>
<p align="center">
<a href="https://www.codefactor.io/repository/github/victorsouzaleal/lbot-whatsapp"><img src="https://img.shields.io/codefactor/grade/github/victorsouzaleal/lbot-whatsapp?label=quality&color=#79C83D" alt="CodeFactor" /></a>
</p>
<p align="center">
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fvictorsouzaleal%2Flbot-whatsapp&count_bg=%234dc61f&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=views&edge_flat=false"/></a>
<a href="#"><img title="Version" src="https://img.shields.io/github/package-json/v/victorsouzaleal/lbot-whatsapp?label=version&color=#79C83D"/></a>
<a href="https://github.com/victorsouzaleal/followers"><img title="Followers" src="https://img.shields.io/github/followers/victorsouzaleal?label=followers&style=flat&color=#79C83D"/></a>
<a href="https://github.com/victorsouzaleal/lbot-whatsapp/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/victorsouzaleal/lbot-whatsapp?label=stars&style=flat&color=#79C83D"></a>
<a href="https://github.com/victorsouzaleal/lbot-whatsapp/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/victorsouzaleal/lbot-whatsapp?label=watching&style=flat&color=#79C83D"></a>
<a href="https://github.com/victorsouzaleal"><img title="Author" src="https://img.shields.io/badge/author-victorsouzaleal-blue.svg?logo=github&color=#79C83D"></a>
</p>

<br>

<h2 align="center"> 🔄 Last Update: <a href="https://github.com/victorsouzaleal/lbot-whatsapp/releases/latest">HERE</a> </h2>

<br>

## 🚨 REQUIREMENTS:
- A phone number connected to WhatsApp to scan the QR Code and connect the bot.
- On **Windows/Linux** :<br>
        - Install [GIT](https://git-scm.com/) <br>
        - Install [NODE LTS VERSION](https://nodejs.org/en/)
- On **Termux** :<br>
        - Install [TERMUX](https://github.com/termux/termux-app/releases/download/v0.118.0/termux-app_v0.118.0+github-debug_universal.apk) on your phone

<br>

## 1 - 💿 Installation:

### 🖥️ Windows/Linux:

Download the latest released version from the following link: https://github.com/victorsouzaleal/lbot-whatsapp/releases/latest, extract the zip, and enter the bot folder for the next steps.

Open the command prompt (terminal) **INSIDE THE PROJECT FOLDER** and execute the following commands:

* 1.1 - Install yarn (if on Linux, use sudo before the command)
```bash
npm i -g yarn
```

* 1.2 - Install project dependencies
```bash
yarn install
```

<br>

### 📱 Termux:
For the Termux installation guide:  [Click HERE](docs/TERMUX.md)

<br>

## 2 - 🤖 Usage:

**Inside the project folder**, after completing all previous steps, execute this command:

```bash
yarn start
```

After the first launch, scan the QR Code with your phone.

<br>

## 3 - ⌨️ Functionality:
After completing all the previous steps, your bot should be running normally. Use the commands below to view available commands.
<br><br>
**!menu** - Access the MAIN MENU.
<br>
**!admin** - Access the ADMINISTRATOR/OWNER MENU.
<br><br>
All commands now have a guide by typing **!command guide**
<br><br>

### Done! Your bot is now ONLINE, but continue reading the next step for configuration!

<br>

## 4 - ⚙️ Bot Configuration and .env File:

### When opening the .env file in the project root after launching the bot for the first time, it will look like this: </br>
        # API KEY CONFIGURATION FOR COMMANDS

        # ACRCLOUD - Enter your ACRCloud keys (Music Recognition) below
        acr_host=?????
        acr_access_key=?????
        acr_access_secret=?????

        # DEEPGRAM - Enter your DEEPGRAM key (Audio to Text Transcription) below
        dg_secret_key=??????

#### How to set up the ADMINISTRATOR:
To use **ADMINISTRATOR** functions, type **!admin** for the first time when starting the BOT, and your number will be registered as the owner.<br><br>
Now you have access to **ADMIN** commands. Use **!botname**, **!adminname**, **!stickername** to customize your bot's name in menus and stickers, and see all admin commands with **!admin**.

<br>

#### How to obtain API keys for specific commands:
To use specific commands like **!whichsong** and **!listen**, you need to configure the API keys in .env first. Below is a complete guide with images on how to obtain the keys.<br><br>
**Detailed information on how to obtain NewsAPI (News), ACRCloud (Music Recognition), and DEEPGRAM (Audio to Text) keys**:  [Click HERE](docs/CHAVESAPI.md)

<br>

## 5 - 🛠️ Features/Commands:

### 🖼️ Stickers
- Photo to sticker ✅
- Video/gif to sticker ✅
- Sticker to photo ✅
- Rename sticker ✅
- Auto sticker ✅

### 📥 Downloads 
- YouTube (video/audio) ✅
- Facebook (video) ✅
- Instagram (video/image) ✅
- Twitter (video/image) ✅
- TikTok (video) ✅
- Google (image) ✅

### ⚒️ General Utilities
- Chat-GPT ✅
- AI Image Creation ✅
- Brazilian League A/B ✅
- Movie/Series Trends ✅
- URL Shortener ✅
- Image Upload ✅
- Audio Effects ✅
- Text to Speech ✅
- Audio to Text ✅
- Song Lyrics ✅
- Music Recognition ✅ 
- DDD Detector ✅
- Weather Forecast ✅
- Currency Conversion ✅
- Calculator ✅
- Google Search ✅      
- Anime Detector ✅     
- Postal Tracking ✅ 
- Google News ✅ 
- Google Translator ✅

<br>

### 👉 And much more... [Click HERE](docs/COMANDOS.md)

<br>

## 6 - 💻 Troubleshooting

### Termux
Some users may face issues installing dependencies on Termux due to an unstable internet connection or an outdated Termux version. The Play Store version of Termux hasn't been updated in years, so here’s an official APK from the Termux developers.

* **Termux APK:** https://github.com/termux/termux-app/releases/download/v0.118.0/termux-app_v0.118.0+github-debug_universal.apk

<br>

## 7 - 👤 Contact
For inquiries, I try to respond to emails, or you can open an issue on GitHub explaining the problem.

* **Email:** victorsouzaleal@gmail.com

<br>

## 8 - 🙏 Acknowledgments/Contributions

* [`WhiskeySockets/Baileys`](https://github.com/WhiskeySockets/Baileys) - Baileys Library.
* [`Samuel/samucacastro`](https://github.com/samucacastro) - API Development

