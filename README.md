# DB25CHEP-TAG
Cheap DB25 Parallel Port JTAG Programmer for IDE-EXI, USB Gecko and other XC95XX CPLD projects

Used on Xilinx Webpack ISE software suite to program the CPLD, I use version 13.3 in windows XP but it should work with any version that still supports Parallel cable 3

When using with Xilinx Impact under cable options choose Parallel cable 3

USB-C is only to provide power to the 3.3V regulator for the programmer/CPLD, the R3 and R4 5.1kOhm Resistors can be left out if you'll only be using a USB-C to A cable, they're only necessary with a C to C cable.

A nice 6pin Clip makes it easier to program most CPLDs that have 2.54mm pin JTAG headers on the pcb boards

I use this 6P clip https://www.aliexpress.us/item/3256805030490716.html 

![ChepTag+Clip](https://github.com/user-attachments/assets/e05d7be3-22a1-4c8e-9a6a-8cde7eaf3279)

![ISE](https://github.com/user-attachments/assets/ac2cf885-70cd-414c-9815-aee2f93ea321)

# CHEP-TAG BOM

**U1:** <ins>AMS1117-3.3 SOT-223</ins>

DigiKey Part#: 5399-AMS1117-3.3SOT-223CT-ND

LCSC Part#: C426566

**C1, C2:** <ins>10uF Tantalum Capacitors, + on PCB indicates the Stripe anode side of the cap</ins>

Digikey Part#: 718-TMCMA1C106KTRFCT-ND

LCSC Part#: C4988312

**D1:** <ins>1206 Blue 5ma LED, Led Green side Cathode orientation Marked with a Dot on pcb.</ins>

Digikey Part#: 2007-BL-HB333Q-AV-TRBCT-ND

LCSC Part#: C434440

Aliexpress Link: 1206 Blue https://www.aliexpress.us/item/3256805993208379.html

**R1:** <ins>4.7Kohm 1206 Resistor</ins>

Digikey Part#: 311-4.70KFRCT-ND

LCSC Part#: C137262

**R2:** <ins>10Rohm 1206 Resistor</ins>

Digikey Part#: 311-10.0FRCT-ND

LCSC Part#: C108080

**R3, R4:** <ins>5.1Kohm 0402 Resistors, (only necessary if you want to use USB-C to C cables can be unpopulated if using USB-C to A)</ins>

Digikey Part#: 311-5.1KJRCT-ND

LCSC Part#: C105873

**J1:** <ins>DB25 Male Right Angle Connector</ins>

Digikey Part#: A32100-ND

LCSC Part#: C305948

A cheap option is this 25P Male from Aliexpress https://www.aliexpress.us/item/3256805300852948.html?

remove the screw posts, and solder the front metal faceplate through the post holes filling the holes with lots of solder to the metal rear threads on the back to keep it in place.

**J2:** <ins>2.54mm 01x02 Male Pinheader (can be unpopulated, used as external +5V supply input to board instead of USB-C)</ins>

Can be found on Amazon, Ebay, Aliexpress etc. in any length just snip off however much you need.

Example Aliexpress Link https://www.aliexpress.us/item/3256807383526945.html

**J3:** <ins>2.54mm 01x06 Male Pinheader (can use either vertical or right angle 2.54mm header depending on preference)</ins>

Can be found on Amazon, Ebay, Aliexpress etc. in any length just snip off however much you need. 

Example Aliexpress link https://www.aliexpress.us/item/3256807383526945.html

**J5:** <ins>USB-C Female Connector</ins>

Digikey Part#: 52-USB-CB16HTBTRCT-ND

LCSC Part#: C165948
