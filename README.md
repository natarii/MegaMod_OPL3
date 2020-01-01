# OPL3 MegaMod
This addon board lets you play OPL, OPL2, and OPL3 VGM files using your MegaGRRL Desktop.

**DO NOT BUILD YET - DESIGN UNTESTED, SOFTWARE SUPPORT INCOMPLETE**

# Usage
Power off the MegaGRRL Desktop. Remove the YM2612 and SN76489 and seat the addon board into their sockets. Move all 4 DIP switches on the desktop board to the OFF position. The presence of the OPL3 board will be detected upon boot.

# Bill of Materials
| Ref.Dsg. | Value | 
| -------- | ----- |
| C1 | 10uF electrolytic |
| C2 | 47pF ceramic |
| C3 | 2.7nF ceramic |
| C4 | 2.7nF ceramic |
| C5 | 0.1uF ceramic |
| C6 | 0.1uF ceramic |
| C7 | 0.1uF ceramic |
| R1 | 33 ohm |
| R2 | 1k ohm |
| IC1 | YMF262 (SMD) |
| IC2 | YAC512 (SMD) |
| IC3 | SA5532 (THT) |
| D1 | 1N5819 |
| Misc | 0.1" machine pin male-to-male headers, 40 pins total required |

# Assembly
The side with the SMD components faces up, and the pin headers poke down towards the desktop board. It's important that the pin headers aren't crooked. I recommend breaking them to the appropriate lengths, pushing them into the main desktop board, and using that as an alignment jig. Otherwise, assembly is pretty easy, just solder everything on.
