---
id: linux.xfce4-screenshooter
title: Xfce4 Screenshooter
desc: ''
updated: 1615655543112
created: 1615655543112
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# xfce4-screenshooter

> The XFCE4 screenshot tool.

- Launch the screenshooter GUI:

`xfce4-screenshooter`

- Take a screenshot of the entire screen and launch the GUI to ask how to proceed:

`xfce4-screenshooter --fullscreen`

- Take a screenshot of the entire screen and save it in the specified directory:

`xfce4-screenshooter --fullscreen --save {{path/to/directory}}`

- Wait some time before taking the screenshot:

`xfce4-screenshooter --delay {{seconds}}`

- Take a screenshot of a region of the screen (select using the mouse):

`xfce4-screenshooter --region`

- Take a screenshot of the active window, and copy it to the clipboard:

`xfce4-screenshooter --window --clipboard`

- Take a screenshot of the active window, and open it with a chosen program:

`xfce4-screenshooter --window --open {{gimp}}`
