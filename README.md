#This is a modified fork of VintageLines v0.5
You may find the original repository at: [https://github.com/tmanderson/VintageLines](https://github.com/tmanderson/VintageLines) .

The tweaks are:

  - show relative line number along the absolute one in normal mode. As showing the absolute line number for line 0 just like in Vim is nearly impossible, so I think this is ok-ish, at least for me.
  - set the color of the relative line number to dark blue.
  - don't show the current line as line 0.

## VintageLines v0.5
### Jankily making relative line numbers in [Vintage mode](http://www.sublimetext.com/docs/2/vintage.html)

VintageLines is available via [Sublime Package Control](https://sublime.wbond.net). **Now compatible with ST3!**


#### Relative lines in command mode
![Relative lines in command mode](https://raw.github.com/tmanderson/VintageLines/master/screenshots/screenshot1.png)

#### Normal lines in insert mode
![Normal line numbers in insert mode](https://raw.github.com/tmanderson/VintageLines/master/screenshots/screenshot2.png)

### Notes

If you prefer to always have relative line numbers on set the setting `"vintage_lines.force_mode": true`.

If you prefer a key binding toggle relative lines on and off you can set one up by using key binding code like the following:

        {"keys": ["ctrl+t"], "command": "toggle_setting", "args": {"setting": "vintage_lines.force_mode"}}

Note that you should also set `vintage_lines.force_mode` in your User Preferences to your preferred default
for the toggle to be effective in both command mode and insert mode.

### CONTRIBUTORS (THANKS A LOT!):
- [@kuroir](https://github.com/kuroir)
- [@quarnster](https://github.com/quarnster)
- [@i-akhmadullin](https://github.com/i-akhmadullin)
- [@dsmatter](https://github.com/dsmatter)
- [@MattDMo](https://github.com/MattDMo)
