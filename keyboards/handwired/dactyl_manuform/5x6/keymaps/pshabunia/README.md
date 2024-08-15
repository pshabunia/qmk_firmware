# QMK config for Dactyl Manuform 5x6

## Prerequisites
Read the docs, install QMK

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
