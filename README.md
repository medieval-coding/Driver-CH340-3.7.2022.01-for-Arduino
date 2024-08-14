# Driver-CH340-3.7.2022.01-for-Arduino
The version 3.7.2022.01 of the driver CH340 for Arduino users. 

Recently i've been having some problems with the Arduino IDE related to the new version of the CH340 driver. After compiling a code, even a test one like the "blink", the IDE couldn't run the code and showed this error message: erro arduino avrdude: ser_open(): can't set com-state for "\\.\COM3".

It happened with all the ports of my computer and with my professor's too. The only way we find out how to solve this problem, that causally happens with the new version of the CH340 driver at Windows 11, was downloading an older version (the 3.7.2022.01 one) and installing it.

Now, you shall watch out the automatic update of the drivers that Windows does. This may update the driver and cause the same problem again. In the devide manager area, select the driver and deactivate the automatic updates by selecting the option saying that the newer version of the driver are not working well for you. This might solve your problems with the Arduino IDE related to this error message.
