# 🎵 MISAKI Bot

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Python](https://img.shields.io/badge/python-3.10+-brightgreen)
![Discord.py](https://img.shields.io/badge/discord.py-2.0+-blue)
![Status](https://img.shields.io/badge/status-active-success)

**A powerful multi-server Discord music bot with advanced features and intuitive controls.**

---

## 📖 About MISAKI Bot

MISAKI is a feature-rich Discord music bot designed to provide seamless audio entertainment across multiple servers simultaneously. Built with Python and Discord.py, it offers high-quality music streaming from various platforms with an easy-to-use interface and powerful control features.

### ✨ Key Features

- 🎶 **Multi-Platform Support**: Play music from YouTube, Spotify, JioSaavn, and SoundCloud
- 🌐 **Multi-Server Compatible**: Run in unlimited servers with independent settings and queues
- 🎛️ **Advanced Audio Filters**: 10+ audio effects including nightcore, bassboost, vaporwave, and more
- 📝 **Custom Prefixes**: Each server can set its own command prefix
- 🔄 **24/7 Mode**: Keep the bot connected to voice channels around the clock
- 🎯 **Interactive Controls**: Button-based music player with full playback control
- 📜 **Smart Queue Management**: Shuffle, loop, move, swap, and skip tracks with ease
- 🔍 **Similar Track Suggestions**: AI-powered music recommendations
- 💾 **Playback History**: Track and replay your music history
- 🎨 **Clean UI**: Beautiful embeds with thumbnails and progress indicators
- ⚡ **Low Latency**: Fast response times and reliable performance

---

## 🎯 What Makes MISAKI Special?

### 🎮 Interactive Music Player
- Play/Pause, Skip, Previous, Loop, Shuffle
- Rewind/Forward (10s jumps)
- Replay current track
- Built-in filter selector
- One-click similar track discovery

### 🎨 Audio Customization
- **Filters**: Nightcore, Bassboost, Vaporwave, Karaoke, Tremolo, Vibrato, Rotation, Distortion, Channel Mix
- **Volume Control**: Adjustable from 1-150%
- **Equalizer**: Fine-tune your audio experience

### 📊 Queue Features
- View queue with pagination
- Skip to specific positions
- Move, swap, and duplicate tracks
- Reverse queue order
- Clear queue
- Queue statistics

### 🔧 Server Management
- Custom prefix per server
- Server-specific playlists and history
- Independent 24/7 mode per server
- Auto-join voice channels
- Inactivity timeout protection

---

## 🎵 Supported Platforms

| Platform | Search | Playlists | Albums |
|----------|--------|-----------|--------|
| YouTube | ✅ | ✅ | ✅ |
| Spotify | ✅ | ✅ | ✅ |
| JioSaavn | ✅ | ✅ | ✅ |
| SoundCloud | ✅ | ✅ | ✅ |

---

## 🚀 Command Categories

### 🎵 Music Commands
`play`, `search`, `pause`, `resume`, `skip`, `stop`, `loop`, `shuffle`, `nowplaying`, `queue`, `volume`, `replay`, `seek`, `jump`

### 🎛️ Queue Management
`clearqueue`, `move`, `remove`, `swap`, `skipto`, `reverse`, `duplicate`

### 🎨 Audio Filters
`nightcore`, `bassboost`, `vaporwave`, `karaoke`, `tremolo`, `vibrato`, `rotation`, `distortion`, `channelmix`, `clearfilters`

### 📜 History & Discovery
`showhistory`, `clearhistory`, `similar`, `grab`

### 🔧 Configuration
`prefix`, `247`, `join`, `disconnect`, `serverinfo`, `playerstats`, `queueinfo`

### 📚 Information
`help`, `serverinfo`

---

## 💡 Usage Examples

```bash
# Play a song
/play Never Gonna Give You Up
>play https://www.youtube.com/watch?v=dQw4w9WgXcQ

# Search across platforms
/search lofi hip hop

# Apply audio filters
/nightcore
/bassboost

# Manage queue
/shuffle
/loop
/move 3 1

# Get similar tracks
/similar

# Configure server
/prefix !
/247
```

---

## 🏗️ Technical Stack

- **Language**: Python 3.10+
- **Framework**: Discord.py 2.0+
- **Audio Library**: Wavelink (Lavalink)
- **Database**: SQLite3
- **Dependencies**: aiohttp, python-dotenv

---

## 🌟 Core Functionalities

### Multi-Server Architecture
Each server gets:
- Independent music queue
- Separate playback history
- Custom prefix settings
- Individual 24/7 mode configuration
- Isolated database entries

### Intelligent Music Management
- Automatic queue progression
- Loop modes (single track, queue)
- Smart similar track discovery
- Playback history (last 10 tracks)
- Auto-disconnect on inactivity

### User Experience
- Slash commands + prefix commands
- Interactive button controls
- Dropdown menus for selections
- Ephemeral responses for privacy
- Real-time progress indicators

---

## 🎨 Interface Highlights

- **Now Playing Embed**: Shows track info, duration, source, requester, and artwork
- **Queue Display**: Paginated list with track details
- **Similar Tracks**: Multi-select dropdown for easy queueing
- **Control Panel**: Comprehensive button-based music controls
- **Filter Selector**: Dropdown menu with all available audio effects

---

## 📊 Statistics

- **Total Commands**: 40+
- **Audio Filters**: 10
- **Supported Platforms**: 4
- **Multi-Server**: Unlimited
- **Queue Capacity**: Unlimited
- **Uptime**: 24/7 with auto-reconnect

---

## 🔒 Privacy & Security

MISAKI Bot respects your privacy:
- No personal data collection
- Server data isolation
- No cross-server data sharing
- Automatic cleanup of invalid entries
- Secure database storage

See [Privacy Policy](PRIVACY_POLICY.md) and [Terms of Service](TERMS_OF_SERVICE.md) for details.

---

## 🛠️ Developer Information

**Bot Name**: MISAKI  
**Version**: 1.0.0  
**Language**: Python  
**Status**: Active Development  
**Multi-Server**: Yes  
**Open Source**: Private

### Features Roadmap
- [ ] Playlist saving system
- [ ] Lyrics display
- [ ] Advanced equalizer controls
- [ ] Web dashboard
- [ ] Music recommendations AI
- [ ] Spotify playlist import
- [ ] YouTube playlist optimization

---

## 📝 Notes

- The bot requires Lavalink servers for music streaming
- Wavelink is used for audio processing
- SQLite databases store server configurations
- All music is streamed in real-time (not downloaded)
- Multi-server support with independent states

---

## 🤝 Support

For questions, issues, or feature requests:
- Contact the developer on Discord
- Check the help menu: `/help`
- Review documentation

---

## ⚠️ Disclaimer

MISAKI Bot is provided "as is" without warranties. The bot does not store or distribute copyrighted content. All music is streamed from third-party sources. Users are responsible for ensuring they have the legal right to play requested content.

---

## 📜 License

This bot is private and proprietary. All rights reserved.

---

**Made with ❤️ for Discord music lovers**

*MISAKI Bot - Explosive Music, Zero Lag* 💥🎵

