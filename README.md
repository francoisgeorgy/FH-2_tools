# FH-2_tools
Open source tools relating to the FH-2 Eurorack module

View this project as a web page (for ease of downloading scripts): https://expertsleepersltd.github.io/FH-2_tools/

## Some remarks about configurations

The configuration tool only allows to edit and save the *current configuration*. 

If you want to edit one of the configuration slot, you have to load this configuration slot into
the current configuration. After you are done with the editing, you must first save this configuration
in the current slot (with the save button in the tool) and then save this configuration
in the configuration slot with the FH-2.

### Program Change (PC) messages to load a configuration

PC <number> is Configuration Slot <number+1>

To request the Configuration Slot #3 name, send a PC message with value 2.

The current configuration does not have a slot number nor a PC number. 
