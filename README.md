# KerbIDE

A new code editor specifically for KSP Modders!

## What is this?

KerbIDE is a code editor like VSCode but specifically made for Kerbal Space Program modding, it is meant to be somewhat lightweight but still feature-ful.

## Features:

### Languages it supports
- **C#** - For making actual KSP mods
- **C++** - For other stuff
- **Python** - For scripting stuff
- **.cfg files** - Part configs with useful highlighting
- **KerboScript** - If you use kOS

We will have more later on these are just the first ones we'll be adding in.

### KSP Stuff
- **ModuleManager Debugger** - Test your MM patches without launching the game!
- **Game Launcher** - Launch KSP right from the editor
- **Log Monitor** - Watch game logs in real-time
- **Part Config Checker** - Makes sure your configs don't have errors
- **KSP API Help** - Shows you what KSP functions do

### Other Cool Tools
- **Asset Browser** - Look at all your GameData textures and models
- **Auto Build** - Compiles your C# mods automatically
- **Git Stuff** - Version control built right in
- **Templates** - Quick starts for common mod types

### Editor Features
- Syntax highlighting (makes code colorful and easier to read)
- Autocomplete (suggests code as you type)
- Multiple tabs
- Find and replace
- Themes!
- Customizable shortcuts

## How to Install

### What You Need
- Python 3.8 or newer
- .NET SDK (for C# mods)
- Git (optional, but useful)

### Installing

```bash
# Download the code
git clone https://github.com/KerbalMissile/KerbIDE.git
cd KerbIDE

# Install the stuff it needs
pip install -r requirements.txt

# Run it!
python src/main.py
```

## Getting Started

1. **First Time Setup**: When you open KerbIDE, tell it where KSP is installed
2. **Open Your Mod**: Open the folder with your mod files
3. **Start Coding**: Edit files using the file browser on the left
4. **Test It**: Press F5 to launch KSP and test your mod
5. **Build C# Mods**: Press F6 to compile if you're making a C# mod

## Basic Usage

### Opening Files
- `Ctrl+O` - Open a file
- `Ctrl+Shift+O` - Open a whole project folder
- Just click files in the file browser

### Saving
- `Ctrl+S` - Save current file
- `Ctrl+Shift+S` - Save as `name_here`
- `Ctrl+Alt+S` - Save everything

### Editing
- `Ctrl+Z` - Undo
- `Ctrl+Y` - Redo
- `Ctrl+F` - Find text
- `Ctrl+H` - Find and replace
- `Ctrl+/` - Comment/uncomment lines

### KSP Stuff
- `F5` - Launch KSP
- `F6` - Build your C# mod
- `F12` - Open log monitor

## Configuration

Settings are in:
- Windows: `%APPDATA%/KerbIDE/`

Other OS settings will be in when compatibility is added for the OS':
- Linux: `~/.config/KerbIDE/`
- macOS: `~/Library/Application Support/KerbIDE/`

Important settings:
- `ksp_path` - Where KSP is installed
- `theme` - Color scheme
- `auto_save` - Auto-save every X seconds

## Help & Documentation

- [User Guide](docs/USER_GUIDE.md) - How to use everything
- [Architecture](docs/ARCHITECTURE.md) - How the code works
- [API Docs](docs/API.md) - For making plugins
- [Contributing](docs/CONTRIBUTING.md) - How to help make KerbIDE better

## Want to Help?

This project is open source! You can:
- Report bugs
- Suggest new features
- Add code
- Fix bugs
- Make the docs better

Check out [CONTRIBUTING.md](docs/CONTRIBUTING.md) for more info!

## Problems?

If something breaks:
1. Check the User Guide
2. Look at GitHub Issues
3. Ask on the KSP modding Discord
4. Make a new GitHub Issue

When reporting bugs, include:
- What KerbIDE version you're using
- What operating system
- What happened
- What you expected to happen
- Screenshots help!

## Links

- **GitHub**: https://github.com/KerbalMissile/KerbIDE

## Thanks

Thanks to the KSP modding community for being awesome and giving feedback!

---


Made with ❤️ for the KSP community



