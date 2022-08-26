# 3dprintable_slew_bearing_openscad
A 3d printable customizable slew bearing designed with OpenSCAD

This is a complete reimplementation in OpenSCAD of the slew bearing created by Christoph Laimer. He implemented it in Fusion360 and made a nice Youtube video on how to design such a thing and testing it, highly recommended!

The main features of this over the one by Christoph Laimer are:
- customizable in Customizer
- integrated threads, so no need for additional screws
- tension adjustable (unscrew a bit to reduce tension)

I highly recommend printing the rollers in vase mode to get best possible surface quality. If your slicer allows, add some bottom and top layers to make the rollers stiffer.
The outer ring can be printed in one part, but two parts may provide better surface quality because otherwise there is a 45 degrees overhang.

The bearing height will determine your roller diameter and height, i recommend using a height of 8mm or more, otherwise it might be challanging to print and tolerances must be small.
I successfully printed bearings from 70x25mm diameter down to 13x2.5mm.
Without screwable outer ring 11mm should be possible. Rollers cant be printed that small, but you can use small chunks of 1.75mm filament as rollers.

Hints:
- Number of rollers are not (yet) automatically optimized. You should design it with minimal distance between rollers and number of rollers must be even! Easiest to adjust by changing height of bearing
- This does not feature the very cool kegel style rollers as designed by Christopf Laimer