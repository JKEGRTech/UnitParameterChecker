# UnitParameterChecker - Manufactor Unit Parameter Checker (MUPChecker)

# --Basic Information--
+ Communicate to a device on the network through TCP/IP and TelNet. 

+ Query Unit Parameter for IP Address, MAC Address, serial Number, and part number

+ Check queried parameter and compare to main server to perfomce check sum on the unit

+ Pass and fail you base on provided parameter

+ This is why MUPChecker was created. 

+ The one purpose is to help production speeding up loading parameter verification step.


# -- HOW --
+ MUPChecker sent a command through TCP/IP or telnet to device connected in the local network.

+ Then, query all return information from unit. 

+ After that, it sent request to our MUP Server for unit parameter.

+ Then it compare the two parameter to make sure the parameter got loaded into the unit is corrected and in order

+ In addition, it verifying the process to make sure programming is run smoothly and successed at the end of the process. 

+ Finally, sent in a reset command to restart unit back to the default setting.
