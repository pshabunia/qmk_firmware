# QMK config for Dactyl Manuform 5x6

Dactyl Manuform in 5x6 layout with myr4x5 keymap plus trackpoint. Left hand part is powered by ATMega32u4. The right hand is running EliteC.


## Prerequisites
[Install QMK](https://docs.qmk.fm/#/getting_started_build_tools) if you have not.


## Flashing
```shell
# Right (EliteC / DFU)
make handwired/dactyl_manuform/5x6:pshabunia:dfu
# Left (ATMega / AVR)
make handwired/dactyl_manuform/5x6:pshabunia:avrdude
```

## Handedness
```shell
# Right
make handwired/dactyl_manuform/5x6:pshabunia:dfu-split-right
# Left  
make handwired/dactyl_manuform/5x6:pshabunia:avrdude-split-left
```
