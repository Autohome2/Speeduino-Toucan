# Speeduino-Toucan
Speeduino 2Can aka "Toucan" Canbus interface. 

This firmware is based upon my GPIO std and Beetle firmware.

It was designed to be used in conjunction with the PCB from DIY-EFI.co.uk , the 2can aka "Toucan"

This has 2 Canbus interfaces 

   Can0 is used for broadcast and other general used

   Can1 is for OBD2 style interface. This allows the data to be used by any std code reader.

The interface connects to Speeduino via Serial3(on the mega2560 based version)

The PCB also has a micro SD card interface which adds logger support (readable directly into MLV HD( megalog viewer HD)

It is also possible to use this firmware with a adafruit ATsamD21G18A based feather board with two mcp2515 modules
