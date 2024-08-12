# QMK config for Dactyl Manuform 5x6


## Prerequisites

TODO: migrate to `brew install qmk/qmk/qmk`

```shell
ports install dfu-utils avr-gcc avr-libc
pyenv virtualenv trackpoint
pyenv activate trackpoint
pip install qmk
qmk setup
```

# Keymap
Edit config on https://config.qmk.fm/ and compile json file with `qmk json2c ps34.json > keymap.c` before flashing.

Flashing
```shell
# Right (EliteC / DFU)
make handwired/dactyl_manuform/5x6:pshabunia:dfu
# Left (ATMega / AVR)
make handwired/dactyl_manuform/5x6:pshabunia:avrdude
```

# Handedness
```shell
# Right
make handwired/dactyl_manuform/5x6:pshabunia:dfu-split-right
# Left
make handwired/dactyl_manuform/5x6:pshabunia:avrdude-split-left
```


