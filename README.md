# Ender-2-PRO-Klipper-HC32
Klipper firmware for the Ender 2 pro 3d printer with the HC32F460PETB MCU

To install the firmware on the printer.
Create a folder in your SD card named Factory and place the .bin file in the folder. Turn off your printer and insert the SD card. Turn on the 3D printer and your LCD screen should be blank, that means that the firmware is flashing. After the firmware is flashed the LCD will not show anything, so there is no way to tell that the flashing is done. So you can leave he SD for 30sec - 1 minute and then turn off your printer. To verify that the firmware is flashed, the .bin file in the SD card should be removed from the folder.

After that, you can install Octoprint, install the Klipper addon (there is plenty of tutorials online) and copy and pase everything from the printer.cfg file into the config of the klipper.

Restart the host and firmware and the the LCD should come on. That means that its ready for printing.
