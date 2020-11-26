# tecnosoftvid20

Device for automatize the input to SENA Tolima Tecnoacademia instalations. This device can register temp, id, time and date and give antibactery gel for user. This data will be almacenated on blynk server for future consults.

Use a two embebids devices: 1- WEMOS LOLIN 32: This device upload and connect with the blink server, show too the process data in it OLED screen from serial port to Arduino Nano. 2- Arduino Nano: This device manage the data capture from the sensors and modules, the data process is read by the following modules and devices: Temperature (GY809), ID (RFID RF522), Stay (Sharp), Gel dispensador (Servomotor).

In this project the two devices are used like a master-slave system, when WEMOS LOLIN 32 is the slave, and Arduino Nano is the Master. The communication way is only in one way, from master to slave and is codificated for can transmit the data process correctly.

All the mechanism and electronic card for implement all this device was designed and fabricated with industry standards and 4.0 factory elements.
