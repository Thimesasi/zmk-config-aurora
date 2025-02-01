# ZMK Config for the Aurora Keyboard

This is the ZMK config for the [Aurora Keyboard](https://github.com/Musab-Hassan/aurora_keyboard). There are three firmware files, one for each peripheral.

I would like to add support for ZMK studio in the future but have not had the chance to come around to it yet.

## Download the Firmware Files

If you would like to use the pre-built firmware, follow these steps to download it:

1. Go to the [Actions tab](https://github.com/Musab-Hassan/zmk-config-aurora/actions/workflows/build.yml).
2. Click on the latest run that has a green checkmark.
3. Scroll down to **Artifacts** and download the firmware zip file.
4. Extract the firmware files and store them somewhere you can easily find them.

## Flash Firmware

When flashing the firmware, keep both sides of the keyboard off (battery switch off). They can still receive power from the USB port even when off, as the switch only disconnects the battery.

To flash the firmware:

1. Connect one of the three devices to your computer using a USB-C cable.
2. Press the reset button twice (located above the power switch).
3. The microcontroller should mount as a flash drive on your computer. Drag the correct firmware file for that device onto the microcontroller.
4. The microcontroller should disconnect and reconnect with the "Aurora" keyboard name.
5. Repeat these steps for the other two devices.

Once all three devices are flashed, disconnect them all and connect the dongle to your computer with a USB-C cable. Once the dongle is connected, turn on both keyboard devices, and you should now have a functional keyboard.

## License

MIT
