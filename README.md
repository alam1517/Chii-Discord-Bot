# Chii Discord Bot

Chii is a personal Discord bot that is in continuous development. It uses [Discord](https://github.com/discord/discord-api-docs), [Youtube](https://github.com/ytdl-org/youtube-dl), & [OpenWeather](https://openweathermap.org/current) APIs.

Invite Chii to your server [here](https://discord.com/api/oauth2/authorize?client_id=788205742188003368&permissions=8&scope=bot)!

## 🔧 Features
* Welcome new members to the server via direct message
* Respond back to certain messages
* React to certain messages
* Display guild/server information
* Simple probability/chance
* Play audio (Youtube)
* Display the weather for a city

## ⚙ Setup/Installation
You can invite Chii to your server using this [link](https://discord.com/api/oauth2/authorize?client_id=788205742188003368&permissions=8&scope=bot)!
Alternatively, you can clone this repo and host it yourself:
```
git clone https://github.com/alam1517/Chii-Discord-Bot.git
```
Before starting, making sure that you have latest version of python3 and python3-pip.
To check, do the following:
```
python3 --version
pip --version
```
If you do not have either or both installed, do the following:
```
sudo apt-get install python3
sudo apt-get install python3-pip
```
Afterwards, you will need to install the other libraries/APIs if you do not have it:
```
pip install -U discord.py

pip install -U youtube_dl
```

## 🤖 Commands List:
The prefix for these commands is `-`. Arguments encased with `[]` are required.


### 🧑‍🤝‍🧑 Guild
| Command | Description                          | Usage   |
|---------|--------------------------------------|---------|
| Guild   | Display the guild/server information | -guild  |
| Server  | Display the guild/server information | -server |

### 🪙 Probability/Chance 
| Command  | Description                      | Usage           |
|----------|----------------------------------|-----------------|
| Coinflip | Flips a coin                     | -coinflip       |
| Rolldice | Rolls a dice                     | -rolldice       |
| Choose   | Chooses a number between n and m | -choose [n] [m] |

### 🎵 Music
| Command | Description                                   | Usage                |
|---------|-----------------------------------------------|----------------------|
| Play    | Play music using, so far, Youtube links       | -play [Youtube Link] |
| Exit    | Exit the bot from voice channel               | -exit                |
| Pause   | Pauses the music the bot is currently playing | -pause               |
| Resume  | Resumes the music from bot if it is paused    | -resume              |
| Stop    | Stops the music the bot is playing            | -stop                |

### ☀ Weather
| Command | Description                            | Usage           |
|---------|----------------------------------------|-----------------|
| Weather | Display weather information for a city | -weather [City] |

## ✔ TODOs
Chii is still in development and will be adding new features/updates at an upcoming time.
Below are ideas that I would like to implement:
- [x] React to certain string messages
- [ ] Add game command where users could interact with it
- [ ] Add other APIs to it:
  - [ ] Spotify
  - [x] Weather
  - [ ] Image-based
- [ ] Host it in the cloud (using [repl.it](https://repl.it) or some other alternative) or locally (using raspberry pi)
- [ ] Organize the project more (seperate certain functions into different file)
- [x] Add server info command to show info of current server

And more will be added.
