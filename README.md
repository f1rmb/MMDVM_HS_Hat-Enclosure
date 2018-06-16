# MMDVM_HS_Hat-Enclosure
Enclosures for MMDVM_HS hats (various board revisions)

Based on the enclosure shape from *Toufik*, **F0DEI**, here are some personnal variations, built from scratch.

**FreeCad** (https://www.freecadweb.org/) files are available (not for all variations, since the only differences are antenna and screen cutouts).

All STL files are also provided, just open them in your favorite slicer, then 3D print'em.

__WARNING__
You should use supports for top and bottom parts.

I'm using the daily snapshots (https://launchpad.net/~freecad-maintainers/+archive/ubuntu/freecad-daily), so using the latest stable version may not works.

 <br><br>
## Full height enclosures
![FULL](https://github.com/f1rmb/MMDVM_HS_Hat-Enclosure/blob/master/Assembly-All.png)

 <br><br>
## Slim enclosures
![SLIM](https://github.com/f1rmb/MMDVM_HS_Hat-Enclosure/blob/master/Assembly-All-SLIM.png)

 <br><br>
## Full height enclosures
All 3 major PCB versions are supported:

* 1,2
  * Known as "chinese* jumbospot
* 1,6
  * latest official version from DB9MAT and DF2ET (https://github.com/mathisschmieder/MMDVM_HS_Hat)
* 1.7
  * my slightly modified version, made out of a 1.6 fork (https://github.com/f1rmb/MMDVM_HS_Hat)


 <br><br>
## Parts needed for assemblies:

 __For full height assembly__

 Qty | Part
 ----|------
 1 | bottom assembly (file: MMDVM_HS_Bottom.stl) 
 1 | top cover (choose between blind, antenna and screen, in PCB-\<version\> directory, accordingly), non SLIM.
 4 | M2 1.2mm 3D printed washers (file: Parts/Washer-M2x1.2mm.stl)
 4 | M2 11.35mm 3D printed spacers (file: Parts/Spacer-M2x11.35mm.stl)
 4 | M2x30mm socket headed CHC screws
 4 | M2 hex nuts
 4 | M3x30mm socket headed CHC screws
 4 | M3 hex nuts

 <br><br>
 __For SLIM assembly__

 Qty | Part
 ----|------
 1 | bottom assembly (file: MMDVM_HS_Bottom-SLIM.stl) 
 1 | top cover (choose between blind, antenna and screen, in PCB-\<version\> directory, accordingly), -SLIM.
 4 | M2 1.2mm 3D printed washers (file: Parts/Washer-M2x1.2mm.stl)
 4 | M2 5mm 3D printed spacers (file: Parts/Spacer-M2x5mm.stl)
 4 | M2x16mm socket headed CHC screws
 4 | M2 hex nuts
 4 | M3x16mm socket headed CHC screws
 4 | M3 hex nuts
 
 ***Some specific assembly informations will be added later about this SLIM version.***

 <br><br>
## License
This project is released under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 (CC-BY-NC-SA 4.0, https://creativecommons.org/licenses/by-nc-sa/4.0/) license. You may edit and share it as you like, as long as credit is given and the license is not changed. You can build as many enclosures for you and your friends as you like and you can even sell it to them to cover your costs, **however it is strictly forbidden to turn this into a commercial product! You are not allowed to build and sell these enclosures for profit!. WE ARE HAM RADIO, keep that in mind!**
