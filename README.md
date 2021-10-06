# rpi-eeprom
This repository contains the scripts and pre-compiled binaries used to create the `rpi-eeprom` package which is used to update the Raspberry Pi 4 bootloader and VLI USB controller EEPROMs.

# Support
Please check the Raspberry Pi [general discussion forum](https://www.raspberrypi.org/forums/viewforum.php?f=63) if you have a support question. 

# Reset to factory defaults
To reset the bootloader back to factory defaults use [Raspberry Pi Imager](https://www.raspberrypi.com/software/) to write an EEPROM update image to a spare SD card. Select `Misc utility images` under the `Operating System` tab.

# Bootloader documentation
* [The boot folder](https://www.raspberrypi.com/documentation/computers/configuration.html#the-boot-folder)
* [Config.txt boot options](https://www.raspberrypi.com/documentation/computers/config_txt.html#boot-options)
* [Bootloader EEPROM](https://www.raspberrypi.com/documentation/computers/raspberry-pi.html#raspberry-pi-4-boot-eeprom)
* [Bootloader configuration](https://www.raspberrypi.com/documentation/computers/raspberry-pi.html#raspberry-pi-4-bootloader-configuration)
* [Updating the Compute Module 4 bootloader](https://www.raspberrypi.com/documentation/computers/compute-module.html#cm4bootloader)
* [Release notes](firmware/release-notes.md)
* [Releases](releases.md)
