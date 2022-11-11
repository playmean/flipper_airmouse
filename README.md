# Flipper Air Mouse

## Brief

> "You can turn anything into an air mouse if you're brave enough"
--- Piper, a.k.a. Pez

Naturally, the quote above applies to [Flipper](https://flipperzero.one/) as well.

## What?

The app allows you to turn your Flipper into a USB or Bluetooth air mouse...

Using it is really simple:
 * Connect the Flipper via a USB cable and pick `USB`, or pick `Bluetooth` and pair it with your PC;
 * Hold the Flipper in your hand with the buttons pointing towards the screen;
 * Wave your Flipper like you don't care to move the cursor;
 * Up button for Left mouse click;
 * Down button for Right mouse click;
 * Center button for Middle mouse click;
 * Use calibration menu option if you notice significant drift (place your Flipper onto a level surface, make sure it doesn't move, run this option, wait 2 seconds, done).

See early prototype [in action](https://www.youtube.com/watch?v=DdxAmmsYfMA).

## Hardware

Take a look into the [schematic](https://github.com/ginkage/FlippAirMouse/tree/main/schematic) folder for Gerber, BOM and CPL files, so you can order directly from JLCPCB.

Original idea:
![What I thought it would look like](https://github.com/ginkage/FlippAirMouse/blob/main/schematic/schematic.png)

Expectation:
![What EDA though it would look like](https://github.com/ginkage/FlippAirMouse/blob/main/schematic/render.png)

Reality:
![What it looks like](https://github.com/ginkage/FlippAirMouse/blob/main/schematic/flipper.jpg)


## Software

If you're familiar with Flipper applications, start in the firmware checkout folder and do the following:
```
cd applications/plugins
git clone https://github.com/ginkage/FlippAirMouse
cd ../..
./fbt fap_air_mouse
```
If you're not familiar with those, just grab a `fap` file from Releases.