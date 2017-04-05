This sketch is used for the Ithaca power project and other AC power management applications.

It needs the following repos to build:
*  https://github.com/mcci-catena/Adafruit_FRAM_I2C
*  https://github.com/mcci-catena/Catena4410-Arduino-Library
*  https://github.com/mcci-catena/arduino-lorawan
*  https://github.com/mcci-catena/Catena-mcciadk
*  https://github.com/mcci-catena/arduino-lmic
*  https://github.com/mcci-catena/Adafruit_BME280_Library
*  https://github.com/mcci-catena/Adafruit_Sensor
*  https://github.com/mcci-catena/RTCZero
*  https://github.com/mcci-catena/BH1750

The script 'git-boot.sh' in this directory will get all the things you need.

After you've done that, you may also need to do the following:

```bash
git remote add mcci-catena https://github.com/mcci-catena/ArduinoCore-samd.git
git fetch mcci-catena --all
git merge mcci-catena/TMM-Sleep
```