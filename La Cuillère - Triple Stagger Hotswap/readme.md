![La Cuillere Front View](https://github.com/baconspoon85/la-lettre/assets/101666389/9279e423-1bd3-47c9-81c4-8dfd341255b2)

La Cuillère is a drop in PCB designed for La Lettre, by somepin. The original case and plate support a QAZ-like, traditional row-stagger layout. La Cuillère PCB and the modified plate file in this directory support three layouts:

- Traditional row stagger, with 0.25u stagger between the top two alpha rows and 0.5u stagger between the bottom two
- Uniform row stagger, with a uniform 0.25u stagger between rows
- “Alpha” row stagger, where the top two rows are ortholinear

![la-cuillère---tripple-stagger-pcb-for-la-lettre-by-somepin](https://github.com/baconspoon85/la-lettre/assets/101666389/b1477fd8-f8b5-469a-9af2-ac1378ef8482)


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

![La Cuillere Side View](https://github.com/baconspoon85/la-lettre/assets/101666389/21a24f49-0cb8-4001-bc11-51fcad0c4aa5)
![La Cuillere Rear View](https://github.com/baconspoon85/la-lettre/assets/101666389/156f1966-f9c4-47dc-bb00-1ddbce6085cc)
![La Cuillere Top View](https://github.com/baconspoon85/la-lettre/assets/101666389/26f11bc4-4842-42f2-9d0c-c75164ac617b)
![La Cuillere Bottom View](https://github.com/baconspoon85/la-lettre/assets/101666389/3ad5f571-cda9-4414-9e9a-12db01a66651)
