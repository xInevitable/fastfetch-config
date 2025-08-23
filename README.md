# 🚀 Fastfetch Custom Configuration

Welcome to a stunning configuration for [Fastfetch](https://github.com/fastfetch-cli/fastfetch), the ultimate system information tool that turns your terminal into a work of art! 🎨✨

## 📋 Table of Contents

1. [✨ Features](#-features)
2. [👀 Preview](#-preview)
3. [🛠️ Installation](#️-installation)
4. [🚀 Usage](#-usage)
5. [🎨 Customization](#-customization)
6. [🔤 Font Requirement](#-font-requirement)
7. [📥 Quick Download](#-quick-download)

## ✨ Features

- 🖥️ **Comprehensive System Information**
  - OS, Kernel, Uptime, Packages
- 🎨 **Detailed Desktop Environment Showcase**
  - DE, WM, Theme, Resolution, Shell, Font
- 💻 **In-depth Hardware Specifications**
  - CPU, GPU, Memory, Disk usage
- 🌈 **Vibrant Color Palette Display**

## 👀 Preview

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/f249aabf-6850-4c45-938e-2a364c64b5ea" alt="Fastfetch-preview-linux" width="80%">
        <br>
        <em>Linux Preview</em>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/6f4b7f2b-989b-4f90-bd71-183dd00f0d0f" alt="Fastfetch-preview-windows" width="80%">
        <br>
        <em>Windows Preview</em>
      </td>
    </tr>
  </table>
</div>

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

## 🚀 Usage

Simply type `fastfetch` in your terminal to display your system information in a beautifully formatted layout.

## 🎨 Customization

To tailor the display to your preferences:

1. Open the `config.jsonc` file in your preferred text editor.
2. Modify the settings according to your needs.
3. Save the file and run `fastfetch` to see your changes.

For detailed customization options and syntax, refer to the [Fastfetch documentation](https://github.com/fastfetch-cli/fastfetch/wiki/Configuration).

## 📥 Quick Download

For quick access to the configuration file:
<p align="center">
  <a href="https://raw.githubusercontent.com/sorcereric/fastfetch-config/main/config-linux.jsonc">
    <img src="https://img.shields.io/badge/⬇️ Download-config.jsonc-blue?style=for-the-badge&logo=json&logoColor=white" alt="Download config.jsonc">
  </a>
</p>

<p align="center">
  <a href="https://raw.githubusercontent.com/sorcereric/fastfetch-config/main/config-windows.jsonc">
    <img src="https://img.shields.io/badge/⬇️ Download-config.jsonc-blue?style=for-the-badge&logo=json&logoColor=white" alt="Download config.jsonc">
  </a>
</p>

Enjoy your beautifully displayed system information! 🎉
