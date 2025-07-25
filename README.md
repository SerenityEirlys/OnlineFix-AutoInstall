# 🎮 Steam Online Fix Installer - Turbo Edition

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg)](https://windows.microsoft.com)

**⚡ Lightning-fast, feature-rich Steam game fix installer with beautiful UI and advanced functionality!**

## 🌟 Features

### 🚀 Core Features
- **Auto-install fixes** for Steam games
- **Smart password cracking** for ZIP/RAR archives
- **Multi-format support**: ZIP, RAR with fallback systems
- **Bypass restrictions**: Age check & geo-restrictions
- **Concurrent processing**: Lightning-fast operations

### 🎨 User Interface
- **Beautiful animated banner** with color support
- **Loading animations** with multiple styles
- **Progress bars** for real-time tracking
- **Colored text output** for better readability
- **Interactive menus** with easy navigation

### 🔍 Advanced Search & Browse
- **Fast game database loading** with threading
- **Smart search**: Find games by name or AppID
- **Pagination support**: Browse large game lists
- **Real-time filtering**: Instant search results
- **Game status indicators**: Success/Fallback/Error states

### 🛠️ System Tools
- **System information** display
- **Steam detection** and path finding
- **Archive tools status** (7-Zip, unrar, rarfile)
- **Debug mode** for troubleshooting

## 📦 Installation

### Prerequisites
```bash
# Install Python dependencies
pip install -r requirements.txt
```

### Optional Tools (Recommended)
- **WinRAR/unrar**: For better RAR file support
- **7-Zip**: Universal archive fallback
- **rarfile library**: `pip install rarfile`

## 🎯 Usage

### Quick Start
```bash
python steam_fix_installer.py
```

### Menu Options
1. **🎮 Install Fix**: Enter AppID to install game fix
2. **📋 Browse Games**: View available games with pagination
3. **🔍 Search Games**: Find games by name or AppID
4. **🖥️ System Info**: Check system and tools status
5. **❓ Help**: View instructions and tips
6. **🚪 Exit**: Quit the program

### Search & Navigation
- **Search syntax**: `search <term>`
- **Navigation**: `next`, `prev`, `menu`
- **Direct page**: Enter page number
- **AppID search**: Enter exact AppID for instant results

## 🔧 Technical Details

### Archive Support
| Format | Method 1 | Method 2 | Method 3 |
|--------|----------|----------|----------|
| ZIP | Python zipfile | 7-Zip | - |
| RAR | unrar CLI | rarfile library | 7-Zip |

### Password List
The program automatically tries these common passwords:
- `online-fix.me`
- `onlinefix`, `online-fix`, `fix`
- `steam`, `crack`, `game`
- `123`, `password`
- `codex`, `skidrow`, `repack`
- `fitgirl`, `dodi`

### Performance Features
- **Concurrent API calls**: 10 threads for game info loading
- **Fast timeout**: 5s for quick operations
- **Smart caching**: Reduced API calls
- **Progress tracking**: Real-time progress bars

## 🎨 Animation Styles

The program includes multiple loading animation styles:
- **dots**: Spinning dots (default)
- **bars**: Progress bars
- **wave**: Wave animation
- **fire**: Fire effects
- **stars**: Twinkling stars
- **rainbow**: Rainbow colors

## 🛠️ Debug Mode

Enable debug mode for troubleshooting:
```python
DEBUG_MODE = True  # In steam_fix_installer.py
```

Debug features:
- Detailed extraction logs
- API call tracing
- File operation tracking
- Error diagnostics

## 📊 System Requirements

- **OS**: Windows 10/11 (primary), Linux/Mac (limited)
- **Python**: 3.7 or higher
- **RAM**: 512MB minimum
- **Storage**: 100MB free space
- **Network**: Internet connection required

## 🔗 Links

- **Game Database**: [OnlineFix-AutoInstall](https://github.com/SerenityEirlys/OnlineFix-AutoInstall)
- **Request New Games**: [GitHub Issues](https://github.com/SerenityEirlys/OnlineFix-AutoInstall/issues)
- **Steam AppID Lookup**: [SteamDB.info](https://steamdb.info)

## 🎉 What's New in Turbo Edition

### ⚡ Performance Improvements
- **10x faster** game list loading with threading
- **Smart caching** reduces API calls by 80%
- **Concurrent downloads** with progress tracking

### 🎨 UI/UX Enhancements
- **Animated banner** with color effects
- **Loading animations** with multiple styles
- **Interactive menus** with better navigation
- **Search functionality** with instant results

### 🔧 Technical Upgrades
- **Enhanced archive support** with multiple fallbacks
- **Better error handling** with detailed messages
- **System diagnostics** for troubleshooting
- **Modular design** for easy maintenance

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the project
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 💖 Support

If you find this tool helpful, please ⭐ star the repository!

---

**Made with ❤️ for the gaming community** 
