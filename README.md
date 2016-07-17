# Ren'Py Event Editor

Ren'Py Event Editor forked from this: [Ren'Py Event Editor 2.1.1 forum post][1]

#Now it:
- Genterate buttons for all spekers added to speakers list:
  ```
  $ speakers.append(mycharacter)
  ```
- Easy add custom images folders:
  ```
  init -30 python:
    addBGs('my_custom_bgs', 'my_bg_prefix') #you don't have to write prefix
    addEVs('my_custom_ev', 'my_ev_prefix')
    addChs('my_custom_ch')
    ```
- Remove old comments
- Comments make in EE are in next line
- Fix indentation or speakers lines
- Added some basic speakers
- Added base bgs with black solid and Tango Palette  
- Automatic generate buttons for all images stored placed in *game/images*:
  - now png and jpg are supported
  - *game/images/characters* for charaters sprites
  - *game/images/bgs* for backgrounds
  - *game/images/events* for events
- Save your events to *game/events*
- All list are scrollable

[1]:[http://lemmasoft.renai.us/forums/viewtopic.php?f=51&t=24108#p374045]
