La Cuillère is a drop in PCB designed for La Lettre, by somepin. The original case and plate support a QAZ-like, traditional row-stagger layout. La Cuillère PCB and the modified plate file in this directory support three layouts:

- Traditional row stagger, with 0.25u stagger between the top two alpha rows and 0.5u stagger between the bottom two
- Uniform row stagger, with a uniform 0.25u stagger between rows
- “Alpha” row stagger, where the top two rows are ortholinear

The modified plate and PCB are compatible with the original case design, provided that consideration is made for mounting a USB-C daughterboard in the bottom case. This repository also includes design files for a modified case (top and bottom) which has mounting for a C Series Unified Daughterboard (UDB): 

https://unified-daughterboard.github.io/#/?id=unified-daughterboard

Modifications to La Lettre case for La Cuillère:

- UDB mounting added to bottom case in place of ProMicro mounting
- Closed viewing window in bottom case and embossed the name "La Lettre" on the underside
- Removed screw entry points which were visible from the back of the case
- Closure on the rear of the case was swapped from screws to a series of six 3mm height by 3mm diameter neodymium magnets. Front screw closure with recess for heatset inserts is maintained. Magnets should be heat set into the added recesses.
- Overall case height is raised by approx. 1mm to accomodate mounting.
- Embossed case underside to accomodate 0.7" diameter rubber feet (standard MacBook feet)

Alternate layout support is achieved by using unconventional key sizes on the interior columns, rather than by using multiple case tops and plates. This, combined with the use of kailh hotswap sockets will allow for multiple quick rebuilds to find your preferred row stagger. A KLE showing all layout options can be found here:

http://www.keyboard-layout-editor.com/#/gists/177f0f58f8eeb77604e0b0c7e826185b

CASE EDITS HAVE NOT BEEN PROTOTYPED OR PHYSICAL TESTED IN ANY WAY. A BUILD GUIDE WILL BE ADDED ONCE TESTING IS COMPLETE.

FIRMWARE HAS NOT BEEN WRITTEN FOR LA CUILLÈRE PCB. GMK/VIAL FIRMWARE IS PENDING AND WILL BE ADDED TO THIS REPO ONCE COMPLETE. YOU CAN BULD CUSTOM FIRMWARE FROM THE KICAD SCHEMATIC AND CONTRIBUTE HERE IF YOU ARE SO INCLINED. 