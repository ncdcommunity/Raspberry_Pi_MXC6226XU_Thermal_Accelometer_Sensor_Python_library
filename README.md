[![ MXC6226XU](MXC6226XU_I2C.png)](https://store.ncd.io/product/mxc6226xu-digital-thermal-orientation-accelerometer/).

#  MXC6226XU

The MEMSIC 6226XU Digital Thermal Orientation Sensor (DTOS) is (was ;)) the world’s first fully-integrated orientation sensor.Its operation is based on a patented MEMS-thermal technology and is built using a standard 0.18um CMOS process.
This Device is available from www.ncd.io 

[SKU: MXC6226XU]

(https://store.ncd.io/product/mxc6226xu-digital-thermal-orientation-accelerometer/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface MXC6226XU thermal accelometer sensor With Raspberry Pi :
1. <a href="https://store.ncd.io/product/mxc6226xu-digital-thermal-orientation-accelerometer/">MXC6226XU thermal accelometer sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python MXC6226XU.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
