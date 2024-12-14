# So Many Robots

1. Download So Many Robots: [Robot Explorer.uf2](https://github.com/somany-io/robot/raw/refs/heads/main/Robot%20Explorer.uf2)
2. Press and hold the BOOTSEL button on the Raspberry Pi Pico W while connecting to a computer via a USB cable.
3. Drag and drop the downloaded So Many Robots: Robot Explorer.uf2 to the RPI-RP2 volume.

See [So Many Robots DIY - Print in Place Robot With Python and Raspberry Pi Pico W](https://www.instructables.com/So-Many-Robots-DIY-Print-in-Place-Robot-for-STEM-L/) for detailed instructions on building the robot.

## Editing code 
Source code can be loaded by editing in Thonny, see https://projects.raspberrypi.org/en/projects/getting-started-with-the-pico/0 for additional info on getting started.

## Taking Snapshots of the Raspberry Pi Pico State  

If you'd like to create a full snapshot of your Raspberry Pi Pico's current state for backup or restoration purposes, you can use `picotool`.  

To use this feature, you’ll need to install `picotool`. Follow the installation instructions in the official Raspberry Pi documentation: [Raspberry Pi Picotool](https://github.com/raspberrypi/picotool)

Run the following command to save a snapshot as a `.uf2` file:  
```
picotool save --all robot-backup.uf2
```
