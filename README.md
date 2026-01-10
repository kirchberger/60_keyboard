# 60_keyboard

This is the design of a custom keyboard for myself.

Ideas I would perfer for my keyboard:

A keyboard with a small spacebar so that there can be modifiers such as super, alt and ctrl easily assesable with my thumbs. Similar ot a JIS layout.

The keys closer to orthogonal in the second row, since it moves some keys on the right far.

Remove the top row of keys since they are difficult to reach, and I never seem to use them. ESC and delete can be moved down.

Remove the dedicated caps lock key since I never seem to use it.

Then ideally move the []\ keys so that they may be closer.

# Hardware 

Will be based on ESP32, choosing the least expensive one in the JLPCB library with enough IO and RISC-V core. Choosing ESP32-C6. 

Looking to make a 12x5 ish matrix.

Looking to use standard MX mechanical switch sockets for potential replacement in the future. It seems the mill max sockets are the best option.

One programming usb interface and one for connection.

Also have a diode on each key so that ghosting is not an issue.
