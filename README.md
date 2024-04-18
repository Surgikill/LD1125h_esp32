These are changes I have made to the code from patrick3399 for the LD-1125h esp32 presence sensor.

These changes include updating settings to be more human readable, and adding a delay to the uart restore_value to fix settings not being saved between boots.

The individual components each have their own file and are all called in the main presencebox.yaml. This allows changes to be synchronized easily across multiple devices, and allows for a more streamlined updating process when changes are made and the user has many devices. 

There is also a RGB led that has been added and a BH1750 illuminance sensor.
