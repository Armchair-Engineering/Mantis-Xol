# Mantis Xol 2 is now [Xol-Toolhead](https://github.com/Armchair-Engineering/Xol-Toolhead)
## We have moved over to a [new home](https://github.com/Armchair-Engineering/Xol-Toolhead) and made some big updates which will make the toolhead much easier to use, maintain, and build.
Go to [https://github.com/Armchair-Engineering/Xol-Toolhead](https://github.com/Armchair-Engineering/Xol-Toolhead) and check it out.

<br/> 
Everything seen below here, and still in this repository is now an archive.

___

## Mantis Xol 2 [ARCHIVE]
<img src="https://cdn.discordapp.com/attachments/929168771216723968/1020895467674026024/unknown.png" width=200px>

### Description
Originally a project to slap 5020 blower fans onto Mantis, this toolhead variant started as an attempt to improve parts cooling, spurred on by Derpimus' noted cooling woes on his DOOMCube. After finding that the 5020s were just plain too fat to fit without looking like a standard Ender 3 Thingiverse special, I abandoned the large fan dream in favor of better cooling efficiency and lighter weight. This new and improved dream was also corrupted by my then budding and now all-consuming love for worm gears.

[![Join me on Discord](https://discord.com/api/guilds/1029426383614648421/widget.png?style=banner2)](https://discord.gg/armchairengineeringsux)

### New Features for Xol 2
 - Cooler: Still a little ugly but better
 - Lighter: 260g-ish for Sherpa Mini
 - Rigid-er: I want to throw this thing across the room

##### Features:
 - Better airflow than Stealthburner (6-7 CFM through short ducts vs 4.6-5.2 CFM through long ducts)
 - Improved resonance management compared to Mantis 5015
 - Support for Sherpa Mini-pattern extruder mounting as well as Annex Engineering's **Double Folded Ascender** worm gear extruder
 - Support for JosAr's Klicky, VinnyCordeiro and WhoppingPochard's PCB Klicky, and Nionio6915's Euclid
 
##### Supported (incl. usermods/experimental):
|Hotends |Extruders |Probes |
|--- |--- |--- |
| Rapido HF | Sherpa Mini | VoronDesign's TAP |
| Dragon SF/HF | Orbiter 2 | Beacon (normal) |
| Revo Voron | Vz-hextrudort | (PCB) Klicky |
| Phaetus XG | DropEffect | Euclid |
| Bambulab | LGX Lite |--- |
| Dragon UHF Mini / NF Crazy |--- |--- |
 
##### Future Development (No ETA):
 - Bracing for PCB mounts
 - Quickdraw 2 support
 - Update DFA Bottom to latest version for slightly better heatset quality of life
 - Port nozzle LEDs to Xol 2 (see usermods)
 - Port MMU sensor support to Xol 2
 - Confirm fitment for MattTheBaker's Beacon


### Build Notes:
This toolhead might require other modifications to retain full functionality of your printer. 
 - All test machines used for this mod had Rama's front idlers which have a much lower profile compared to stock Voron front idlers. The fan assemblies might conflict and reduce usable X travel.
 - The Klicky Probe carriage that was adapted was originally designed for the Dragon hotend. You'll need to use a taller probe body to reach the bed such as the one used by [Unklicky BFP](https://github.com/majarspeed/Unklicky). *This isn't an issue for Euclid or PCB Klicky*.
### Bill of Materials 
|Item|Count|Note|
|----|-|--|
|Rapido or XG|1|
|4010 24v blower fans|2|Add Polulu 3796 if you want the fancy 12v Deltas|
|2510 24v axial fan|1|
|M2x8 SHCS|2|
|M2x12 SHCS|4|
|M2x20 SHCS|2|
|M2.5x20 SHCS|4|
|m3x6 BHCS|7|
|m3x8 BHCS|7|
|m3x20 SHCS|2|
|M2 Heatset 4L x 3.5 OD|11|
|M3 Heatset "Standard"|10|
|D2F-5L Microswitch|1|
|M2x8 or M2x10 Self-Tapping|1|Optionally 1 more M2 heatset and an M2x8 SHCS|
|6x3 magnets|3|
|ZIP TIES||
### Changelog
#### 29 November 2022 - Beacon Support
- Release Day means Beacon Support. Find it in the Experimental folder.
#### 27 November 2022 - Tap Support
- Release Day means Tap Support. Find it in the Experimental folder.
#### 22 November 2022 -Revo Voron
- Added support for Revo Voron with the Sherpa Mini Hotend mount
#### 10 November 2022 - Shiny shiny
- Added nozzle LED support. Find it in the Experimental folder.
#### 23 October 2022
#### 3 October 2022 - Xol 2
- Improved aesthetics
- Downsized HE fan to 2510
- No more self-tapping screws
- Added front brace for Sherpa Mini
- New ducts for Tridents with lead screws
- Miscellaneous printability improvements
#### 3 Aug 2022 - Xol with Boots
- Added MGN9H carriages for PCB Klicky
- Added additional stabilization for ducts. Ideally, these are fastened with 2x M2x20 and M2 heatset inserts.
![image](https://user-images.githubusercontent.com/86749712/182743176-836717be-50c4-4e77-87a8-01fd74bdcb33.png)

### Acknowledgement
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
