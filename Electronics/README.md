# Instructions for Electronics

## Supplies
### Materials:
- Arduino Leonardo
- Arduino Prototyping Shield (does this come with headers?)
- 10 mm RGB LED
- 10 mm yellow LED
- 330\Omega resistor
- 270\Omega resistor
- Heat shrink
- Solid core 22 or 24 gauge wire in black, red, and 3 other assorted colors

### Tools
- Soldering iron + accessories
- Thingy to hold electronics in place while soldering
- Wire strippers
- Wire snippers

## Instructions

Beginning by prepping the wire that you will need. You will need:
- Two 3-inch pieces of black wire
- One 4-inch piece of each red and three other colors
In total, you should have 6 pieces of cut wire.

First, we will prep the prototyping shield. Snip the male-to-male headers into four pieces to match the width of the four block of female headers on the Arduino Leonardo. Then, solder the headers into the prototyping shield such that it matches the Leonardo and can be used as a shield for the Leonardo. If you are struggling to ensure they line up perfectly, stick the male-to-male headers into the Leonardo's female headers, and wiggle the prototyping shield so that the holes align with the male headers that are sticking up. Then, mark those spots, take the setup apart, and proceed to solder the male-to-male headers into the marked locations.

Once the prototyping shield is prepped, we can move to the LEDs.

Begin with the yellow LED. Note that the positive leg of the LED is longer.  


We will begin by prepping the LEDs

Using the splicer of your choice, download the STL files and assemble them onto the print bed, selecting your desired print settings. Note that you will need to print:
- 1 **Base**
- 1 **MidLayer**
- 1 **TopLayer**
- 2 **Rod**s

For each of these STL files, you can view a PNG of the design in this folder as well.

If you used PLA filament and have sandpaper available, it can often be nice to smooth the edges of your 3D printed parts, beginning with the coarsest sandpaper and working your way up. However, this step is optional and purely aesthetic.

Using scissors, cut the orange filter paper into two small hexagons so that each hexagon lies flatly on the inside of openings at the top of **TopLayer**. This can be a tricky process, as you want to make the hexagons you cut small enough to lay flatly inside, but not so small that they do not evenly cover the open channel. Begin by cutting two squares that are much bigger than necessary, and then cutting them down, bit by bit, until they reach the correct size.

To put everything together, you will need to place the Arduino and the attached shield inside the **Base**, making sure to line up the USB port with the side of the **Base** with the corresponding opening. The LEDs should be poking up from the top. Then, slide the two LEDs through the opening on **MidLayer**, lining each LED up with its own hole. Push the **MidLayer** down until it fits into the **Base**, and push the LEDs down so that they lie evenly aginst the **MidLayer**. At this point, it should look like a box with two LEDs poking out of the top (it's okay if you need to hold it in place to achieve that effect). If the LEDs are poking up so much that they don't look evenly flat against the **MidLayer**, try to pull the extra wire on their connections underneath the **MidLayer** as much as possible so that they are pulled evenly.

At this point, place the flat side of **TopLayer** on top of **MidLayer**, allowing the holes on the flat part of **TopLayer** to line up with the LEDs. You should be able to see both LEDs evenly through the two rod openings sticking out of **TopLayer**. Use the rubber band to hold the entire enclosure together, wrapping it between the two rod openings on the top of **TopLayer** and down around the notch at the bottom of the **Base** (make sure this is tight enough to hold everything in place--you might need to wrap it around twice to keep it taut).

Finally, place the two hexagon filters that you cut previously into the tops of the rod openings on **TopLayer**, placing care to lay them evenly to cover the openings. Push each **Rod** into those openings (effectively snapping the filter into place). Look through each rod and make sure that the enclosure looks even, the rods look straight, the filter paper completely covers the openings, and the LEDs are even.
