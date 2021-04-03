# Stepper-control-from-the-phone
This is an Arduino based project that was implemented at Gearbox in which I was a part of along side other collaborators. .

## Intoduction
The objective od the mini-project was to control a stepper motor remotely through a smartphone using the Blynk application.

## Components
1 ESP8266 NodeMCU,
[1 28BYJ-48 Stepper Motor](#28BYJ-48-stepper-motor),
[1 ULN2003 Driver Board](#ULN2003-Driver-Board),
1 Breadboard,
[1 Switching Power Supply Adapter](#Switching-Power-Supply-Adapter),
[1 LM2596 Step-down power module](#LM2596-Step-down-power-module),
Several jumper wires,
USB Cable

## Specifications
### 28BYJ-48 Stepper Motor
Rated voltage:	5 V,
Coil Resistance:	50Ω±7%,
Coil Type:	Unipolar,
Diameter – shaft:	(5.00 mm),
Gear reduction:	1/64, 
**Step angle** *[Half step mode (recommended): 0.0879° = 5.625°/64,
Full step mode: 0.176°]*,
**Steps per revolution**	*[Half step mode: 4096, 
Full step mode: 2048]*,
Number of phases:	4,

**Pin-out**

No | Wire Colour | Description
---|---|---
1 | Blue | Coil 4
2 | Pink | Coil 2
3 | Yellow | Coil 3
4 | Orange | Coil 1
5 | Red | +5V

### ULN2003 Driver Board
Supply Voltage: 5-12V DC,
Max Output Current: 0.5A (Single Output),
4-way LED indicator

**Pin-out**

ULN2003 Driver Board	| Connection
---|---
IN1|D1
IN2|D3
IN3|D2
IN4|D4

### Switching Power Supply Adapter
Input: AC 110V/220V,
Output: DC 12V 10A,
Output Power: 120W,
Frequency: 50/60Hz,
Over-voltage Protection: 115%-135%

**Pin-out**

Input: live, neutral, earth

Output: com, +V

### LM2596 Step-down power module
Input voltage :4V ~ 35V,
The output voltage : 1.23V ~ 30V,
Output Current :3A(Max),
Conversion efficiency: 92%(MAX),
Output ripple: <30mV,
Switching frequency: 150KHz,
Load Regulation: ± 0.5%,
Voltage Regulation: ± 0.5%

**Pin-out**

IN+, IN-, OUT+, OUT-

## Breadboard Layout
![breadboard layout](Fritzing/Stepper%20with%20Blynk_bb.jpg)
