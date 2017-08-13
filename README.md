This is the repository for the LoRaTracker Sensor1 board build and programs. 

The Sensor1 board uses a 28Pin DIP Atmega 328 processor. This needs to be loaded with the 
serial bootloader and can then be programmed with a USB to serial adapter (CH340 etc) connected
to the CONPROG connector. 

There are two Mikrobus sockets which allow a variety of sensors or radio modules to be used. 

The pictures show the sensor board being used with a LoRa module and BME280 sensor. With this 
setup the Sensor1 board has a sleep current of circa 22uA. Used with a 3 x AA Alkaline battery
pack the board could send a sensor reading once a minute for between 5 and 10 years. The LoRa 
module used is capable of extreme long range and can also be used for normal short range use
in a highly power efficient mode. 

One of the other pictures shows the board being used as a long distance GPS tracker. 

There are options on the PCB for an I2C FRAM and independant Watchdog device. 



Stuart Robinson
LoRaTracker
Auguest 2017
