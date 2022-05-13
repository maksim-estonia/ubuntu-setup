# Ubuntu setup

- [Ubuntu setup](#ubuntu-setup)
  - [Tree tool](#tree-tool)
  - [Gitk](#gitk)
  - [Ksnip: image annotation tool](#ksnip-image-annotation-tool)
  - [Redshift: color temperature tool](#redshift-color-temperature-tool)
  - [UMLet: drawing UML diagrams](#umlet-drawing-uml-diagrams)
  - [FFMPEG: video handling tool](#ffmpeg-video-handling-tool)
  - [Crackling sound fix](#crackling-sound-fix)
  - [Recommended extensions](#recommended-extensions)
  - [Extending disk space](#extending-disk-space)
  - [Click to minimize](#click-to-minimize)
  - [Terminal](#terminal)
    - [auto-completion](#auto-completion)
    - [command history](#command-history)
    - [change to homebrew color scheme](#change-to-homebrew-color-scheme)
    - [add open script](#add-open-script)
    - [add starship](#add-starship)
    - [add wintile](#add-wintile)
  - [Visual Studio Code](#visual-studio-code)
    - [Change Terminal color settings](#change-terminal-color-settings)
    - [Keyboard shortcuts](#keyboard-shortcuts)
    - [Add extensions](#add-extensions)
- [Shortcuts](#shortcuts)
  - [Ubuntu](#ubuntu)
  - [VScode](#vscode)
- [Terminal commands](#terminal-commands)
- [Linux Keyboard Shortcuts](#linux-keyboard-shortcuts)
- [Unix filesystem](#unix-filesystem)
- [Git cheat sheet](#git-cheat-sheet)

## Tree tool

```
sudo apt install tree
```

## Gitk

[Tutorial](https://www.atlassian.com/git/tutorials/gitk)

```
sudo apt install gitk
```

## Ksnip: image annotation tool

```
sudo snap install ksnip
```

## Redshift: color temperature tool

[Link](https://linoxide.com/install-and-use-redshift-on-ubuntu-20-04/)

## UMLet: drawing UML diagrams

```
sudo apt-get install -y umlet
```

## FFMPEG: video handling tool

```
sudo apt install ffmpeg
```

## Crackling sound fix

[Link](https://askubuntu.com/questions/1110422/crackling-sound-when-playing-youtube-ubuntu-18-04-1-running-on-virtualbox-6-0)

## Recommended extensions

[Setup & Install](https://linuxconfig.org/how-to-install-gnome-shell-extensions-on-ubuntu-20-04-focal-fossa-linux-desktop)

[Link](https://itsfoss.com/best-gnome-extensions/)

Installed:

- [Hide Activities Button](https://extensions.gnome.org/extension/744/hide-activities-button/)

## Extending disk space

[Link 1](https://linuxhint.com/increase-virtualbox-disk-size/)

[Link 2](https://gparted.org/display-doc.php%3Fname%3Dmoving-space-between-partitions)

## Click to minimize

[Link](https://itsfoss.com/click-to-minimize-ubuntu/)

## Terminal

### auto-completion

[Link](https://unix.stackexchange.com/questions/55203/bash-autocomplete-first-list-files-then-cycle-through-them)

```
bind "TAB:menu-complete"
bind "set show-all-if-ambiguous on"
bind "TAB:complete"; bind "set show-all-if-ambiguous off"
```

### command history

[Link](https://gist.github.com/petewarden/0c653bd41cb225ded69ed9af3a0c8c34)

### change to homebrew color scheme

[Link color scheme](https://mattgadient.com/how-to-make-the-ubuntu-terminal-more-like-the-mac-os-x-terminal/)

[Link font install](https://linuxconfig.org/how-to-install-fonts-on-ubuntu-20-04-focal-fossa-linux)

![color-scheme.png](/color-scheme.png)

Color codes:

- Default color (Text): #00FF00
- Default color (Background): #000000
- Highlight color (Background): #0900E9

| #000000  | #C33720  | #FD5D5D | #AFAD24  | #8B96FF | #D43BD3 | #5061F8 | #CCCCCC |
|---|---|---|---|---|---|---|---|
| #000000  | #C33720  | #34BC26 | #AFAD24  | #5061F8 | #D43BD3 | #5061F8 | #CCCCCC |

(top and bottom row = same)

### add open script

Open current directory in terminal by typing `open .`

`gedit ~/.bashrc`

Add the following line:

`alias open='xdg-open'`

### add starship

[Link](https://opensource.com/article/22/2/customize-prompt-starship)

### add wintile

[Link](https://github.com/fmstrat/wintile)


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
        "terminal.ansiGreen":"#1D1F21",
        "terminal.ansiMagenta":"#A36AC7",
        "terminal.ansiRed":"#CC342B",
        "terminal.ansiWhite":"#C5C8C6",
        "terminal.ansiYellow":"#FBA922",
        "terminal.selectionBackground": "#135564"
    },
    "testMate.cpp.log.userId": "2b6ec97f4dff59272c92ff1211b8d2f1b4c10127",
    "testMate.cpp.log.logSentry": "enable",
    "cmake.configureOnOpen": false,
    "terminal.integrated.cursorStyle": "line",
    "terminal.integrated.cursorBlinking": true
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
        "command": "cursorEnd",
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
- Bazel

# Shortcuts

## Ubuntu

Shortcut | Action 
---------|----------
 `Print Screen` | Take a screenshot of the desktop 
 `Alt`+`Print Screen` | Take a screenshot of a window
 `Shift`+`Print Screen` | Take a screenshot of an area you select 
 `Super`+`Page Up` | Switch to workspace 1
 `Super`+`Page Down` | Switch to workspace 2
 `Super`+`0` | Hide window
 `F2` | Rename file/folder
 `Alt`+`F4` | Close window

 ![ubuntu-shortcuts.jpg](/ubuntu-shortcuts.jpg)

## VScode

![vscode-shortcuts.png](/vscode-shortcuts.png)


- 
Basic editing | -
---------|----------
 `Alt`+`ArrUp`/`ArrDown` | Move line up/down 
 `Ctrl`+`Enter` | Insert line below
 `Ctrl`+`]`/`[` | **Indent/Outdent line**
 `Ctrl`+`/` | Toggle line comment
 `Ctrl`+`Shift`+`A` | **Toggle block comment**

 Basic editing | -
---------|----------
 `Ctrl`+`Space` | Trigger suggestion

  Basic editing | -
---------|----------
 `Ctrl`+`B` | **Toggle Sidebar visibility**



# Terminal commands

![linux-cheat-sheet.png](/linux-cheat-sheet.png)

# Linux Keyboard Shortcuts

[100 Keyboard Shortcuts](https://linuxhint.com/100_keyboard_shortcuts_linux/)

```
sudo apt-get install -y dconf-editor
```

[dconf](https://wiki.ubuntu.com/Keybindings)

# Unix filesystem

![standard-unix-filesystem-hierarchy.png](/standard-unix-filesystem-hierarchy.png)

# Git cheat sheet

[Pdf](/git-cheat-sheet.pdf)