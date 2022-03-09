# Ubuntu setup

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



 ## Visual Studio Code

 ### Change Terminal color settings

Settings -> Terminal -> Integrated -> Automation Profile: Linux

```json
{
    "workbench.colorTheme": "Visual Studio Light - C++",
    "git.confirmSync": false

    "workbench.colorCustomizations": {
        "terminal.background":"#1D1F21",
        "terminal.foreground":"#C5C8C6",
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
    }
}
```

### Add extensions

- Markdown All in One
- Markdown Preview Github Styling
- Markdown Shortcuts
- VS Sequential Number
- C/C++ Snippets

## Tree tool

sudo apt install tree

## Image annotation tool

```
sudo snap install ksnip
```

![ksnip.png](/ksnip.png)

## FFMPEG: video handling tool

```
sudo apt install ffmpeg
```

## Ubuntu shortcuts

Shortcut | Action 
---------|----------
 `Print Screen` | Take a screenshot of the desktop 
 `Alt`+`Print Screen` | Take a screenshot of a window
 `Shift`+`Print Screen` | Take a screenshot of an area you select 

 ![ubuntu-shortcuts.jpg](/ubuntu-shortcuts.jpg)

 ## Vscode shortcuts

![vscode-shortcuts.png](/vscode-shortcuts.png)
