# MIE366-Precision-Current-Sense-Amplifier-PCB

This project focuses on the design, build, and testing of a a high precision current sense amplifier PCB for accurate measurements of small currents in the presence of electrical noise. It needs to sense load current using a low-side 0.1 Ω sense resistor and convert it into a voltage signal suitable for a microcontroller ADC to read. As voltage across the sense resistor is very small (0-0.35 V for 0-3.5A respectively), the signal must be conditioned before it can be accurately read. The system integrates analog circuit design on LTSpice, PCB layout design on Eagle, and soldering and hardware documentation. The final system performs successfuly, achieving stable output current of 3.5A with minimal ripple.

<br><br>
Please look at the documents to see the PCB development process in the following order (Below gives a brief description of each skill demonstrated in the documentation):
<br><br>
**Part 1: MIE366_DesignAssignment1_Designing_the_circuit**: 
<br>
- Studied engineering specifications and researched different types of potential building-block circuits to find an optimal candidate design for the current sense amplifier.
- Designed and simulated our best two designs on LTSpice, calculating the total product gain, voltage sense, and voltage out against varying load currents from 0A - 3.5A. 
- Iterated based on best two design to create our final design and verified results to ensure it met the conditions

<br><br>
**Part 2: MIE366_DesignAssignment2_Creating_the_PCB**: 
- Simulated and tested different low-pass filters to achieve smooth roll-off and minimal phase distortion
- Selected components to optimize accuracy, stability, and noise performance
- Created full schematic and custom PCB Layout on Eagle
- Prepared board for fabrication with design rule checks and manufacturing files

<br><br>

**Part 3: MIE366_DesignAssignment3_Soldering_and_Verification**
- Assembled and soldered/desoldered components onto the printed PCB
- Diagnosed and repaired real hardware faults including cold solder joints, short circuits from solder bridges, damaged traces, and broken components
- Verified correct analog behavior by measuring unfiltered and filtered outputs, confirming linear voltage–current response and proper filter operation
- Validated that the PCB performed within expected component tolerances
 

<br><br>
**Part 4: MIE366_DesignAssignment4_Final_Testing**:
- Integrated the current-sense PCB into the full embedded power-supply system  
- Generated calibration curves demonstrating strong linearity (R² ≈ 0.9999) between sensed current and ADC output  
- Demonstrated fully functional operation with live firmware, LCD interface, and closed-loop control :contentReference[oaicite:1]{index=1}



<br><br>
This project was completed by Zurizadae Soto Maya and Zarah Mathew. 
