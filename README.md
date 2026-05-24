# 60_keyboard

This is the design of a custom keyboard for myself.

Ideas I would perfer for my keyboard:

A keyboard with a small spacebar so that there can be modifiers such as super, alt and ctrl easily assesable with my thumbs. Similar ot a JIS layout.

The keys closer to orthogonal in the second row, since it moves some keys on the right far.

Remove the top row of keys since they are difficult to reach, and I never seem to use them. ESC and delete can be moved down.

Remove the dedicated caps lock key since I never seem to use it.

Then ideally move the []\ keys so that they may be closer.

# Hardware 

Based on ESP32, choosing the least expensive one in the JLPCB library with enough IO and RISC-V core. Choosing ESP32-C6. 

Looking to make a 12x5 matrix for the keys after idea generation, this layout is in the layout_idea folder.

Looking to use standard MX mechanical switch sockets with hot swapable recepticles for potential replacement in the future. 

One usb interface.

Also have a diode on each key so that ghosting is not an issue.

# Overview of the Repo 

PCB is designed in the the PCB folder, the 3D CAD is designed in [OnShape](https://cad.onshape.com/documents/0a169c5ae1023445fae5efdd/w/4e7a7d406d370b73ca30bc79/e/bc0921f5439b5b5204013faf?renderMode=0&uiState=6a13294e8f64716ebe2b3083) with stl files and gcode files for an Ender 3 pro in the 3dcad folder, and the firmware is in the firmware folder.
