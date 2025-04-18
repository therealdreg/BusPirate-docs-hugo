+++
weight = 100103
title = 'Bill  of Materials (6 REV 2)'
+++

![Boxes with reels of components ready for assembly](/images/docs/hw/bp5rev10/bom-rev10.jpg)

Bus Pirate 6 REV 2 is the latest production version (from August 2024) using the RP2350B chip. Find your revision number on the PCB near the production date (bottom) and the 10 pin connector (top). 

{{% readfile "/_common/_footer/_footer-cart.md" %}}

## Change Log
6 REV 2 uses the latest Raspberry PI RP2350B chip.
- Changed microcontroller (RP2040) to RP2350B with twice as much RAM, faster cores, more IO pins
- Add XXXX to enable a live action follow along logic analyzer, see what happens instantly while you work
- Add XXXX LDO voltage regulator to power the RP2350 core
- LED backlight controlled by RP2350 pin enables brightness control

## Bill of Materials

**NOT UPDATED**


| Brand | Part | Package | Description| Reel Quantity | Supplier |Changes|
|-|-|-|-|-|-|-|
| SAMSUNG(三星) | CL05B104KO5NNNC| 0402| 100nF ±10% 16V | 10000 |SZRCD|
<!--
| SAMSUNG(三星) | CL05C150JB5NNNC| 0402| 15pF ±5% 50V | 10000 |SZRCD|
| SAMSUNG(三星) | CL05A225MP5NSNC| 0402| 2.2uF ±20% 10V | 10000 |SZRCD|
| SAMSUNG(三星) | CL05A475KP5NRNC| 0402| 4.7uF ±10% 10V | 10000 |SZRCD|
| SAMSUNG(三星) | CL05C121JB5NNNC| 0402| 120pF ±5% 50V | 10000 |SZRCD|
| UNI-ROYAL(厚声) | 0402WGF1003TCE | 0402| 100K ±1% | 10000 |SZRCD|
| UNI-ROYAL(厚声) | 0402WGF1023TCE | 0402| 102K ±1% | 10000 |SZRCD|
| UNI-ROYAL(厚声) | 0402WGF1002TCE | 0402| 10K ±1%| 10000 |SZRCD|
| UNI-ROYAL(厚声) | 0402WGF1333TCE | 0402| 133K ±1% | 10000 |SZRCD|
| UNI-ROYAL(厚声) | 0402WGF1001TCE | 0402| 1K ±1% | 10000 |SZRCD|
| UNI-ROYAL(厚声) | 0402WGJ0511TCE | 0402| 510R ±1% | 10000 |SZRCD|Value|
| UNI-ROYAL(厚声) | 0402WGF2000TCE | 0402| 200R ±1% | 10000 |SZRCD|
| UNI-ROYAL(厚声) | 0402WGF220JTCE | 0402| 22R ±1%| 10000 |SZRCD|
| UNI-ROYAL(厚声) | 0402WGF3300TCE | 0402| 330R ±1% | 10000 |SZRCD|
| UNI-ROYAL(厚声) | 0402WGF3302TCE | 0402| 33K ±1%| 10000 |SZRCD|
| UNI-ROYAL(厚声) | 0402WGF1003TCE | 0402| 5.1K ±1% | 10000 |SZRCD|
| UNI-ROYAL(厚声) | 4D02WGJ0104TCE | 0402x4| 100K ±5% | 10000 |SZRCD|
| UNI-ROYAL(厚声) | 4D02WGJ0103TCE | 0402x4| 10K ±5%| 10000 |SZRCD|
| UNI-ROYAL(厚声) | 4D02WGJ0105TCE | 0402x4| 1M ±5% | 10000 |SZRCD|
| UNI-ROYAL(厚声) | 4D02WGJ0511TCE | 0402x4| 510R ±5%| 10000 |SZRCD|Value|
| UNI-ROYAL(厚声) | 4D02WGJ0331TCE | 0402x4| 330R ±5% | 10000 |SZRCD|
| UNI-ROYAL(厚声) | 0805W8J0330T5E | 0805| 33R ±5%| 5000|SZRCD|
| Ta-i Technology (大毅科技)| RLP25FEER200 | 2515| 0R2 ±1% 2W | 4000|SZRCD|
| FH(风华)  | CBW201209U300T | 0805| 1.5A Ferrite Bead| 4000|SZLCSC|Part, Manuf|
| CBI (创基)| 1N4148WT| SOD-523 | 100V 150mA | 3000|CBI (创基)|Package|
| CBI (创基)| BAS40-05T-7-F|SOT-523|Schottky Diode x 2| 3000|CBI (创基)|New|
| CBI (创基)| MMBT7002K | SOT-23|NFET| 3000|CBI (创基)|
| CBI (创基)| BC2301(2.8A) | SOT-523|PFET| 3000|CBI (创基)|Part, Package, Manuf|
| CBI (创基)| MMDT3906| SOT-363/SC-70-6 |Dual PNP| 3000|CBI (创基)|
| DIODES(美台)| BCM857| SOT-363/SC-70-6 |Dual PNP matched pair| 3000|SZLCSC|
| YXC (扬兴晶振) | X322512MSB4SI| 3225| 12MHz ±10ppm 20pF| 3000|Navia|
| MICRONE(南京微盟) | ME6211A33PG-N | SOT-89-3|3.3V VREG| 1000|Navia|
| DIODES(美台)| AP2127K-ADJTRG1| SOT-23-5|0.8V-5.5V 400mA VREG| 3000|Navia|
| Gainsil(聚洵) | LMV321 | SOT-23-5|R2R op-amp| 3000|Gainsil(聚洵)|Part, Footprint, Manuf|
| Gainsil(聚洵) | LMV321A (GS321A) | SOT-23-5|R2R op-amp A grade| 3000|Gainsil(聚洵)|Part, Footprint, Manuf|
| Gainsil(聚洵) | LMV324 (GS324MT)| TSSOP-14 |R2R op-amp x 4| 3000|Gainsil(聚洵)|New|
| Gainsil(聚洵) | LMV331 (GSV331) | SOT-23-5|Comparator| 3000|Gainsil(聚洵)|Part, Footprint, Manuf|
| Raspberry Pi| RP2040| QFN-56|Microcontroller|500|SZLCSC|
| Winbond | W25Q128JVSIQ| SOP-8 |128Mbit Flash|2000|SZLCSC|
| Micron | MT29F1G01ABAFDWB-IT:F|UPDFN-8|1Gbit NAND flash|4000|SZLCSC|New|
| I-CORE(中微爱芯) | AIP74HC595TA | TSSOP-16|Shift register| 2500|DXZH|Manuf|
| I-CORE(中微爱芯) | AIP74HCT245TA| TSSOP-20|Level shifter|2500|DXZH|Manuf|
| I-CORE(中微爱芯) | CD4067| TSSOP-24|16 channel analog mux| 2500|DXZH|Manuf, Part|
| I-CORE(中微爱芯) | AIP74LVC1T45| SOT-363/SC-70-6 |Buffer| 3000|DXZH|Manuf|
| CGL LED | SK6812-mini-e | |LED down facing|2000|CGL LED|
| CGL LED | SK6812-side-a_b | |LED side facing|2000|CGL LED|
| SZHTC | QT200H1201| |320x240 Display| |SZHTC|
| KAIDI |TJC8-10AW|1x10 P2.54mm horizontal male| main IO connector **with silkscreen**|1000|KAIDI|Added pinout silkscreen|
| SZWG |1x03 P2.54mm vertical female milled, low profile|1x03 P2.54|Programming connector| |SZWG|
| SZYC | SH 1.0-9P WT|"SH" 1x09 P1.00mm horizontal male|AUX connector|Tube|SZYC|
| SHOU HAN(首韩) | TYPE-C-31-M-12| |USB C 16P|1000|SHOU HAN(首韩)|
| SHOU HAN(首韩) | TS3425BA 098 2.5H 250gf|4.2x3.4x2.5mm|4x3x2.5H button 250gf|3000|SHOU HAN(首韩)|
| SHOU HAN(首韩) | TS3315A 250gf 025 |3.3x3.3x1.5mm|3x3x2.5H button 250gf|4000|SHOU HAN(首韩)|
-->

- Manuf = Change of part manufacturer (may or may not be drop in replacement)
- Package = Change of part size
- Part = Change of part number that requires FCC recertification
- Footprint = Part required a PCB footprint change
- Value = Value of part changed/new part value on this BOM revision
- New = New component in this revision

## Get a Bus Pirate
 
{{% readfile "/_common/_footer/_footer-get.md" %}}