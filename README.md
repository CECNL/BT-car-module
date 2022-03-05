# BT-car-module

A tutorial on how to assemble the arduino bluetooth car module

## Steps:
### 1. Assemble the car hardware.

  Chasis / The car assembly instruction come with the package.
  
  There are a lot of tutorial on how to assemble and wire the modules together. Here's one example of the tutorial.
  
  https://create.arduino.cc/projecthub/electronicprojects/bluetooth-control-rc-car-dca116
  
  Be mindful that the code and the wiring is related, so please change the pin output on the program according to your wiring or wire your connections according to the code provided. We allow modification of the code as long as it works. 
  
  Be careful that mistakes in wiring and soldering might cause the modules to break. Please check before turning on or connecting the power.
    
### 2. Upload the arduino program to the arduino uno

![-](https://cdn.sparkfun.com/assets/d/4/e/3/c/51df245ece395f0728000001.png)

### 3. Run the test_car.py

  In the test_car.py you need to put the correct bluetooth port that's connected to the car's bluetooth module (i.e. COM5).
  
```python
ser = serial.Serial("COM5", 9600, timeout = 1)
```
  
  Use the outgoing port.
  
![-](http://blog.bachi.net/wp-content/uploads/2019/06/win10_bluetooth_spp-1.png)
