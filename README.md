[commits]: https://github.com/yourusername/roblox-autoupdater/commits
[badges/last-modified]: https://img.shields.io/github/last-commit/yourusername/roblox-autoupdater?label=Last%20Updated

> [!CAUTION]
> This project uses unofficial Roblox APIs and endpoints. The maintainers are not responsible for any potential issues caused by using this auto-updater. Use at your own risk.

# Roblox Auto-Updater

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Last Modified][badges/last-modified]][commits]

Automated version monitoring and updating tool for Roblox clients on Windows.

## What is this?

This Python script provides automatic:
- Version detection through Roblox's API endpoints
- Client download and installation
- Temporary file cleanup

Everything runs locally on your machine without requiring additional server infrastructure.

## Features

- Multi-threaded download and extraction
- Automatic deployment to correct Roblox directories
- Clean removal of previous versions
