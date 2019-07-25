# STLink-v3 to Tag connect TC2030-MCP adapter board

Replacement board for the MB1440 to expose the SWIM and SWD/SWO interface to RJ12 for the TAG-connect TC2030-MCP adapter cable.

SWIM level shifter interface is reverse engineered from the MB1440. 

The SWIM/SWD cannot be used simultenaously, but pop option 0 ohms resistors should be populated. (See the board variants.)

![stlinkv3_tagconnect](https://raw.githubusercontent.com/martonmiklos/stlink_v3_tag_connect/master/stlinkv3_tagconnect.png "Layout")
