---
title: GCC Laser Engraver
parent: Guides
nav_order: 2
---
# GCC LaserPro CO2 Laser Engraver Operation Instructions
{: .no_toc}

## Contents
{: .no_toc .text-delta }
1. TOC
{:toc}

## Main power-on checklist:
- Laser power key is turned off (counter-clockwise)
- Work bed is clear
- Engraver is connected to computer
- Door is closed

## Setup
- Turn on main power switch (located on right side of machine), wait until manufacturer logo is no longer displayed on screen
  
![](../../../assets/img/gcc/gcc1.png)

- Wait for tool head to park in home position at the top left corner of work bed

![](../../../assets/img/gcc/gcc2.png)

- Place your workpiece on the bed.

- Position laser head over the workpiece by using the arrow keys surrounding the “Enter button”. If on the main screen, you may need to press an arrow key twice to begin manual XY positioning.

![](../../../assets/img/gcc/gcc3.png)

- If workpiece is too close too laser head, lower the bed with the down arrow under the “Auto Focus” button

![](../../../assets/img/gcc/gcc4.png)

- Install the autofocus probe to the tool head

![](../../../assets/img/gcc/gcc5.png)

- Press the autofocus button, wait for the probe to touch the workpiece

![](../../../assets/img/gcc/gcc6.png) ![](../../../assets/img/gcc/gcc7.png)

- Now that surface focus is found, you may desire to focus laser beneath parts surface (cutting operations) or above the surface (wider, blurrier burn area). The focus can be adjust from here by raising/lowering the z axis with corresponding up/down arrow buttons surrounding the “Auto Focus” buttons.

- Once focus is set, leave the autofocus confirmation screen with the back button

![](../../../assets/img/gcc/gcc8.png)

- Before running laser, turn on fume extractor. Ensure it is running. Not only is this good for your health, but the laser lens is protected from soot buildup. 

## Software
The GCC laser engraver acts like a regular printer. To make use of it, we need to use two pieces of software in conjuntion with each other: A graphics application and the proprietary print driver used to control the laser.

### Corel Draw
Corel Draw is the graphics application we have setup to use the laser. This application can handle both vector (shapes defined by lines) and raster graphics (shapes defined by points in a grid). It is important to note that the laser will only follow vector lines if the "hairline" thickness is used within Draw, otherwise, vectors will be treated as a raster image by the laser.

A free version can be installed on your home computer to get you acquainted. Alternativley, you can use a graphics application of your choice and import your files into Corel. No guarantees can be made on file type compatibility. For instance, one version of Corel Draw may have trouble importing a file that was exported from a different version. 

#### Page Setup

#### Tutorials
We can't cover the complete usage of Corel Draw. We'll leave it to you to master this application. Free versions can be installed on your personal computer and SVG and DXF files can be ran off from the the laser engraver computer. Please note, there can be differences between versions of Corel Draw (i.e. dimensional differences or incompatibilities between exported files). Here are some links to get you started.

### GCC Print Driver
#### Vector vs. Raster
#### Settings
