# Instructions for CAD & Assembly

### Materials:
- 3D printer
- white filament (I used PLA, but any material that is stiff and has good geometric stability should be fine!)
- 400-4000 grit sandpaper (optional)
- two square inches of [Rosco #23 orange-colored filter](https://www.bhphotovideo.com/c/product/43934-REG/Rosco_RS2311_23_Filter_Orange.html)
- completed & assembled electronics (Arduino + shield + components)
- a rubber band or hairband to hold the enclosure together

### Instructions

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

[This video](https://onedrive.live.com/?authkey=%21AOk2AyiAh6hIyBw&cid=89B07BAA70C581C2&id=89B07BAA70C581C2%2142266&parId=root&o=OneUp) demonstrates the process as well.
