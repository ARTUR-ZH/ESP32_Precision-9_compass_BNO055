# ESP32_Precision-9_compass_BNO055
Digital compass acting as B&G Precision 9 based on ESP32 and BNO055 (tilt compensated)
copy a lot of Code an Idea from https://github.com/htool/ESP32_Precision-9_compass_CMPS14 thanks for that.

## used Librarys 
- Adafruit_BNO055 copy the included modifyed directory to Librarys don't use the original.
  or add  "bool getSensorMagneticOffsets(adafruit_bno055_offsets_t &offsets_type);"  to
  the File "Adafruit_BNO055.h" in the public area.

- Timo's NMEA2000 Library https://github.com/ttlappalainen/NMEA2000
- NMEA2000_esp32  https://github.com/ttlappalainen/NMEA2000_esp32
- Adafruit_BusIO
- Adafruit_Unified_Sensor
- BluetoothSerial

## BNO055
- After trying the MPU9250 first, Iwasn't happy with the noise level. ( as https://github.com/htool ... I am with him!)

## Bluetooth
- Configuration can be done via Bluetooth using free App SerialBluetooth

### What's not working
  - Heave ... I was trying to do this. But I did not get it. The Value was floating away :-(   . Has anyone an Idea ?!
    I did not find a good description for PNG 127252. Is the Value positiv and negativ ? ... Where is Zero Level ? ... 
    Does the Value come up to Zero in time? ... and so on.
    Has anyone a real B&G Precision-9 and can describe what it does?
    
