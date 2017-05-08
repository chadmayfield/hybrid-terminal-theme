# hybrid-terminal-theme

A dark theme based on [w0ng's vim-hybrid theme](https://github.com/w0ng/vim-hybrid) for Apple's default terminal.app.

Terminal settings
* Font: 12 pt SF Mono Regular
* Use of antialiasing text
* Use of bright colors for **bold** text
* Modify terminal size to 84 x 24 (added px for offset to vim line numbers)
* Close if the shell is exited cleanly

## Screenshots

<p align="center">
hybrid.terminal<br />
<img src="http://i.imgur.com/xPBkiUZ.png"><br />
hybrid-reduced-contrast.terminal<br />
<img src="https://i.imgur.com/M9xdTeD.png"><br />
<a href="http://tldp.org/HOWTO/Bash-Prompt-HOWTO/x329.html">Color Mappings</a><br />
<img src="http://i.imgur.com/YtRP0Tp.png"><br />
</p>

## Installation
There a few different ways to install an Apple Terminal profile.  The two easiest are;

1. In Finder, locate the .terminal file and double-click it.  This will automatically import the settings into the Terminal.app.
2. Open Terminal and choose Preferences.  In the Preferences windows, click the down arrow on the gear icon in the lower left corner of the windows and click Import.  Navigate to and select the terminal file, then click import.

## Hex Values
The values for the hybrid.terminal theme are modified from [w0ng's .Xresources-hybrid](https://gist.github.com/w0ng/3278077)

 bg/fg     | black  |  red   |  green  | yellow  |  blue   | magenta |  cyan   | white  
---------- | ------ | ------ | ------- | ------- | ------- | ------- | ------- | ------
background | color0 | color1 | color2  | color3  | color4  | color5  | color6  | color7
1D1F21     | 282A2E | A54242 | 8C9440  | DE935F  | 5F819D  | 85678F  | 5E8D87  | 707880
foreground | color8 | color9 | color10 | color11 | color12 | color13 | color14 | color15
C5C8C6     | 373B41 | CC6666 | B5BD68  | F0C674  | 81A2BE  | B294BB  | 8ABEB7  | C5C8C6

The values for the hybrid-reduced-contrast.terminal are modified from [w0ng's .Xresources-hybrid-reduced-contrast](https://gist.github.com/w0ng/16e33902508b4a0350ae)

 bg/fg     | black  |  red   |  green  | yellow  |  blue   | magenta |  cyan   | white  
---------- | ------ | ------ | ------- | ------- | ------- | ------- | ------- | ------
background | color0 | color1 | color2  | color3  | color4  | color5  | color6  | color7
232C31     | 2D3C46 | A54242 | 8C9440  | DE935F  | 5F819D  | 85678F  | 5E8D87  | 6C7A80
foreground | color8 | color9 | color10 | color11 | color12 | color13 | color14 | color15
C5C8C6     | 425059 | CC6666 | B5BD68  | F0C674  | 81A2BE  | B294BB  | 8ABEB7  | C5C8C6

*NOTE:* Color [differences](https://i.imgur.com/haBkExL.png) for reduced contrast are; background, color0, color7, & color8. 

#### Follow-up
Shortly after I made these themes for my terminal, I found the [mac-os-x-terminal-themes](https://github.com/lysyi3m/osx-terminal-themes) repo with [Hybrid.termial](https://raw.githubusercontent.com/lysyi3m/osx-terminal-themes/master/schemes/Hybrid.terminal) glaring at me. Oh well! I've kept this repo for myself and tweaks I make to the them. 
