These config files are for the CR-10 V2 modified w/ BTT-SKR1.4T using TMC2209 drivers and Marlin 2.0.x

As with all config files, replace the stock Configuration.h and Configuration_adv.h files in directory .../Marlin to build for the CR-10 V2 SKR1.4T Mod w/ BLTouch

Due to a firmware issue with defined location of the EEPROM flash, we are using a workaround of emulated flash on the SD Card. SD card should live w/ the machine and be exclusive to the machine.

WIRING NOTES: (Reference underside of board for pin numbers)
    --D11 plugs into SERVO port, pin 2.0
    --Z-Max plugs into Z-MIN port
    --Z-Min is unused.
    --Cooling fan (K-Fan) plugs into FAN0 port. Do not change extruder fan to E1 MOSFET (Pin 2.4) as this powers both the extruder and cooling fans, it needs to be on constant power.
