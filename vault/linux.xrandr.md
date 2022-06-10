---
id: linux.xrandr
title: Xrandr
desc: ''
updated: 1642441815118
created: 1642441815118
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xrandr

> Set the size, orientation and/or reflection of the outputs for a screen.
> More information: <https://www.x.org/releases/current/doc/man/man1/xrandr.1.xhtml>.

- Display the current state of the system (known screens, resolutions, ...):

`xrandr --query`

- Disable disconnected outputs and enable connected ones with default settings:

`xrandr --auto`

- Change the resolution and update frequency of DisplayPort 1 to 1920x1080, 60Hz:

`xrandr --output {{DP1}} --mode {{1920x1080}} --rate {{60}}`

- Set the resolution of HDMI2 to 1280x1024 and put it on the right of DP1:

`xrandr --output {{HDMI2}} --mode {{1280x1024}} --right-of {{DP1}}`

- Disable the VGA1 output:

`xrandr --output {{VGA1}} --off`

- Set the brightness for LVDS1 to 50%:

`xrandr --output {{LVDS1}} --brightness {{0.5}}`
