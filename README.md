
# Pehmis Sofle V2 case

<a href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img src="https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg" alt="Licence" height="25"/></a><a href="https://www.paypal.com/donate/?hosted_button_id=LNPV4WR7C95VA"><img src="https://img.shields.io/badge/Donate-PayPal-blue" alt="Donate button" align="right" height="25"/></a>

A 3D printed, seamless case with magnetic wrist rests for the Sofle V2 keyboard

![](_Images/sofle1.png)

---

### --> [Original Sofle keyboard repository](https://github.com/josefadamcik/SofleKeyboard)

### --> [Original Elmo Case Repository](https://github.com/kb-elmo/SofleCase)

**Please note that only the v2.0 and 42keebs V2.1 versions are compatible with this case. The V2.1 Sofle with per-key RGB is not compatible.**

---

## Assembly materials needed

* **10x** m2x8mm screws for the cases.
* **20x** m2x4mm screws for the plates (If you bought a sofle kit these should be included).
* **10x** m2x8mm standoffs for the pcbs (If you bought a sofle kit these should be included).
* **10x** m2x4x3.5mm heat-set threaded inserts to screw the cases together.
* **16x** 8mm rubber bumpons (optional).
* **8x** 8x3mm magnets to attach wrist rests (optional).

## Changes to Elmo's original case

* Added magnetically attached wrist rests.
* Added holes for heat-set threaded inserts to avoid screwing the case bottoms into bare plastic.
* Raised the top of the case by 1mm to look nicer with cherry profile caps.
* Moved usb port holes and made more space inside to fit a socketed regular pro micro instead of elite-c.
* Changed to "tray mount" style to allow use with a normal plate from a sofle kit instead of a printed one.
* Removed rgbled-strip channels on the bottom. Depending on the size of your strips you might still be able to fit some under the pcb.
* Modified knob to work with raised case and plum style encoder shaft.
* Enlarged reset button holes and added a second pair to work with 42keebs V2.1 kit.
* Enlarged rubber bumpon pads to fit 8mm bumpons.

## Please note

* The two case halves are not symmetrical!  
Just using one of the files and mirroring it in your slicer will not work.  
The holes for the TRRS and usb cables are in slightly different locations on the two sides.
* The reset switch on both sides of the board should ideally be mounted on the bottom of the PCB.  
That way you can press the button through the hole in the bottom of the case without having to disassemble the entire board.
* The included knob is designed for the Alps EC11 encoder with a 15mm tall plum shaft.  [Such as this one.](https://www.aliexpress.com/item/1005002767327743.html)
If you are using a different model you might have to use a different knob for your board.
* 3MF files are oriented for best print results and don't require supports.

## Assembly instructions

1. Assemble the Sofle keyboard like you would normally, but don't screw the fr4/acrylic bottom on. 
2. Instead screw the keyboard halves into `Left-Bottom` and `Right-Bottom` respectively with the `m2x4mm` screws.
3. Install the heat-set threaded inserts into the holes in `Left-Top` and `Right-Top`.
4. Slot the case bottoms into the tops, and screw together with the `m2x8mm` screws.
5. Install `Knob-X2` into the encoders.
6. Glue the `8x3mm` magnets into the holes in `Left-Top`, `Right-Top`, `Left-Wristrest` and `Right-Wristrest`

## Special Thanks to

* Josef Adamcik for designing the original Sofle keyboard and making the project open source.
* kb-elmo for making the original version of this case and sharing the step files.

---

These files are meant for 3D printing only! 

They are not suitable for CNC machining and trying to use them for that will most likely result in unusable parts.

---
## Exploded view

![](_Images/render1.png)

---

_Licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa]._

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/

<a href="https://www.paypal.com/donate/?hosted_button_id=LNPV4WR7C95VA"><img src="https://github.com/andreostrovsky/donate-with-paypal/raw/master/dark.svg" alt="Donate button" width="400px"></a>
