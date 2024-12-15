---
title: Getting Started
parent: 3D Print Lab
nav_order: 1
---

# Getting Started in The Print Lab
There are several things to consider when 3D printing. What materials are best suited for my application? Which printers will work with my desired materials? Will my model fit the printer's bed? This document can help you answer these questions, but is by no means meant to cover all possibilities. We can get you started, but mastery of these concepts and the equipment is up to you!

## Printers
We have too many printers to put all of this information here! Consult this chart to get a sense of the capabilities of and software considerations for our various printers.

## Common Fillament Materials
PLA - A low temperature plastic. At room temperature, it's brittle. At higher temperatures, it becomes more pliable. Both of these properties make it prone to failure in high stress applications. Don't write it off just yet, though. It's still an excellent material in a lot of use cases and nearly all FDM printers will print it with no issue. It's considered easy to print, because, of all commonly available fillaments, it's the least prone to warping.

TPU - It's soft an squishy and melts at a relatively low temperature (comparable to PLA). It's relatively difficult to print without special considerations. It can't bridge or overhang well. If the extruder needs to move away from material that's already been layed down, expect stringing. TPU is also prone to clogging nozzles, so we only offer one dedicated printer for handling TPU. See printer chart for detail.

PETG - Offers more temperature resistance, impact strength, and tensile strength compared to PLA. Compared to ABS, it's more UV resistent. Do not take this as an invitation to leave PETG in the sun, it will still degrade and become brittle over time. A temperature controlled enclosure is recommended, so this is generally limited to our Bambu printers.

ABS - One of the most temperature resistant materials we can print. It's more flexible/pliable than PETG at room temperature and offers slightly better impact and tensile strenghts. If it's exposed to higher heat, ABS is probably your best bet (becomes a wet noodle at 105C, so keep it a fair deal under that!). Strength degrades relatively quickly with prolonged UV light exposure. Like PETG, this should be printed in an enclosure.

## Software: The Slicer
So you've picked the materials and the printer you want to use and you have a model you want to print. Great, but we still have one more step before you can begin printing. It's important to understand that these printers are relatively dumb machines. We can't throw a model at them and expect them to know what to do with it. We need to give the machine explicit instruction on how to move all of its parts and adjust its heaters and fans to give us a decent print. To do this, we use a piece of software called a slicer that analyzes our model layer by layer and generate the necessary machine instructions (g-code) for us. We use two different slicer software packages depending on the type of printer. Be sure to consult the printer chart and slicer guide to make sure the right software and settings are being used for a chosen printer.

## I can't be bothered, I just want to see something print
Fair enough! Feel free to use any of these files in Bambu studio with PLA filament on the Bambu X1C. Just make sure you use our reservations system and follow this simple Bambu Studio guide!

## I don't have a model, but I have an idea. What do I do?
Ah, you're looking to design! That's a subject we can't easily teach, but, with enough demand there may be workshops on the topic. Many of our members use OnShape, a free, online CAD package. For making simple models in a relatively intuitive (albeit, functionally restrictive) software, you might explore TinkerCAD.
