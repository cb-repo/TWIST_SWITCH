# TWIST_SWITCH v1.0

<img src="/Switch.jpg" width="500">

The TWIST_SWITCH is a light-weight power switch: originally designed for combat robotics, but it's suitable for any application that requires a high-current vibration-resistance power switch. 

Designed and built in [Christchurch, New Zealand ](https://www.google.co.nz/maps/place/Christchurch+New+Zealand) by Connor Benton, visit [CB-Technology](https://www.cb-tech.co.nz/) for details.

## SPECIFICATIONS

- **Current:** See the Current Rating section below
- **Voltage Drop:** 0.5 mV *(at 12V, 20A)*
- **Dimensions:** 10x30x7 mm
- **Weight:** 2g *excluding wires*
- **Power and Mounting Screw:** M2

## Installation

1. Drill the holes as per the provided hole pattern: 
   *image*
2. Testfit the TWIST_SWITCH, checking for correct alignment and functionality prior to soldering wires.
3. Solder the battery wires to the mounting pads.
   - The positive wires should be soldered to the topside and the negative to the underside, labelled +BATT/VCC and GND respectively. 
   - It's not necessary to solder the negative wires to the switch as this is just a passthrough. The pads were provided to simplify cable management.
   - It's best practice to reduce the cable length between the switch and battery as much as possible, reducing shorting risk.
4. Mount the switch using the provided hardware.
   - The provided hardware allows for mounting onto pannels up to 3mm thick. Mounting to thicker pannels will require 
  
## Operation

###### Turning ON

1. Verify the power screw is in the OFF position
2. Connect the battery 
3. Using a 2mm Allan Key, tightening the power screw clockwise until it connects the pads below. 
   - It does not take much force to make a good connection. Only tighten to 0.4[Nm] (approximately finger tight)
   - If the screw seems stiff to turn, that is normal. The rearside spacer is undersized causing friction and reducing the risk of backout due to vibration.
5. Smash some bot! 

###### Turning OFF

1. Using a 2mm Allan Key, turn the power screw counter-clockwise.
   - It will only take ~1/4 turn to fully-disconnect the power.
   - Although, it is recommended to back the screw out at least a full turn.

## Current Rating

Keep in mind that the temperature and therefore current rating of the switch is **very** dependednt on the wires used (gauge, length, and insulation material). 
It is the responsibility of the user to choose the correct wires for their setup and to test that it stays within their desired operating temperature. 

As a guide, two tests have been conducted each with different wire gauges to illistrate the thermal characteristics of the switch.  
Note: All testing has been conducted at constant current, resulting in a higher temperature than pulse current as most combat robot applications will experience. 

###### 16 AWG Wire

 - **Wire Length:** 200mm
 - **Wire Gauge:** 16 AWG
 - **Voltage:** 12V
 - **Continuious Current Rating:** 10A 

<img src="/Temperature Curve.png" width="500">

###### 12 AWG Wire

 - **Wire Length:** 200mm
 - **Wire Gauge:** 12 AWG
 - **Voltage:** 12V
 - **Continuious Current Rating:** 25A 

<img src="/Temperature Curve.png" width="500">
