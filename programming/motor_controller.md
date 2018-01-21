---
layout: page
title: Motor Controller Test Usage
subtitle: How to use the Roboclaw motor controller
---

# Materials

* Power supply
* Motor Controller
* Potentiometer
* Motor

# Setup

Turn on the power supply without the motor connected. Turn the output voltage to 12 volts. On some of the power supplies in the clinic lab you have to enable the output before you can change the voltage. 

For the Agilent E3631A in the lab the procedure may be as follows:
1. Turn on the unit with the button in the bottom left
2. Select the +25V output, 2nd button from the left, top row
3. Make sure the motor controller is not connected to the power supply
3. Turn on the output, rightmost button, bottom row
4. Tune to 12V using the adjustment knob on the right of the unit. Use the arrows beneath the knob to select which digit you are changing.
5. Turn the output off to prepare for the next steps

There are 4 14 AWG wires connected to the motor controller. Two should be going to the center and two to the right hand side. The center wires are your power wires. With the power supply off, unscrew the + and COM connectors of the right hand set of connectors on the power supply. There should be a hole on the top of these connectors that a wire can be inserted into. Insert the red power wire into the + connector and the black power wire into the COM connector

DO NOT REVERSE THESE WIRES, IT WILL CAUSE PERMANENT DAMAGE

Make sure the potentiometer is connected to the motor controller. If it became disconnected, reconnect it to the pin header labeled S1 on the motor controller with the wire colors, from outside to inside, going Orange, Red, Brown. This potentiometer must be centered before powering on the motor controller. 

Now make sure the motor is securely connected to the motor controller. Wire polarity does not matter as much here. Make sure the motor itself is secured. It may be handy to place it in between the handles of some plyers so the torque does not throw it, along with everything else, off of the table. 

Ensure the potentiometer is centered.

# Running the Motor

Turn on the output of the power supply. If everything was done correctly, the motor should not be moving but some LEDs should light up on the motor controller. Now slowly turn the potentiometer, the motor should start to turn. Changing the direction that you turn the potentiometer should change the direction of the motor. Try not to do drastic direction changes, this could damage things. 

Note on the potentiometer: turning the knob counter clockwise will cause the motor to go faster than if it were turned clockwise. I think this is caused by the potentiometer being old and not being an even resistance. 