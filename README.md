# DSpi-2.0
The DS-pi 2.0 is the 2nd, and latest generation of the DS-pi project, a project with the goal of creating an open source dual screen gaming handheld, aimed at DS and 3DS emulation. Like the previous version, the DS-pi 2.0 is built off the Raspberry PI CM5, a small ARM based processor compute module, running a port of debian linux. Improvements over the original DSpi include a signifiantly better enclosure (resin printing option), and 720p main screen, allowing for use of steam-link and regular steam (mileage may vary, it's still a raspberry pi underneath). 

## System Specifications

- Uses any Pi CM5 module (however the CM5 lite 8GB wifi is highly recommended) with 4 A76 cores at 2.4GHz.
- 1280x720 main display + 800x480 secondary display, with capacitive touch on both screens.
- Stereo speakers, using PCM5102 DAC + NS1450B amplifier, over the I2S interface.
- Headphone output, sharing the same PCM5102 DAC + PAM8908 Headphone AMP, speaker muting is enabled through the 3.5mm jack.
- 5000 Mah LiPo battery, with USB-PD charging enabled using the BQ24192 1S BMS, and HUSB238 PD controller..
- Full size controller using RP2040, and the GP2040CE firmware, using dual analog 3ds slide pads.
- Full 3d printable chassis, with both FDM and resin options available, using GBA SP hinges.

In addition to the changes in spec, this generation has also undergone a complete redesign of the internal electronics, to make use of the Modu-PI motherboard, more information here: https://github.com/borpendy/Modu-PI. This allows for a degree of seperation between the main motherboard, and controller daughterboard. If anyone wants to have a shot at improving the controller board (IMU, RGB ect), this should make things way easier for you.
