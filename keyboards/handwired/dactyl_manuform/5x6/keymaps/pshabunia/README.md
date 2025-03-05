# QMK config for Dactyl Manuform 5x6

Because of the trackpoint the right hand side needs EliteC (pins D2 and D5). Left hand side is (still) powered by ProMicro.

## EEPROM Handedness
```shell
# Right
make handwired/dactyl_manuform/5x6:pshabunia:dfu-split-right
# Left  
make handwired/dactyl_manuform/5x6:pshabunia:avrdude-split-left
```

## Flashing
```shell
# Right (EliteC / DFU)
make handwired/dactyl_manuform/5x6:pshabunia:dfu
# Left (ProMicro / AVR)
make handwired/dactyl_manuform/5x6:pshabunia:avrdude
```
