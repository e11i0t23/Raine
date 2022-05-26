# Raine PCB

PCB for the Raine by AKB, Please note the open source version has a reset button added to underside for compatibility with jlcpcb assembly 

---
##### Please Note these PCBs are provided under the MIT Liscence
---

### How to order
The steps bellow outline how to order this pcb with assembly through the JLCPCB platform  

1) From the releases section download CamOutputs.zip, BOM_Raine.xlsx, and PNP_Raine_Back.xlsx
2) Load the new order section of Jlcpcb, uploading CamOutputs.zip as gerber file
3) Most settings can be left as defualt, reccomend selecting LeadFree HASL under surface finish,
    (Note only Green or Black soldermask can be used with assembly)
4) Enable PCB assembly, choose wanted quantity, and select assemble bottom side then press next
5) For the Bom upload the file BOM_Raine.xlsx, for CPL upload PNP_Raine_Back.xlsx, then press next
6) Ensure file has loaded and no items show out of stock, then press next followed by add to basket
7) Once PCB has arrived QMK firmware can be flashed