This is a small experiment to test the ZPUflex core on the MiSTer board.

The source is from https://github.com/robinsonb5/CtrlModuleTutorial.

The four raw files need to be on a fat or fat32 sd card that is inserted into the second sd card reader on the IO board.
The card needs to be inserted before stating the core as it checks the sd card first.

The only changes I made was the function key for the OSD was set to f12 which conflicts with the MiSTer osd key.
I changed the key to F11 for this experiment.

The core runs a VGA output (640 x 480) at 25Mhz using the sdram expansion board.

