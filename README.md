# Firmware_dump-Fichero-Labelprinter

This repository contains the 2 firmware binaries i dumped from the Fichero Labelprinter in this Article i posted on the blog: [Link](https://blog.309electronics.net/articles/dumping-the-firmware-off-a-labelprinter-i-bought-at-action/). They are clean off any sensitive information and have been verified against the storage of the device. There is no guarantee these dumps are 1 to 1 replacements to repair a bricked model or are compatible with all models/devices. This repo contains the ROM dump of the YC3121-D on the printer PCB and also a Flash dump which holds the main Application. 

From a short reverse engineering session, i can conclude that it seems to be making use of (or some components off) [RT-Thread Real TIme Operating System.](https://www.rt-thread.io/) which is Opensource and free to use/download. It does use some components of the SDK of YiChip which is proprietary/not available to the public.

# DISCLAIMER.
Because I could not really find a single manufacturer of this printer, i am taking the risk by sharing these firmware dumps in this repository. The printer is branded **Fichero** but seems like a gneric white label brand (probably from China). These dumps, as said in the beginning, dont really contain any sensitive data. The firmware is made with the YiChip SDK which probably runs ontop of a platform like FreeRTOS or RT_Thread RTOS. **IF you are the manufacturer or software vendor of this device and wish to have this repository removed, i am happy to cooperate immideatly and will take action. So please also be so nice to give me the chance to do so before suing or adding any legal troubles. Many thanks!**

