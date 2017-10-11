
<p align="center"><img width="620px" src="https://i.imgur.com/77xXWrA.jpg"/></p>
<p align="center"><img width="450px" src="https://i.imgur.com/JXb5aRO.jpg"></p>

[![GitHub tag](https://img.shields.io/github/release/faultless/vsc-material-theme.svg?style=flat-square)](https://github.com/faultless/vsc-material-theme/releases)   [![GitHub tag](https://img.shields.io/github/issues/faultless/vsc-material-theme.svg?style=flat-square)](https://github.com/faultless/vsc-material-theme/issues)
<a href="https://code.visualstudio.com/updates/v1_12"><img src="https://img.shields.io/badge/VS_Code-v1.12+-373277.svg?style=flat-square"/></a> <a href="https://marketplace.visualstudio.com/items?itemName=Serge.vsc-material-theme-italicize"><img src="https://vsmarketplacebadge.apphb.com/installs/Serge.vsc-material-theme-italicize.svg?style=flat-square"/></a>

> This fork aims to add some special font transforms (italicizing mainly) to important keywords.

The most epic theme meet Visual Studio Code. Please note that this theme is still in Beta (β) release. You can help by reporting issues [here](https://github.com/faultless/vsc-material-theme/issues)

# Getting started
You can install this awesome theme through the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=Serge.vsc-material-theme-italicize).

## Installation

Launch *Quick Open*
  - <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`
  - <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `⌘P`
  - <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

Paste the following command and press `Enter`:
```shell
ext install vsc-material-theme
```

#### Packaged VSIX Extension

[Download the latest .vsix release](https://github.com/faultless/vsc-material-theme/releases/latest)  file from the GitHub repository and install it from the command line
```shell
code --install-extension vsc-material-theme-*.*.*.vsix
```
or from within VS Code by launching *Quick Open* and running the *Install from VSIX...* command.

##### GitHub Repository Clone

Change to your `.vscode/extensions` [VS Code extensions directory](https://code.visualstudio.com/docs/extensions/install-extension#_side-loading).
Depending on your platform it is located in the following folders:
  - <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> **Linux** `~/.vscode/extensions`
  - <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> **macOs** `~/.vscode/extensions`
  - <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> **Windows** `%USERPROFILE%\.vscode\extensions`

Clone the Material Theme repository as `Serge.vsc-material-theme-italicize`:
```shell
git clone https://github.com/faultless/vsc-material-theme.git Serge.vsc-material-theme-italicize
```


## Activate theme

Launch *Quick Open*,
  - <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`
  - <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `Shift+⌘+P`
  - <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

Type `theme` anc choose `Preferences: Color Theme`, then select Material Theme from the list.

This theme provide differents color variants, to change the active theme variant type `Material Theme` and choose `Material Theme: Settings`, then select `Change color variant` and pick one theme from the list.

## Activate File Icons

Launch *Quick Open*,
  - <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`
  - <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `Shift+⌘+P`
  - <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

type `icon theme` and select `Material Theme Icons` from the drop-down menu.

## Set the accent color
Launch *Quick Open*,
  - <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`
  - <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `Shift+⌘+P`
  - <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

Type `Material Theme` and choose `Material Theme: Settings`, then select `Change accent color` and pick one color from the list.


# Recommended settings for a better experience:

```json
    // Controls the font family.
    "editor.fontFamily": "Operator Mono",
    // Controls the line height. Use 0 to compute the lineHeight from the fontSize.
    "editor.lineHeight": 24,
    // Enables font ligatures
    "editor.fontLigatures": true,
```

# Acknowledgements
- [@OctoD](https://github.com/balanceiskey) for the typescript theme builder.


<p align="center">Copyright &copy; 2017 Mattia Astorino and Paolo Roth</p>

<p align="center"><a href="http://www.apache.org/licenses/LICENSE-2.0"><img src="https://img.shields.io/badge/License-Apache_2.0-5E81AC.png?style=flat-square"/></a> <a href="https://creativecommons.org/licenses/by-sa/4.0"><img src="https://img.shields.io/badge/License-CC_BY--SA_4.0-5E81AC.png?style=flat-square"/></a></p>
