# GY-801-4-sensors-
just another project with raspberrypi
# GY-801 orientation sensor on Raspberry Pi
There are plenty of guides from people using I2C interface sensors from a Raspberry Pi, so this seemed worth a try. You can buy a GY-80 on ebay for £7.50 shipped from China.
The GY-80 is tiny, only about 27x17mm in size, and has following I2C sensors:
      HMC5883L (3-Axis Digital Compass), I2C Address 0x1E 
      ADXL345 (3-Axis Digital Accelerometer), I2C Address 0x53 
      L3G4200D (3-Axis Angular Rate Sensor / Gyro), I2C Address 0x69 
      BMP085 (Barometric Pressure / Temperature Sensor), I2C Address 0x77.
# Raspberry pi I2C Setup  
The raspberry pi is disable by default so  we have to enable I2C on raspberry pi configuration. 
configuring I2C for raspberry pi looks like
        
