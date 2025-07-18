# Battery-Charger-Circuit-PCB-Design
A PCB design for a battery charging circuit using scr and zener diode

#5V regulated power supply
this project integrates a SCR to regulate the AC source to a DC to charger electronic gadgets or power other modules like esp, uno, etc

#Features and working
1. stepped-down input through a transformer of rated voltage and current as per the circuit requirements through screw terminal connectors.
2. use of full wave rectifier with smoothening filters
3. a triggered SCR for safe regulation of power by its gate current
4. 5.1V zener diode to give a stable voltage output
5. TIP122 power transistor to amplify current to provide stable power to any gadget.
6. output via USB A port

#Components
1. terminal screw connector
2. diodes(1N4007)
3. 5.1V Zener diode
4. TYN612 SCR
5. TIP122
6. 100u polarised capacitor
7. gate resistor (500 ohms)
8. USB A port

#Designed using KiCAD
