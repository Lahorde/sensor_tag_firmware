## Description
FW with Gyro not going into sleep mode after a read. Consequently, Gyro capture period no more limited by gyro startup time (60ms).
Min period set to 10ms. Period set by GATT client no more divided by 10 factor.

## Use
To interact with Sensortag either use bluez tools (will be described later)
or nodejs :

``` 
sudo DEBUG=test_gyro node test_gyro.js 
```
