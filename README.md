# DEPRECATION NOTICE.
Usage of this Script is no longer necessary as the xpad driver should have the SHANWAN support built in now. Install the driver from https://github.com/paroj/xpad and use the controller.

# shanwan-controller-fix

A Fix for SHANWAN based Xbox controllers on Linux Machines.

Based on information on https://steamcommunity.com/sharedfiles/filedetails/?id=1595753315

This script requires Python3 and pyusb to be installed.

The Controller presents several interfaces to the system in order to detect the system and expects the system reply with a certain sequence. This script detects the controller and writes the sequence to the controller in order to make the xbox mode to work. This script also enables vibration/rumble on the controllers which support vibration on only xbox mode.

The script has been tested on the following controllers.
| Product Name | Website | Working without script? | Working with script? |
|---|---|---|---|
| ANT Esports GP100 Controller | https://antesports.com/product/gp100/ | Starts in PS3 mode. Vibration does not work. | Works Flawlessly |
|---|---|---|---|
| Fantech Revolver GP12 | https://fantech.ph/product/gp12-revolver-2/ | Starts in Android Mode. Triggers, Vibration does not work, Keymapping mismatched | Everything works fine, except vibration |
