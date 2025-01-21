# GRUB Theme Selector Script

This Bash script provides an automated and interactive way to manage GRUB themes. It searches for `theme.txt` files in predefined directories such as `/usr/share/grub/themes` and `/boot/grub/themes`, and uses Whiptail to present a user-friendly interface for selecting themes. The selected theme is then applied safely by updating the `GRUB_THEME` variable in `/etc/default/grub` and regenerating the GRUB configuration file. Robust checks and administrative authentication ensure the integrity of the process.

## Features
- Automatically detects available GRUB themes in common directories.
- Presents an interactive menu using Whiptail.
- Updates the GRUB configuration securely.
- Requires administrative privileges to apply changes.

## Installation
```bash
git clone https://github.com/felipefacundes/grub_theme_selector
cd grub_theme_selector
```

## Usage
```bash
bash ./grub_theme_selector
```

## Framework Integration
This script is part of the [shell_utils](https://github.com/felipefacundes/shell_utils) framework, one of the largest collections of scripts and utilities designed to simplify user tasks.
