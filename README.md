# 🚀 Fastfetch Custom Configuration

Welcome to a stunning configuration for [Fastfetch](https://github.com/fastfetch-cli/fastfetch), the ultimate system information tool that turns your terminal into a work of art! 🎨✨

## 📋 Table of Contents

1. [✨ Features](#-features)
2. [🛠️ Installation](#️-installation)
3. [🚀 Usage](#-usage)
4. [🎨 Customization](#-customization)
5. [📥 Quick Download](#-quick-download)
6. [✏️ Notes](#%EF%B8%8F-notes)

## ✨ Features

- 🖥️ **Comprehensive System Information**
  - OS, Kernel, Uptime, Packages, Local IP, Public IP,...
- 🎨 **Detailed Desktop Environment Showcase**
  - DE, WM, Theme, Resolution, Shell, Font,...
- 💻 **In-depth Hardware Specifications**
  - CPU, GPU, Memory, Disk usage,...
- 🌈 **Vibrant Color Palette Display**

## 🛠️ Installation

### 1. Install Fastfetch:

| System | Command |
|:------:|:-------:|
| Arch Linux | `sudo pacman -S fastfetch` |
| Ubuntu/Debian | `sudo add-apt-repository ppa:fastfetch-devs/fastfetch && sudo apt update && sudo apt install fastfetch` |
| macOS (Homebrew) | `brew install fastfetch` |
| Windows (Scoop) | `scoop install fastfetch` |
| Windows (Winget) | `winget install fastfetch` |

For other systems, refer to the [official installation guide](https://github.com/fastfetch-cli/fastfetch#installation).

### 2. Set up the configuration:

| System | Command |
|:------:|:-------:|
| Linux/macOS | `mkdir -p ~/.config/fastfetch && wget -O ~/.config/fastfetch/config.jsonc https://raw.githubusercontent.com/sorcereric/fastfetch-config/main/config-linux.jsonc` |
| Windows | ```New-Item -ItemType Directory -Force -Path "$env:APPDATA\fastfetch" ; Invoke-WebRequest -Uri "https://raw.githubusercontent.com/sorcereric/fastfetch-config/main/config-windows.jsonc" -OutFile "$env:APPDATA\fastfetch\config.jsonc"``` |

### 3. Add ASCII art
| System | Command |
|:------:|:-------:|
| Linux/macOS | `wget https://raw.githubusercontent.com/sorcereric/fastfetch-config/main/ascii-art.txt -O ~/.config/fastfetch/logo.txt` |
| Windows | ```Invoke-WebRequest -Uri "https://raw.githubusercontent.com/sorcereric/fastfetch-config/main/ascii-art.txt" -OutFile "C:\ProgramData\fastfetch\logo.txt```|

You can also use your personal ascii art , this just has mine :) 
## 🚀 Usage

Simply type `fastfetch` in your terminal to display your system information in a beautifully formatted layout.

## 🎨 Customization

To tailor the display to your preferences:

1. Open the `config-linux.jsonc/config-windows.jsonc` file in your preferred text editor.
2. Modify the settings according to your needs.
3. Save the file and run `fastfetch` to see your changes.

For detailed customization options and syntax, refer to the [Fastfetch documentation](https://github.com/fastfetch-cli/fastfetch/wiki/Configuration).

## 📥 Quick Download

For quick access to the configuration file:
<p align="center">
  <a href="https://raw.githubusercontent.com/sorcereric/fastfetch-config/main/config-linux.jsonc">
    <img src="https://img.shields.io/badge/⬇️" alt="Download config-linux.jsonc">
  </a>
</p>

<p align="center">
  <a href="https://raw.githubusercontent.com/sorcereric/fastfetch-config/main/config-windows.jsonc">
    <img src="https://img.shields.io/badge/⬇️" alt="Download config-windows.jsonc">
  </a>
</p>

Enjoy your beautifully displayed system information! 🎉
## ✏️ Notes

I also provided Two images (one has background other doesnt)
They are original images for ascii art
