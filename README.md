# OPL3 MegaMod
This add-on board lets you play OPL, OPL2, and OPL3 VGM files using your MegaGRRL Desktop.

**This board is provided as an experimental add-on. Software support is working, but incomplete. Software support may improve in the future.**

**MegaGRRL Desktop Firmware v0.97dev or newer is required!** See [Firmware Releases](https://git.agiri.ninja/natalie/megagrrl/-/releases)

# Usage
1. Power off the MegaGRRL Desktop.
2. Remove the YM2612 and SN76489, and seat the addon board into their sockets.
3. Set all 4 DIP switches on the desktop board to OFF.
4. Power on. The presence of the OPL3 board will be detected upon boot. Play an OPL/OPL2/OPL3 VGM file.

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
| IC1 | YMF262 aka YMF262-M (SMD) |
| IC2 | YAC512 (SMD) |
| IC3 | SA5532 (THT) |
| D1 | 1N5819 |
| Misc | 0.1" machine pin male-to-male headers, 40 pins total required. Must be machine pin type!!! |

All capacitors, resistors, diode are THT

# Assembly
1. Solder on the SMD components (YMF262, YAC512)
2. Solder on the THT components (SA5532, capacitors, resistors, diode)
3. Solder on the pin headers (use MegaGRRL Desktop IC sockets for alignment)

# Gerber files
Gerbers for JLCPCB are in the `gerbers/` directory.