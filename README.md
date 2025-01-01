![Logo](https://user-images.githubusercontent.com/89016694/207632622-76adb3c7-ea28-4afa-9fd1-b6e613123a01.png)
<p align="center">
<a href="https://github.com/rahriver/rofi-noter/master/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=flat&label=License&message=MIT&logoColor=eceff4&logo=github&colorA=black&colorB=green"/></a>
<img src="https://img.shields.io/github/commit-activity/m/rahriver/rofi-noter">
<a href="https://github.com/rahriver/rofi-noter/graphs/contributors"><img src="https://img.shields.io/github/contributors/rahriver/rofi-noter"></a>
<img src="https://img.shields.io/github/v/release/rahriver/rofi-noter">
</p>

> Welcome to Rofi Noter, a bash script that runs Rofi with different functionalities to create and view your notes and library. With Rofi Noter, you can easily organize your notes and access them directly from the Rofi application launcher.

# 📹 Preview
https://user-images.githubusercontent.com/89016694/222392394-cfbfca20-c122-4362-98bc-75e5214bb755.mp4

## ⚙️  Usage
To use Rofi Noter, simply run the command rofi-noter in your terminal. This will open Rofi with the available functionalities:

- 📑 Create Note
  - Basic (Markdown)
  - LaTeX
  - Beamer (Presentation)
  - R Markdown
- 🔖 View Notes
- 📚 View Library
- 📜 View Articles
- ⏬ Download Books

You can put your note templates inside the templates directory.

## Configuration
Rofi Noter is customizable to suit your needs. You can change the following parameters in the script:

- **directory**: For each Functionality
- **EDITOR**: The file editor you want to open your files in
- **TERMINAL**: The terminal you want to open your notes in

## Dependencies
Before using Rofi Noter, make sure the following dependencies are installed on your system:
- [ripgrep](https://github.com/BurntSushi/ripgrep)
- [rofi](https://github.com/davatorium/rofi)
- [libby](https://github.com/carterprince/libby)

## Installation
To install Rofi Noter, clone the repository and run the installation script:
```bash
git clone https://github.com/rahriver/rofi-noter.git
cd rofi-noter
cp ./rofi-noter /usr/bin
```

### ☕ Support
If you find Rofi Noter useful, please consider giving this repository a star on GitHub, or buying me a cup of coffee :) If you have any issues or suggestions, feel free to open an issue or pull request. Thanks for using Rofi Noter!

<a href="https://www.buymeacoffee.com/rahriver" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
