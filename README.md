# LoRaWan-Gateway-in-a-Tube
This short "tutorial" visualize the housing of an IMST iC880A - LoRaWAN Concentrator 868MHz together with a RaspberyPi
The power is delivered by PoE and a step-down booster (12V -> 5V)

The tube is made of polypropylen and could be found at various stores. (HT-Tube DN70)
It is fixed at the balcony with clamps, attached with each two "Fixation_Clamps"

Many thanks to Hanspeter for his support during design, laser cutting of the carrier board (http://www.funlab.ch) and preparing the clamps
and @ local.ch for sponsoring the LoRaWan Concentrator and the RaspberryPi




# BOM:
IMST iC880A SPI with 3dB antenna, connected via ufl to SMA cable

Raspberry Pi with (at least) 4GB SDcard configured as in https://github.com/ttn-zh/ic880a-gateway

PoE Injector (Wall plug version) EU Power Over Ethernet AC/DC POE Adapter 48V 0.5A Injector Support IEEE802.3AF

PoE Splitter ( PoE -> 12Volt)  Power Over Ethernet POE Splitter 10/100mbps 12V 2A POE Adapter

                               an other tested splitter (xV->5V) delivered only 4.7V   [:(]

                               Voltage Converter (xV -> 5Volt) preferable an adjustable one, set to 5.1Volt 

                               adj: LM317 DC-DC Linear Converter Buck Step Down Module

                               fix: Step Down Converter Buck Module DC 9V-40V to 5V 4Port USB (gives 4.8V!)


PP-Tube (75 x 350mm) with cover  or 75 x 500mm and cut on the desired length

Tube attachement:  (depending where you mount the tube)
- 2 x Clamps
- 4 x Fixation Clamps (see drawing)
- 4 x 8x70mm screws   (outer drillings)
- 4 x 8mm locknuts or self locking screws
- 1 x 10x90mm screw   (center drilling)
- 1 x 10mm nut
- 1 x 10mm screw lock or self locking screws


Mounting Plate (3mm Acrylic Glass laser cuttable!, see drawing)

microUSB with 90° Elbow cable

Ethernet cable : 10m flat PoE Plug to splitter , 2m router to PoE Plug

some cable tie

                              