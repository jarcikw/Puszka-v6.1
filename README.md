# Puszka-v6.1
Wall module based on ESP8266 12S
**Dimensions 46mm x 46mm x 22mm**  

R1,R3,R4,R5,R6,R7,R9,R12,R13 - 4,7K SMD 0603 
R2,R8,R10,R11 - 10K SMD 0603 
R14,R15 - 360R/470 SMD 0603 (Depending on LED Color)
C1,C2,C3,C5,C6 - 100nF/50V SMD 0603  
C4,C7 - 100uf/6V - TANTAL 3216-18  
D1,D2 - LL4148 SMD
D3,D4 - LED SMD 0603  (Use any Color , only check value for R14,R15)
F1,F2 - Fuse 2410 (1A,2A depending on load ) (https://www.digikey.com/en/product-highlight/t/te-connectivity/2410-smt-fuses)  
Q1,Q2 - BC817 SMD  SOT-23
J2,J7 - ARK2  	 
J4 - goldpin 2,54mm
U1 - HLK-PM01 , TSP-05  (5V DC) 
U2 - MCP1825T-3302E/DC 
U3 - ESP-12S  
J1,J2,J5 - 3pin board connector with 2.0 mm raster (example - https://www.antenk.com/2-0mm-wire-to-board-connectors/57147398.html)
J6 - 4pin board connector with 2.0 mm raster (example - https://www.antenk.com/2-0mm-wire-to-board-connectors/57147398.html)
RV1 - Varistor 07D431K  
SW1 - microswitch 3x6x2.5mm  


K1,K2 - SONGLE SRD-05VDC-SL-C - 5V - 230VAC 10A
 
 
 
To enter programming mode short J4 with jumper and then reset(SW1 switch) board. LED diode ilustrate relays state

You can:
 - connect two switches/buttons to control Relays or any other purpose supported by used firmware
 - conenct DS18B20 sensor
 - connect any I2C device supported firmware
 - connect MODBUS Power meter with Tasmota
 
You should:
- solder wires where 230VAC is used (removed soldermask) wit higher current
