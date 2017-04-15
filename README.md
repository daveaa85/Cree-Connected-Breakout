# Cree-Connected-Breakout

Overview:
  This is an Eagle CAD project to make a power/interface PCB for the Cree Connected RF board. This facilitates usage of the low cost Cree LED to interface to other hardware. Open collector transistor drive allow drive of relays or drive of different voltage level H/W interfaces.
  
-- RF module description --
Inside the A19 Cree Connected LED is an add on PCB which implements the ZigBee radio function.
The PCB is attached to the main LED power supply with a 4 pin connector having a 2mm pitch.

---- RF Board connector pins --
Pin 1 - Gnd
Pin 2 - +3v
Pin 3 - PWM
Pin 4 - On, /Off

-- Features --
1) USB micro connector provides +5v supply
2) 3.3v/800mA regulator can supply external hardware via output connector
3) Cree RF board PWM and On/Off signals are buffered by open collector transistor drive
4) Solder pad selectable +5v/3.3v power supply output for external system use.

-- Parts list --
1) PCB - Interface
2) 0.1uf bypass cap - body size 1206, quantity = 2, C1, C2
3) MUN2212 pre-biased NPM transistor, quantity = 2, Q1, Q2
4) Low Dropout regulator, AP7363-33D-13 3.3v/1.5A , 3.3v, package SOT-23, U1
5) JST-PTH series 4 pin 2.0mm vertical connector J1
6) Cree Connected RF module - remove from Cree Connected LED.


