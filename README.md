MEEPROMMER
==========

(E)EPROM programmer based on Arduino hardware


The MEEPROMMER is a combination of hardware and software that lets you read and write 
data from (and to) 28Cxxx EEPROMS. Maybe later there will be enhancements to use it
also for 27Cxxx EPROMS. 

At the moment we have an working prototype on a PCB that uses an Arduino Nano and an 
Arduino-shield that can directly plugged to an Arduino Uno. 

The Arduino firmware provides a serial interface with simple commands to transfer data 
between a host computer and an eeprom.

For the host computer a Java based GUI application is available that uses the RXTX 
library to interface the programmer.

Updated HW to allow using CD4015 chips for addressing the eprom memory
Updated serial com library to jSerialComm-2.6.2.jar