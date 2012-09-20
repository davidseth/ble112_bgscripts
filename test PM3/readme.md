From: http://forum.mkroll.mobi/viewtopic.php?f=7&t=495

I want to set the BLE modul into the sleep mode. Thats okay.. i use the gap_set_mode(0,0) function and in the hardware.xml 
i use the sleeposc enable = "true" ppm="30" and finished. But now the main problem. I want to use a command from the 
BLEGUI2.exe as an interrupt to wake up the modul. Not a IO interrupt. is it always possible to send data to the Modul 
even in the sleep mode?