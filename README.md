# X-NUCLEO-53L3A2

Arduino library to support the X-NUCLEO-53L3A2 based on VL53L3CX Time-of-Flight and gesture-detection sensor
This sensor uses I2C to communicate. An I2C instance is required to access to the sensor.
The APIs provide simple distance measure in both polling and interrupt mode, single swipe gesture detection,
directional (left/right) swipe gesture detection and single tap gesture detection.

## Examples

There are 5 examples with the  X-NUCLEO-53L3A2 library.

* X_NUCLEO_53L3A2_HelloWorld: This example code is to show how to get multi-object detection and proximity
  values of the onboard VL53L3CX sensor and eventually of the two satellites with polling.

* X_NUCLEO_53L3A2_HelloWorld_Interrupt: This example code is to show how to get multi-object detection and proximity
  values of the onboard VL53L3CX sensor with interrupts.

## Dependencies

This package requires the following Arduino libraries:

* STM32duino VL53L3CX: https://github.com/stm32duino/VL53L3CX
  
## Note

The maximum detection distance is influenced by the color of the target and
the indoor or outdoor situation due to absence or presence of external
infrared. The detection range can be comprise between ~40cm and ~400cm.

## Documentation

You can find the source files at  
https://github.com/stm32duino/X-NUCLEO-53L3A2

The VL53L3CX datasheet is available at  
https://www.st.com/content/st_com/en/products/imaging-and-photonics-solutions/proximity-sensors/vl53l3cx.html
