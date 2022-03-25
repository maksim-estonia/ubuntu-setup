# Ubuntu setup

- [Ubuntu setup](#ubuntu-setup)
  - [Tree tool](#tree-tool)
  - [Ksnip: image annotation tool](#ksnip-image-annotation-tool)
  - [UMLet: drawing UML diagrams](#umlet-drawing-uml-diagrams)
  - [FFMPEG: video handling tool](#ffmpeg-video-handling-tool)
  - [Recommended extensions](#recommended-extensions)
  - [Terminal](#terminal)
    - [auto-completion](#auto-completion)
    - [change to homebrew color scheme](#change-to-homebrew-color-scheme)
    - [add open script](#add-open-script)
  - [Visual Studio Code](#visual-studio-code)
    - [Change Terminal color settings](#change-terminal-color-settings)
    - [Keyboard shortcuts](#keyboard-shortcuts)
    - [Add extensions](#add-extensions)
- [Shortcuts](#shortcuts)
  - [Ubuntu](#ubuntu)
  - [VScode](#vscode)
  - [Window manager](#window-manager)
- [Terminal commands](#terminal-commands)
- [Unix filesystem](#unix-filesystem)

## Tree tool

```
sudo apt install tree
```

## Ksnip: image annotation tool

```
sudo snap install ksnip
```

## UMLet: drawing UML diagrams

```
sudo apt-get install -y umlet
```

## FFMPEG: video handling tool

```
sudo apt install ffmpeg
```

## Recommended extensions

[Link](https://itsfoss.com/best-gnome-extensions/)



## Terminal

### auto-completion

[Link](https://unix.stackexchange.com/questions/55203/bash-autocomplete-first-list-files-then-cycle-through-them)

```
bind "TAB:menu-complete"
bind "set show-all-if-ambiguous on"
bind "TAB:complete"; bind "set show-all-if-ambiguous off"
```

### change to homebrew color scheme

[Link color scheme](https://mattgadient.com/how-to-make-the-ubuntu-terminal-more-like-the-mac-os-x-terminal/)

[Link font install](https://linuxconfig.org/how-to-install-fonts-on-ubuntu-20-04-focal-fossa-linux)

![color-scheme.png](/color-scheme.png)

Color codes:

- Default color (Text): #00FF00
- Default color (Background): #000000
- Highlight color (Background): #0900E9

| #000000  | #C33720  | #34BC26 | #AFAD24  | #5350F8 | #D43BD3 | #7458DB | #CCCCCC |
|---|---|---|---|---|---|---|---|

(top and bottom row = same)

### add open script

Open current directory in terminal by typing `open .`


## Visual Studio Code

 ### Change Terminal color settings

Settings -> Terminal -> Integrated -> Automation Profile: Linux

```json
{
    "workbench.colorTheme": "Visual Studio Light - C++",
    "git.confirmSync": false,

    "workbench.colorCustomizations": {
        "terminal.background":"#1D1F21",
        "terminal.foreground":"#00FF00",
        "terminalCursor.background":"#C5C8C6",
        "terminalCursor.foreground":"#C5C8C6",
        "terminal.ansiBlack":"#1D1F21",
        "terminal.ansiBlue":"#3971ED",
        "terminal.ansiBrightBlack":"#969896",
        "terminal.ansiBrightBlue":"#3971ED",
        "terminal.ansiBrightCyan":"#3971ED",
        "terminal.ansiBrightGreen":"#51b837",
        "terminal.ansiBrightMagenta":"#A36AC7",
        "terminal.ansiBrightRed":"#CC342B",
        "terminal.ansiBrightWhite":"#FFFFFF",
        "terminal.ansiBrightYellow":"#FBA922",
        "terminal.ansiCyan":"#3971ED",
        "terminal.ansiGreen":"#198844",
        "terminal.ansiMagenta":"#A36AC7",
        "terminal.ansiRed":"#CC342B",
        "terminal.ansiWhite":"#C5C8C6",
        "terminal.ansiYellow":"#FBA922",
        "terminal.selectionBackground": "#135564"
    },
    "testMate.cpp.log.userId": "2b6ec97f4dff59272c92ff1211b8d2f1b4c10127",
    "testMate.cpp.log.logSentry": "enable",
    "cmake.configureOnOpen": false
}

```

### Keyboard shortcuts

Settings -> Open Keyboard Shortcuts (JSON)

```json
// Place your key bindings in this file to override the defaultsauto[]
[
    {
        "key": "ctrl+meta+right",
        "command": "cursorEndSelect",
        "when": "textInputFocus"
    },
    {
        "key": "end",
        "command": "-cursorEnd",
        "when": "textInputFocus"
    },
    {
        "key": "ctrl+meta+left",
        "command": "cursorLineStartSelect"
    },
    {
        "key": "home",
        "command": "cursorLineStart"
    }
]
```

### Add extensions

- Markdown All in One
- Markdown Preview Github Styling
- Markdown Shortcuts
- VS Sequential Number
- C/C++ Snippets

# Shortcuts

## Ubuntu

Shortcut | Action 
---------|----------
 `Print Screen` | Take a screenshot of the desktop 
 `Alt`+`Print Screen` | Take a screenshot of a window
 `Shift`+`Print Screen` | Take a screenshot of an area you select 

 ![ubuntu-shortcuts.jpg](/ubuntu-shortcuts.jpg)

## VScode

![vscode-shortcuts.png](/vscode-shortcuts.png)

## Window manager

[quicktile](https://github.com/ssokolow/quicktile) ([commands](http://ssokolow.com/quicktile/commands.html))

Setup: go to "Startup Applications", add a startup command `quicktile --daemonize`

Shortcut | Action 
---------|----------
 `Ctrl`+`Alt`+`7` | Top-left
 `Ctrl`+`Alt`+`8` | Top
 `Ctrl`+`Alt`+`9` | Top-right
 `Ctrl`+`Alt`+`4` | Left
 `Ctrl`+`Alt`+`5` | Center
 `Ctrl`+`Alt`+`6` | Right
 `Ctrl`+`Alt`+`1` | Bottom-left
 `Ctrl`+`Alt`+`2` | Bottom
 `Ctrl`+`Alt`+`3` | Bottom-right
 `Ctrl`+`Alt`+`0` | Maximize

# Terminal commands

![linux-cheat-sheet.png](/linux-cheat-sheet.png)

# Unix filesystem

![standard-unix-filesystem-hierarchy.png](/standard-unix-filesystem-hierarchy.png)