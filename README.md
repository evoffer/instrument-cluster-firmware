# Instrument Cluster Firmware

## Update Note for Round Instrument Cluster

### V1.4.25.0812R (20210830)
1. Changed the operation logic to open the Setting Interface to avoid activating the voice command at the same time.
2. Fix: Setting may not be saved when display mode is selected to AUTO. 

### V1.4.25.01007R (20211008)
1. Fix: Screen cannot be shut down after the car is updated to v10.2 (2021.32.21) or above.

### V1.4.25.01030 (20211030)
1. Fix: Screen cannot be shut down.

### V1.4.25.1103Y (20211103)
1. Fix: Screen black out issue.

### V1.4.26.101501R (20221015)
1、Fix: High Beam Display is inaccurate after the car is update to v11.0 (2022.28) or above.

## Software Update

### Step 1 - Prepare USB Flash Drive (Type-C)
Prepare a Type-C or a Type-A USB Flash Drive with a Type-C to Type-A USB Adapter.
Make sure it is in FAT32 format.

### Step 2 - Getting the Update File
Get the update files (`ModeBra01_Left.TLINK` & `ModeBra01_Right.TLINK`) ready.
Place them under the root of the Flash Drive.
Eject it from the computer afterwards.

### Step 3 - Flashing the Update
Insert the USB Flash Drive into the left port behind the display.
Navigate to the setting menu and choose "Upgrade" from the menu.
The left screen will update and reboot.

Now, eject the Flash Drive from the left port and insert it into the right port.
Repeat the above procedure to update the right screen.

### Complete! Test the System
Eject the flash drive and the instrument cluster should be on now. You are all set!

If the system software update failed or didn’t complete in 5 minutes,
please remove the Flash Drive and hold the left and right scroll wheel until the system reboot.
Then, try to upgrade the system again.
