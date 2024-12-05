# Installation Guide

This guide will help you install WinLat3 and set up all necessary dependencies.

## System Requirements

- Windows 10 (version 1809 or later) or Windows 11
- 4GB RAM (8GB recommended)
- 2GB free disk space
- DirectX 12 compatible graphics card

## Prerequisites

1. **MiKTeX**
   - Download from [MiKTeX website](https://miktex.org/download)
   - Run the installer and follow the setup wizard
   - Choose "Install missing packages on-the-fly = Yes"

2. **Pandoc**
   - Download from [Pandoc website](https://pandoc.org/installing.html)
   - Run the installer
   - Verify installation by running `pandoc --version` in terminal

3. **Visual C++ Redistributable**
   - Download the latest version from Microsoft
   - Required for WinUI 3 applications

## Installing WinLat3

### Method 1: Microsoft Store (Recommended)
1. Open Microsoft Store
2. Search for "WinLat3"
3. Click "Install"
4. Launch from Start menu

### Method 2: Manual Installation
1. Download the latest release from [GitHub Releases](https://github.com/shibinkuriakose/WinLat3/releases)
2. Extract the ZIP file
3. Run `WinLat3Setup.exe`
4. Follow the installation wizard

## Post-Installation Setup

1. **First Launch**
   - Launch WinLat3
   - Complete the initial setup wizard
   - Configure default compiler settings

2. **Package Management**
   - Open Package Manager
   - Install commonly used packages
   - Configure custom package repositories (if needed)

3. **Editor Configuration**
   - Set your preferred theme
   - Configure auto-save settings
   - Set up keyboard shortcuts

## Troubleshooting

### Common Issues

1. **Installation Fails**
   - Verify system requirements
   - Run as administrator
   - Check Windows Update

2. **Compiler Not Found**
   - Verify MiKTeX installation
   - Check PATH environment variables
   - Reinstall MiKTeX if necessary

3. **UI Issues**
   - Update graphics drivers
   - Install latest Windows updates
   - Verify DirectX compatibility

## Getting Help

- Visit our [GitHub Issues](https://github.com/shibinkuriakose/WinLat3/issues)
- Check the [FAQ](../about/faq.md)
- Join our [Discord community](https://discord.gg/winlat3)

## Next Steps

- Read the [Basic Usage Guide](basic-usage.md)
- Explore [Advanced Features](advanced-features.md)
- Learn about [Custom Packages](../dev-guide/custom-packages.md) 