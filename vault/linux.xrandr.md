---
id: linux.xrandr
title: Xrandr
desc: ''
updated: 1615655543112
created: 1615655543112
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# xrandr

> Set the size, orientation and/or reflection of the outputs for a screen.

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

- Set brightness for LVDS1 to 50%:

`xrandr --output {{LVDS1}} --brightness {{0.5}}`

- See display hardware information:

`xrandr -q`
