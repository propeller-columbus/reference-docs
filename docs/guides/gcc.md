---
title: GCC Spirit GLS Laser Engraver
parent: Guides
nav_order: 2
---
# GCC LaserPro CO2 Laser Engraver Operation Instructions
{: .no_toc}

## Contents
{: .no_toc .text-delta }
1. TOC
{:toc}

## Power-on checklist:
- Laser power key is turned off (counter-clockwise)
- Work bed is clear
- Engraver is connected to computer
- Door is closed

## Setup
- Turn on main power switch (located on right side of machine).
  
![](../../../assets/img/gcc/gcc1.png)

- Wait for homing procedure to finish. The tool head will move to bottom left and then park in home position at the top left corner of the work bed.

![](../../../assets/img/gcc/gcc2.png)

- Open door; Ensure tool head will clear work piece. If needed, lower the bed with the down arrow under the “Auto Focus” button.

- Place workpiece on the bed.

![](../../../assets/img/gcc/gcc4.png)

- Position laser head over the workpiece. This can be done by manually moving the toolhead with your hand or by using the arrow buttons around the "Enter" button on the control pad.

![](../../../assets/img/gcc/gcc3.png)

- Find the autofocus probe in magnetic holder on the left side of machine. Install probe on the right side of the tool head. Ensure pins are aligned properly and insert firmly. Ensure it's fully seated and that the probe is perpindicular to the bed.

![](../../../assets/img/gcc/gcc5.png)

- Press the autofocus button, wait for the probe to touch the workpiece

![](../../../assets/img/gcc/gcc6.png) ![](../../../assets/img/gcc/gcc7.png)

- Now that surface focus is found, you may desire to focus laser beneath parts surface (cutting operations) or above the surface (wider, blurrier burn area). The focus can be adjust from here by raising/lowering the z axis with corresponding up/down arrow buttons surrounding the “Auto Focus” buttons.

- Once desired focus is set, leave the autofocus confirmation screen with the back button (top left of control pad, labeled on screen as "F1).

- Return autofocus probe to storage area.

![](../../../assets/img/gcc/gcc8.png)

- Before running laser, turn on fume extractor. Ensure it is running. Not only is this good for your health, but it also mitigates soot/particulate buildup on the laser lens and mirror. 

## Software
The GCC laser engraver acts like a regular printer. To make use of it, we need to use two pieces of software in conjuntion with each other: A graphics application and the proprietary GCC Spirit print driver used to control the laser.

### Vector graphics applications
On the laser engraver workstation, there are two primary graphics applications: CorelDraw and Inkscape. CorelDraw is a paid application, while Inkscape is a featureful, free alternative. We can't cover their full usage, so feel free to experiment with them or read through their respective documentation.

[CorelDraw](https://www.coreldraw.com/en/learn/academy/)
[Inkscape](https://inkscape.org/learn/)

### GCC Print Driver
There are many settings that can be adjusted to suit your needs. The easiest way to get started is using black and white mode and adjusting pen settings for the black pen between separate print jobs. Please consult the GCC Spirit user's manual for detailed information on how to setup the print driver for your job.

[GCC Spirit manual/ print driver options](https://www.gccworld.com/data/file/upload/UserManual/Laser/Spirit-AC_User-Manual.pdf#page=141)

## Vector vs. Raster
Vector graphics and raster graphics are fundamentaly different. It's important to understand what each are and how the GCC Spirit print driver will treat your files.

Raster graphics follow a set grid where points of light are defined. Raster graphics are composed of vector paths rather than individual points on a grid. The engraver will follow a vector path if it's set to hairline width in your graphics software. This is especially useful for cuts. Paths wider than hairline width and imported images will be rasterized. Raster procedures by the laser will be performed by moving the head horizontally and scanning vertically across the workpieces; similar to how an inkjet printer works.

## External resources
[GCC Spirit Manual](https://www.gccworld.com/data/file/upload/UserManual/Laser/Spirit-AC_User-Manual.pdf)
*NOTE: We do not have the fiber laser option and maintenance tasks cannot be performed without explicit permission.*

[Inkscape download (Windows, Mac, and Linux)](https://inkscape.org/release/)

[CorelDraw free trial](https://www.coreldraw.com/en/free-trials/)
