# Launch Control System
**In Short:** 	Created a chemical rocket motor launch control box with a voltage and continuity check, as well as a complete key locked arming and safety system.

## The Process:
### Research:
I started the project by researching how these controllers work.
For a model rocket to launch the igniter must burn inside to start the reaction. This igniter works by receiving a high voltage which overheats it and causes it to burn. If the voltage is too low, the electricity just passes through and it can work in a circuit. This is helpful for ensuring that there is "continuity" in the circuit. To take advantage of this, you need a resistor before the igniter so that it does not get the full voltage from the batteries. Since LEDs naturally have resistance, it is helpful to use them as they display light if circuit continuity exists. Electricity uses the path of least resistance and so you can have an alternative connection which bypasses the light that is button activated, when that happens, nothing resists the voltage of the battery and the Igniter receives the voltage needed to melt.

![Simple Rocket Launch Controller](https://www.robotroom.com/Launch-Controller/Schematic-of-a-simple-rocket-launch-controller.gif)
### Design:
For my design I wanted to have a system with a keyslot so that any accidental launch by somebody without the key is impossible. In addition,  I wanted to have 3 arming switches and then finally a safety which must be held down to press the "big red button" to launch. Finally, to ensure that the proper voltage is being used, I wanted to have an analog voltmeter to be observable during launch.

To create all of this,  I started by making a 3D printable panel in the CAD software onshape.

additnally i had to create a plan for the circuit, I made this below:

<img src="../assets/images/IMG_7324.JPEG" alt="Circuit Diagram"/>

<video controls>
  <source src="../assets/images/IMG_7561.MP4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<embed src="../documents/Bo_Gardner_Quantum_Radar.pdf" width="800px" height="2100px" />

    
