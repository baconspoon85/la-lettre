![La Cuillere Front View](https://github.com/baconspoon85/la-lettre/assets/101666389/9279e423-1bd3-47c9-81c4-8dfd341255b2)

La Cuillère is a drop in PCB designed for La Lettre, by somepin. The original case and plate support a QAZ-like, traditional row-stagger layout. Together with the modified plate file in this directory, La Cuillère Hotswap PCB supports three layouts:

- Traditional row stagger, with 0.25u stagger between the top two alpha rows and 0.5u stagger between the bottom two
- Uniform row stagger, with a uniform 0.25u stagger between rows
- “Alpha” row stagger, where the top two alpha rows are ortholinear and the bottom alpha is staggered 0.5u (as with traditional row stagger) 

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
![434347585_339994722383188_2484670211822083277_n](https://github.com/baconspoon85/la-lettre/assets/101666389/0272483e-5f26-45ef-87eb-696feccc761c)
![434336551_793017306040206_5648405254212680459_n](https://github.com/baconspoon85/la-lettre/assets/101666389/0db81253-40a7-4ee9-a4d7-cfb53e89fc0a)
![432507778_1146231560055321_1128930338330979377_n](https://github.com/baconspoon85/la-lettre/assets/101666389/b534818e-b16f-4258-9ca5-8f32dbd76e1f)
![434771373_957041872763355_3705679784430354849_n](https://github.com/baconspoon85/la-lettre/assets/101666389/8de4ebae-0e1f-4a1f-9986-c3d5f9ada70c)
![434726009_724846703062193_7743425114401481803_n](https://github.com/baconspoon85/la-lettre/assets/101666389/d2f502c5-1702-4bc3-8a30-ce6560ac6636)

