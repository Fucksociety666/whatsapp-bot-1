<div align="center">
<img src="http://piyobot.000webhostapp.com/822161.png" alt="Piyobot" width="400" />

# Piyobot

> Piyobot Adalah Bot Whatsapp Yang Sangat Kontol
> BACA README GOBLOK BIAR LU TAU BELI APIKEYNYA DIMANA
>

<img src="https://raw.githubusercontent.com/AlvioAdjiJanuar/lord/master/videoplayback-2-online-video-cut.gif">

<p align="center">
  <a href="https://github.com/AlvioAdjiJanuar"><img title="Author" src="https://img.shields.io/badge/Author-AlvioAdjiJanuar-darkred.svg?style=for-the-badge&logo=github" /></a>
</p>


# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip) (for sticker GIF command)
* Any text editor
* [Magisk](https://download.imagemagick.org/ImageMagick/download/binaries/ImageMagick-7.0.10-58-Q16-HDRI-x64-dll.exe) (Buat nuliskanan kiri folio kanan kiri)

# installation
## 📝 Cloning this repo
```bash
> git clone https://github.com/IndonesianDev/whatsapp-bot
> cd whatsapp-bot
```

## ✍️ Edit filenya
Edit value yang diperlukan di `settings/setting.json`.
```json
{
    "limitCount": 10,
    "ownerNumber": "",
    "memberLimit": 10,
    "groupLimit": 50,
    "medialimitCount": "5",
    "prefix": "/",
    "vhtearkey": "Your Apikey In Here",
    "apikeyz": "Your Apikey In Here",
    "apikeyx": "Your Apikey In Here",
    "itech": "Your Apikey In Here"
}

```

`ownerBot`: your WhatsApp number.  
`prefix`: bot's prefix.  
`itech`: API token. Anda bisa mendapatkannya https://api.i-tech.id dengan membuat akun. Setelah itu, setel IP statis server / host Anda di https://api.i-tech.id/settings/profile. 

`vhtearkey`: VHTear API token. Anda bisa mendapatkannya https://api.vhtear.com/ dengan membeli kunci API.
`apikeyz`: Hujan Api token. Anda Bisa Mendapatkannya https://hujanapi.xyz

`apikeyx`: Naufal Hoster token. Anda Bisa Mendapatkannya https://naufalhoster.xyz

## 🔍 Menginstal dependensi
```bash
> npm install
```

## 🆗 Menjalankan bot
Regular node:
```bash
> npm start
```

PM2:
```bash
> pm2 start index.js
> pm2 monit
```

PM2 with cron job (restart after 5 hours):
```bash
> pm2 start index.js --cron "* */5 * * *"
> pm2 monit
```

Setelah itu pindai kode QR menggunakan WhatsApp Anda di ponsel Anda!

# Features


|     Sticker Maker     | Availability |
| :-------------------: | :----------: |
| Send/reply image      |      ✔️      |
| Send/reply GIF        |      ✔️      |
| Send/reply MP4        |      ✔️      |
| Text to sticker       |      ✔️      |
| Text to sticker GIF   |      ✔️      |
| Sticker to image      |      ✔️      |

|     Money Feature     | Availability |
| :-------------------: | :----------: |
| Money Check           |      ✔️      |
| Buy Limit             |      ✔️      |
| Transfer Money        |     Soon      |

|      Downloader     | Availability |
| :-----------------: | :----------: |
| Facebook video      |      ✔️      |
| YouTube audio/video |      ✔️      |
| Joox                |      ✔️      |
| TikTok              |      ✔️      |
| TikTok NoWm         |      ✔️      |
| Twitter             |      ✔️      |
| Instagram post      |      ✔️      |
| Instagram story     |      ✔️      |
| Layarkaca21 film    |      ✔️      |

|        Other        | Availability |
| :-----------------: | :----------: |
| Say                 |      ✔️      |
| Lyric finder        |      ✔️      |
| Shortlink maker     |      ✔️      |
| Wikipedia           |      ✔️      |
| KBBI search         |      ✔️      |
| IG stalk            |      ✔️      |
| SpekHp              |      ✔️      |
| Food receipt finder |      ✔️      |
| TTS                 |      ✔️      |
| AFK                 |      ✔️      |
| Distance            |      ✔️      |
| Find sticker        |      ✔️      |
| List surah          |      ✔️      |
| Math                |      ✔️      |
| Surah               |      ✔️      |
| Random contact      |      ✔️      |
| Play YouTube        |      ✔️      |
| Tafsir Al-Qur'an    |      ✔️      |
| LK21                |      ✔️      |
| Reminder            |      ✔️      |
| Image to URL        |      ✔️      |
| Jadwal sholat       |      ✔️      |
| To Mp3              |      ✔️      |
| Bass                |      ✔️      |
| FishEye             |      ✔️      |
| Line sticker latest |      ✔️      |
| Cek ongkir          |      ✔️      |

|          Fun          | Availability |
| :-------------------: | :----------: |
| Send                  |      ✔️      |
| Mutualan              |      ✔️      |
| Harta tahta maker     |      ✔️      |
| Zodiac                |      ✔️      |
| Write on paper        |      ✔️      |
| Missing person maker  |      ✔️      |
| Valentine frame maker |      ✔️      |
| Glitch text maker     |      ✔️      |
| SimSimi               |      ✔️      |
| Blackpink logo maker  |      ✔️      |
| Pornhub logo maker    |      ✔️      |
| Galaxy text maker     |      ✔️      |
| TikTok asupan         |      ✔️      |
| PH comment maker      |      ✔️      |
| Triggered effect      |      ✔️      |
| Deep fry effect       |      ✔️      |
| Kiss someone          |      ✔️      |
| 3D Text               |      ✔️      |
| Freefire logo         |      ✔️      |
| Freefire banner       |      ✔️      |

|      Weeb Zone     | Availability |
| :----------------: | :----------: |
| Random neko girl   |      ✔️      |
| Random wallpaper   |      ✔️      |
| Kusonime scrapper  |      ✔️      |
| Komiku scrapper    |      ✔️      |
| Anime tracer       |      ✔️      |
| Source finder      |      ✔️      |
| Random waifu       |      ✔️      |

|        Bot       | Availability |
| :--------------: | :----------: |
| Bot usage status |      ✔️      |
| Blocked list     |      ✔️      |
| Ping             |      ✔️      |
| Delete message   |      ✔️      |
| Report bug       |      ✔️      |

|        Owner       | Availability |
| :----------------: | :----------: |
| Broadcast          |      ✔️      |
| Clear all messages |      ✔️      |
| Leave all groups   |      ✔️      |
| Ban                |      ✔️      |
| Add premium user   |      ✔️      |

|    Moderation    | Availability |
| :--------------: | :----------: |
| Add              |      ✔️      |
| Kick             |      ✔️      |
| Promote          |      ✔️      |
| Demote           |      ✔️      |
| Leave bot        |      ✔️      |
| Tag All          |      ✔️      |
| Set Icon Grup    |      ✔️      |
| Anti-group link  |      ✔️      |
| Toogle welcome   |      ✔️      |
| Auto-sticker     |      ✔️      |
| Mute group       |      ✔️      |

|        18+         | Availability |
| :----------------: | :----------: |
| Fetish             |      ✔️      |
| Waifu NSFW         |      ✔️      |
| Waifu 18+          |      ✔️      |
| Xvideos            |      ✔️      |
| Xvidl              |      ✔️      |
| Xnxx               |      ✔️      |
| Xnxxdl             |      ✔️      |
| nHentai downloader |      ✔️      |


# Thanks to
* [`open-wa/wa-automate-nodejs`](https://github.com/open-wa/wa-automate-nodejs)
* [`AlvioAdjiJanuar`](https://github.com/AlvioAdjiJanuar)
* [`dxxoo`](https://github.com/dxxoo)
