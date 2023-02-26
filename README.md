# Ender-2-PRO-Klipper-HC32
## For those who want to get more out their Ender 2 pro

**Creality didnt publish the whole Marlin firmware for this printer with this specific board, it doesnt compile so i thought i publish this workaround, using Klipper firmware**

Klipper firmware for the Ender 2 pro 3D Printer with the HC32F460PETB MCU

To install the firmware on the printer.
Create a folder in your SD card named Factory and place the .bin file in the folder. Turn off your printer and insert the SD card. Turn on the 3D printer and your LCD screen should be blank, that means that the firmware is flashing. After the firmware is flashed the LCD will not show anything, so there is no way to tell that the flashing is done. So you can leave he SD for 30sec - 1 minute and then turn off your printer. To verify that the firmware is flashed, the .bin file in the SD card should be removed from the folder.

After that, you can install Octoprint, install the Klipper addon (there is plenty of tutorials online) and copy and pase everything from the printer.cfg file into the config of the klipper.

Restart the host and firmware and the the LCD should come on. That means that its ready for printing.

The config file inlcudes a tuned *presure_advance* setting which increases the print quality by alot. After perfoming the test according to https://www.klipper3d.org/Pressure_Advance.html i have found that the setting should be around 0.6-0.8. It depends on alot of factors such as filament type. Tried with azure film PLA @223C and 60C bed.

I will be adding input shaping soon.
