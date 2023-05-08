# Marantz 2225 Pre-Tone Amplifier PE01 (pre-amp)

## Components
Components list can be found [here](https://docs.google.com/spreadsheets/d/1S8Fiy-nARGqUnUXXbVScigvOsDpP3ZsTfdl-bGImHVc/edit?usp=sharing).

## KiCad renders 
![2225_PE01_front_01](https://user-images.githubusercontent.com/6032986/213088241-cc220f7a-e4e4-4b19-a9d6-76f0b42e9d16.png)
![2225_PE01_front_02](https://user-images.githubusercontent.com/6032986/213088254-ce99458e-3d73-4800-ad91-e78f3055f076.png)
![2225_PE01_front_03](https://user-images.githubusercontent.com/6032986/213088268-3dfb4294-5c2b-4480-959e-ca9cb709ba35.png)
![2225_PE01_back_01](https://user-images.githubusercontent.com/6032986/213088283-adbb7b90-2a54-4350-aef7-f26d903c29f1.png)
![2225_PE01_layout](https://user-images.githubusercontent.com/6032986/213088331-7bbe73cd-9ac6-4176-aefa-265bec70f223.png)

## PCB Scans
![PE01_front](https://user-images.githubusercontent.com/6032986/200488690-93cd99f3-291e-4a86-bf1d-85c6e44d0a6d.jpg)
![PE01_back](https://user-images.githubusercontent.com/6032986/200488757-555df6c5-78a4-4e4e-a67c-136fc8b1f880.jpg)

## Schematic and Layout (from [Marantz 2225L service manual](https://www.manualslib.com/manual/907153/Marantz-2225l.html))
![PE01_layout](https://user-images.githubusercontent.com/6032986/200488873-2c793606-c4e8-48c0-b3b2-6a16a62e0062.png)
![PE01_schematic](https://user-images.githubusercontent.com/6032986/200488879-9dd9c354-ae6c-4e1c-b258-a5f0fd21bb11.png)

## Notes
- CE21 and CE22 should be 3.3µF, not 33µF as they're listed in the service manual.
- CE23 and CE24 are biopolar capacitors, which the service manual does not indicate. 
- The first prototype board substituted the specified 7.5K resistors RE13 and RE14 with 4.7K 1% components. The reason for the substitution was to mitigate clipping using aux input from a Macbook headphone jack, which was about 1.5VPP.

