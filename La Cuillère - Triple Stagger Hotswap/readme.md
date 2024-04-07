La Cuillère is a drop in PCB designed for La Lettre, by somepin. The original case and plate support a QAZ-like, traditional row-stagger layout. La Cuillère PCB and the modified plate file in this directory support three layouts:

- Traditional row stagger, with 0.25u stagger between the top two alpha rows and 0.5u stagger between the bottom two
- Uniform row stagger, with a uniform 0.25u stagger between rows
- “Alpha” row stagger, where the top two rows are ortholinear

![la-cuillere---tripple-stagger-pcb-for-la-lettre](https://github.com/baconspoon85/la-lettre/assets/101666389/eb393a03-ffdb-4680-a793-099d683fd6a1)

The modified plate and PCB are compatible with the original case design, provided that consideration is made for mounting a USB-C daughterboard in the bottom case. This repository also includes design files for a modified case (top and bottom) which has mounting for a C Series Unified Daughterboard (UDB): 

https://unified-daughterboard.github.io/#/?id=unified-daughterboard

Modifications to La Lettre case for La Cuillère:

- UDB mounting added to bottom case in place of ProMicro mounting
- Closed viewing window in bottom case and embossed the name "La Cuillere" on the underside
- Removed screw entry points which were visible from the back of the case
- Closure screws on the rear and front of the case bottom were  moved to the left and right side to hide the screw entry points, 
which are visible from the rear on the original model
- Udercut added to the sides
- Redesined USB port for level entry (parallel to desk)
- Expanded top for increased clearance
- Modeled screw holed for threaded machine screw tapping
- Overall case height is raised by approx. 1mm to accomodate mounting
- Embossed case underside to accomodate SKUF silicone feet:  https://github.com/Zambumon/SKUF

Alternate layout support is achieved by using unconventional key sizes on the interior columns, rather than by using multiple case tops and plates. This, combined with the use of kailh hotswap sockets will allow for multiple quick rebuilds to trial until you find your preferred row stagger. 

Firmware is QMK with vial. The source is minimal, with the intention being for end user to either setup their desired keymap in Vial, or to flesh out the firmware themselves. Note that La Cuillere uses RP2040, so the compiled Vial hex is a UF2 file.
