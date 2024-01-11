# Hanimex E300 Super 8 Viewer Retrofit

## Project Overview
This project turns a vintage Hanimex E300 Super 8 Viewer into a mini CRT look-alike computer running a Raspberry Pi 4. 

![hanimex8](https://github.com/diamond-one/Hanimex-E300-Retro-Computer-/assets/45215287/9ca298b4-9963-49de-a4db-6a856d70a1ff)

## Features
- **LCD Screen Integration:** Replaces the original optical components with a high-resolution LCD screen.
- **Raspberry Pi 4:** Utilizes the power of Raspberry Pi 4 for OS and connectivity.
- **OS:** Linux OS of choice, since it's Raspberry Pi. This project used Kali Linux.

## Getting Started

### Needed for the build
- Hanimex E300 Super 8 Viewer
- Raspberry Pi 4 or other SBC.
- Raspi Case
- Speaker (optional) - the project uses a Bluetooth speaker; porting out from the Raspberry Pi audio port or the screen's audio board would also work well.
- LCD screen - 7.0 inch CLAA070MA0ACW 800x600
- Basic tools for electronics (soldering iron, screwdrivers, etc.)
- Metal file for interior and creating an exterior hole for IO
- Knowledge of Linux, especially boot/config for screen orientation and alignment
- Keyboard: This project used a custom orthographic 40% keyboard build. However, any Bluetooth or wired keyboard will do.
- Mouse: This project used a Lofree Xiaoqiao Bluetooth mouse, but any wired or Bluetooth mouse will do.

## Steps to recreate
- **Disassemble the Hanimex E300:** Remove the original components to make space for the new electronics. I disposed of the film arms but toyed with the idea of mounting a secondary screen to one of them.
- **Installation of the LCD Screen:** Fit the LCD screen into the viewer. This involves filing some of the interior of the Hanimex chassis away.
- **Set Up Raspberry Pi 4:** Install the desired Linux flavour on your Raspberry Pi and then edit the boot/config screen settings for orientation and alignment.
- **Power and wiring:** Inside this project is a double USB-C charger powering both screen and Raspi, the charger is connected to a single mains power port, cut and wired to the original power switch on the front of the Hanimex.
- **IO:** Since the Raspi 4 has a lot of useful IO, in this project, I cut a hole in the side of the Hanimex to let the user access all of the IO. To make this neat, the Raspi is in an off-the-shelf protective case.

## Acknowledgments
- Inspiration from Boostbox YouTube player [Boostbox GitHub](https://github.com/veebch/boostbox)
