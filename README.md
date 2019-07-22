# P3I1_FWProject

The intention of this repo is to document and share customized firmware files for the DJI Phantom 3 series and the Inspire 1 series aircraft. The customized firmware files will provide modifications to the flight controller module which will enable greater speed, removed height restrictions, removed flight zone restrictions as well as removed battery limits. The tools used to open and extract firmware were created by mefistotelis and other OG's in the DJI reverse engineering community. Credit and props to those guys for paving the way. Original tools found here: https://github.com/o-gs/dji-firmware-tools

More information on Phantom 3 and Inspire 1 modding can be found in our wiki: http://dji.retroroms.info/howto/modp3params

Easy to use tool to execute the firmware tools can be found at 
https://github.com/digdat0/P3_i1_EasyMod
https://github.com/digdat0/P3I1-FW-Toolv2

Currently uploaded firmware:

Height + NFZ Removal Available Versions: 
-  P3 Std (p3c): 1.09.0200
-  P3 4k (P3XW): 1.06.0050
-  P3 SE (p3se): 1.05.0040
-  P3 Adv (p3s): 1.10.0090, 1.11.0020
-  P3 Pro (p3x):  1.10.0090, 1.11.0020
-  Inspire 1 (wm610): 1.10.01.40, 1.11.01.50
-  Inspire 1 Pro (WM610_FC550): 1.11.01.50
-  Inspire 1 Pro RAW (WM610_FC550R): 1.11.01.50

Height + NFZ Removal + Faster Speed Available Versions: 
-  P3 Std (p3c): 1.09.0200
-  P3 4k (P3XW): 1.06.0050
-  P3 SE (p3se): 1.05.0040
-  P3 Adv (p3s): 1.10.0090, 1.11.0020
-  P3 Pro (p3x):  1.10.0090, 1.11.0020
-  Inspire 1 (wm610): 1.10.01.40, 1.11.01.50
-  Inspire 1 Pro (WM610_FC550): 1.11.01.50
-  Inspire 1 Pro RAW (WM610_FC550R): 1.11.01.50

Donations are welcomed via paypal to flyflydrones@gmail.com


 ---- Usage of these files ----
 
Its simple, download the firmware file, rename it, copy to sd card, put into aircraft and power it on.

Detailed steps:

1. Download the proper file for your aircraft and firmware version. Choose wisely. 
 - The file you are downloading is the 306.bin file, like P3X_FW_V01.11.0020_m0306.bin_MODDED
2. Rename the downloaded file. p3 = PMCAPPFw3.bin I1 = INMCAPPFw1.bin
3. Copy the file to your SD card. Put SD card into the aircraft. 
4. Power on the aircraft. Update will start in about 30 seconds. You will hear a distinct noise during the update process, which will change when done. It should take 3-5 minutes.

** If the update does not start, please turn off aircraft. Press and hold the bind button, and turn back on. Hold this button for 20-30 seconds and the update will start and will make a beeping noise, then you can let go and let the update finish.

5. When update is done, power off the aicraft. Remove the SD card from the camera and back into the computer
6. Remove/ Delete the "PMCAPPFw3.bin_updated" or "INMCAPPFw1.bin_updated" file from the SD card
  Note: If the file is "PMCAPPFw3.bin_damaged" or "INMCAPPFw1.bin_damaged" the update did not complete, retry it.
7. Put Sd card back in the camera 

All done!  On your next startup, the modifications will persist on the aircraft. They will remain until you reflash the stock firmware. 





