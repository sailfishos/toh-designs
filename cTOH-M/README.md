**cTOH-M - clip based TOH for magnetic mounting**



The Jolla Phone (2026) (see here: https://commerce.jolla.com/products/jolla-phone-october-2026), which launched in July 2026, is a phone that comes natively with the European mobile OS "Sailfish OS" and features a modular back plate, open for modding by the community. I took measurements from the real product and iterated until I got a 3d printable TOH that fits and is held strongly in place. 

It is sufficient to just print the frame and the camera bump. Optionally one can also print the clips (orientation as in the 3mf file, otherwise they will break and not work) but that requires fiddly assembly and possibly more fine tuning, depending on your extrusion calibration. 



![cTOH-M yellow](https://github.com/thejiral/toh-designs_cTOH-M/blob/thejiral-cTOH-M/cTOH-M/IMG/yellow.jpg)

**Print files**

*1-frame-final.step* is the main frame and *2-Bump-Final2_with_integrated_supports.step* is the insert for the camera bump. You need to print both. 
*1-frame-final.step* is designed to have some extra external margins for sanding for a nice smooth surface. If you do not plan to do any surface sanding, there is the the alternative *Optional_Frame-Final1-no sanding.step* file of the frame without those extra margins. Fully optional are the internal clips (*Optional_Clips.3mf*), they make the assembly more robust but are not required for assembly. 


**Required additional parts**

CloudValley Mobile Phone Ring Holder for MagSafe (https://www.amazon.de/dp/B0FW45FLLW), which includes also the metal ring for the back plate assembly. 


**Printing advice**

*IMPORTANT: The frame and bump cover are designed for rescaling in the slicer by X=100.3%, Y=100.3%, Z=100% if printing with ASA.*

The phone can get quite warm, PLA is not advised, also because it gets brittle and is prone to creeping.  I recommend using ASA, it is more flexible than PLA but a bit less than PETG and is UV resistant. PETG is also an option but consider what you think feels nicer to the touch. 

In both cases an enclosure is advised, but with ASA it is likely required, for PETG merely beneficial.  I found with ASA that printing at regular Prusa MK3 Quality speeds with 100% cooling I got the best results (with sufficient layer adhesion), in an enclosure that reached around 35-40°C. You will get much better layer adhesion with ASA if you have a printer that manages enclosure temperatures of above 55°C. 

The model is quite sensitive towards differences in shrinking (due to material choice) and extrusion coefficient (over/underextrusion). Fine tuning of these two factors might be needed for the right clamping strength and dimensional accuracy of the frame. 

Object orientation: The frame is printed with the flat side down, without support, the bump is printed with the wide side down, it has integrated supports and does not need additional supporting. If custom supports are preferred, separate parts of the object, then supports structures can be deleted. The clips have to be printed on the side, that the profile is in layer plane. Print the clips in multiple copies with other objects or a dummy print to ensure dimensional accuracy. 

**Post treatment**

I sanded down all outer surfaces, which improves the looks but is not required.


**Assembly**

Optional clip insertion (clip 1: bottom left, pointing outward; clip 2: bottom right, pointing outward; clip 3: middle lower section, pointing left; clip 5: upper middle section, pointing outward to the closer end; clip 6: upper left, pointing outward; clip 7: upper right, pointing outwards) 

Remove the protective film from the metal ring and glue it with the sticky side into the ring shaped cavity on the inside of the frame

Put the camera bump cover onto the camera module and clip the frame into place, fixing the camera bump cover into place (The bump cover can alternatively be glued in to the frame from the inside out before clipping it into place)


PS: Feel free to use this model as a starting point for designing other TOHs
