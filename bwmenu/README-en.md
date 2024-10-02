# bwmenu - Bitwarden Integration for Rofi

Welcome to bwmenu, a powerful component of Kinder.Rofi, which is a sub-repository of Kinder.Dots (custom configurations for Arch Linux). This tool enables seamless interaction with Bitwarden through the Rofi interface.

## Overview

bwmenu is a script that integrates Bitwarden password manager with Rofi, providing a convenient and efficient way to access your Bitwarden vault directly from your Rofi menu. This component has been adapted from the original work found in the [mattydebie/bitwarden-rofi](https://github.com/mattydebie/bitwarden-rofi/blob/master/bwmenu) repository.

## Features

- Quick access to Bitwarden vault entries
- Search and filter Bitwarden items
- Copy usernames and passwords to clipboard
- Auto-type functionality for easy form filling
- Secure handling of sensitive information

## Prerequisites

Before using bwmenu, ensure you have the following installed:

- Rofi
- Bitwarden CLI (bw)
- xclip or wl-clipboard (depending on your system)

## Installation

As part of Kinder.Rofi, bwmenu comes pre-configured in the Kinder.Dots repository. To use it:

1. Clone the Kinder.Dots repository
2. Navigate to the Kinder.Rofi directory
3. Ensure bwmenu has execute permissions

## Usage

To use bwmenu, simply run:

```bash
rofi -show bw -modi "bw:./bwmenu"
```

You can also bind this command to a keyboard shortcut for quick access.

## Configuration

bwmenu can be customized to fit your workflow. Check the script for available options and modify as needed.

## Contributing

Contributions to improve bwmenu are welcome. Please submit pull requests or issues to the Kinder.Dots repository.

## License

This adaptation of bwmenu is distributed under the same license as the original project. Please refer to the original repository for license details.

Thank you for using bwmenu! We hope this tool enhances your password management experience within your Arch Linux environment.