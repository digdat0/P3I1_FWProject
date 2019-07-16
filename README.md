# P3I1_FWProject

The intention of this repo is to document and share customized firmware files for the DJI Phantom 3 series and the Inspire 1 series aircraft. The customized firmware files will provide modifications to the flight controller module which will enable greater speed, removed height restrictions, removed flight zone restrictions as well as removed battery limits. These firmware files were created by 
mefistotelis and other OG's in the DJI reverse engineering community. Credit and props to those guys for paving the way. Original tools found here: 
https://github.com/o-gs/dji-firmware-tools

More information on Phantom 3 and Inspire 1 modding can be found in our wiki: http://dji.retroroms.info/howto/modp3params

Easy to use tool to execute the firmware tools can be found at 
https://github.com/digdat0/P3_i1_EasyMod
https://github.com/digdat0/P3I1-FW-Toolv2

 ---- Usage of these files ----

After downloading the file, you will need to RENAME it, then copy it to an SD card, put in the aircraft and power on. 

To install the firmware, please follow these detailed steps.

1. Download the correct file to your computer, somewhere you can remember like the desktop
2. Remove the mini-SD card from the aicraft camera, put into the computer using adapter of sort
3. Format the card in computer, chose FAT32 or EXFAT if asked (this step is optional)
4a. Rename the downloaded file to PMCAPPFw3.bin for Phantom; if Inspire INMCAPPFw1.bin
4b. Copy the renamed file to the SD card
5. Eject the SD card from computer, put into the aircraft camera
6. Power on the aircraft, it will take 30 seconds or so for the update to start
7. You will hear a distinct noise during the update process, which will change when done. It should take 3-5 minutes
 - NOTE: If the update does not start, please turn off aircraft. Press and hold the bind button, and turn back on. Hold this button for 20-30 seconds and the update will start, then you can let go.
8. When finished, remove the mini-SD card from the camera and back into the computer
9. Remove/ Delete the "PMCAPPFw3.bin_updated" or "INMCAPPFw1.bin_updated" file from the SD card
10. Put Sd card back in the camera

All done!  On your next startup, the modifications will persist on the aircraft. They will remain until you reflash the stock firmware. 





