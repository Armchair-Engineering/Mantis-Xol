# SLMantis Xol 2 ALuminum Boogaloo (Slimfast)
![image](https://cdn.discordapp.com/attachments/929168771216723968/1020895467674026024/unknown.png)

## Description
Originally a project to slap 5020 blower fans onto Mantis, this toolhead variant started as an attempt to improve parts cooling, spurred on by Derpimus' noted cooling woes on his DOOMCube. After finding that the 5020s were just plain too fat to fit without looking like a standard Ender 3 Thingiverse special, I abandoned the large fan dream in favor of better cooling efficiency and lighter weight. This new and improved dream was also corrupted by my then budding and now all-consuming love for worm gears.

This was further pushed into the territory of abomination By deadwood83 who decided that plastic just wasn't metal enough, but a straight metal print was too heavy.  Since he was too plebian to have a worm-geared extruder, only Sherpa Mini support currently exists.

https://discord.gg/armchairengineeringsux

## New Features for SLMantis Xol 2
 - Cooler: Think Xol is ugly? This is not any better. But the entire hotend is now a heatsink.
 - Metaler: There is so much more metal. All inserts are replaced by tapped holes.
 - Rigid-er-er: Look at all that metal in the all-metal construction.

#### Features:
 - Better airflow than Stealthburner (6-7 CFM through short ducts vs 4.6-5.2 CFM through long ducts)
 - No inserts. No worries about thermal deformation.
 - Support for Sherpa Mini-pattern extruder mounting.
 - Support for Whoppingpochard's Klicky PCB and bacon, but hardpoints on the bottom of the carriage allow for a modular approach to probing.
 - Top hardpoints and pockets allow development of custom tophats for your toolhead. Umbilical? Sure. Mantis tophat to bolt more stuff to your toolhead?   Sure.
 - Cross-compatibility with most of the XOL2 printed parts. YOu can combine metal hotend mount with a printed carriage, vice-versa, use printed ducts, printed faceplates, LED holder, nozzle camer amounts. 
 - X axis microswitch in either direction (min/max/both)
 
#### Future Development (No ETA):
 - MGN12 Carriage
 - Unnamed things because we have not discovered what else we may want to paste onto this. 


## Build Notes:
This toolhead might require other modifications to retain full functionality of your printer. 
 - All test machines used for this mod had Rama's front idlers which have a much lower profile compared to stock Voron front idlers. The fan assemblies might conflict and reduce usable X travel.
 - The Klicky Probe carriage that was adapted was originally designed for the Dragon hotend. You'll need to use a taller probe body to reach the bed such as the one used by [Unklicky BFP](https://github.com/majarspeed/Unklicky). *This isn't an issue for Euclid or PCB Klicky*.
## Bill of Materials 
|Item|Count|Note|
|----|-|--|
|Rapido|1|
|Sherpa Mini|1|CNC optional, but rigider-er-er|
|M2 Tap|1|
|M2.5 Tap|1|
|M3 Tap|1|
|4010 24v blower fans|2|Add Polulu 3796 if you want the fancy 12v Deltas|
|2510 24v axial fan|1|
|M2x8 SHCS|2|
|M2x12 SHCS|4|
|M2x6 SHCS|2|For Belt Pre-tension (MGN9 Version)|
|M2x20 SHCS|2|
|M2.5x20 SHCS|4|For Cooling Fan|
|M2.5x8 90Deg CS|3|For Rapido mount|
|M3x6 BHCS|2|For Mount<->Carriage Lower Fasteners|
|M3x6 SHCS|1|For Sherpa K-mount|Up to 6 more for top and bottom attachments|
|M3x10 90Deg CS|4|For carriage to block mounting|
|M3x20 SHCS|4|Sharpa<->Hotend Mount and Hotend<->Carriage upper mount|
|D2F-5L Microswitch|1-2|
|ZIP TIES||


## Acknowledgement
[Long/Mandryd](https://github.com/mandryd/VoronUsers/tree/master/printer_mods/Long/Mantis_Dual_5015) for the Mantis toolhead.<br/>
[TheWarolf](https://github.com/TheWarolf/Voron-Personal-Mods/tree/main/V2/Long_Mantis_Toolhead) for the ERCF sensorized Hotend Mount.<br/>
[Derpimus](https://github.com/lraithel15133) for the exegesis, some CAD work, feedback, and just being a rad dude.<br/>
[KayosMaker](https://github.com/KayosMaker) for the MGN12 Klicky X-Carriage and CAN board mounts and spacers.<br/>
[JosAr](https://github.com/jlas1/Klicky-Probe) for Klicky.<br/>
[WhoppingPochard](https://github.com/tanaes) and [VinnyCordeiro](https://github.com/VinnyCordeiro/) for PCB Klicky.<br/>
[Nionio6915](https://github.com/nionio6915/Euclid_Probe) for Euclid. <br/>
[VoronDesign](https://github.com/VoronDesign) for this particular CoreXY flavor.<br/>
[AnnexEngineering](https://github.com/Annex-Engineering) for the Sherpa Mini and Double Folded Ascender extruders, and the K3 that influenced the air management of the ducts. And also for giving access to an early revision of the new DFA so it could be adapted for this toolhead.<br/>
[Clee](https://github.com/clee), you know what you did.  
[Takuya](https://github.com/T4KUUY4)... just added the 36mm SB2040 mount
