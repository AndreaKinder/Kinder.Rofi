# Rofi-Notter

Rofi-Notter is a customized component of the Kinder.Rofi repository, which is part of the larger Kinder.Dots macro repository. This tool enhances the functionality of Rofi within the Kinder.Dots ecosystem, providing a seamless interface for managing notes across multiple Obsidian vaults.

## Features

- Access and manage notes within three Obsidian vaults: “learn”, “work”, and “personal”
- Create new notes using predefined templates
- View and edit existing notes
- User-friendly interface powered by Rofi

## Installation

To install Rofi-Notter, clone the Kinder.Rofi repository:

```bash
git clone https://github.com/AndreaKinder/Kinder.Rofi.git
cd Kinder.Rofi/rofi-notter
```

## Usage

Run the script to launch the Rofi-Notter interface:

```bash
./rofi-notter.sh
```

You will be presented with two main options:

- 📑 Create Note: Create a new note in one of the three vaults
- 🔖 View Notes: Browse and edit existing notes

## Configuration

You can customize the following variables in the script:

- TERMINAL: Your preferred terminal emulator
- VIEW: Your preferred document viewer
- EDITOR: Your preferred text editor
- Vault directories: Paths to your Obsidian vaults

## Dependencies

- Rofi
- A terminal emulator (default: Alacritty)
- A text editor (default: Neovim)

## Contributing

Contributions to Rofi-Notter are welcome. Please feel free to submit pull requests or open issues in the Kinder.Rofi repository.

## License

This project is part of Kinder.Dots and is subject to its licensing terms.

For more detailed information about the code and its functionality, please refer to the inline comments in the script.