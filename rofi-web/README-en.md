# rofi-web

rofi-web is a custom component for Rofi, designed to enhance web browsing and searching capabilities directly from your Rofi launcher. This component is part of the Kinder.Rofi repository, which is a sub-repository of Kinder.Dots - a comprehensive collection of personalized Arch Linux configurations.

## Features

- Quick access to predefined URLs
- Seamless web searching functionality
- Integration with Firefox browser

## Installation

To install rofi-web, follow these steps:

1. Clone the Kinder.Dots repository:
    
    ```bash
    git clone https://github.com/AndreaKinder/Kinder.Dots.git
    ```
    
2. Navigate to the Kinder.Rofi sub-repository:
    
    ```bash
    cd Kinder.Dots/Kinder.Rofi/rofi-web/
    ```
    
3. Copy the rofi-web script to your preferred location, for example:
    
    ```bash
    sudo cp rofi-web ~/.local/bin/
    ```
    
4. Make the script executable:
    
    ```bash
    chmod +x ~/.local/bin/rofi-web
    ```
    

## Usage

To use rofi-web, you can bind it to a keyboard shortcut or run it from your terminal:

```bash
rofi-web
```

When launched, rofi-web will present you with a menu containing predefined URLs. You can either:

- Select one of the predefined URLs to open it directly in Firefox
- Enter a custom URL to visit that website
- Enter a search term to perform a Google search

## Customization

You can easily customize the predefined URLs by editing the `urls` array in the script. Open the script in your preferred text editor and modify the following line:

```bash
urls=("https://www.google.com" "https://www.github.com" "https://www.stackoverflow.com")
```

Add or remove URLs as needed, keeping the format consistent.

## Dependencies

rofi-web requires the following dependencies:

- Rofi
- Firefox
- Bash

Ensure these are installed on your Arch Linux system before using rofi-web.

## Contributing

Contributions to rofi-web are welcome! If you have suggestions for improvements or bug fixes, please open an issue or submit a pull request to the Kinder.Rofi repository.

## License

This project is part of Kinder.Dots and is subject to its licensing terms. Please refer to the main Kinder.Dots repository for license information.