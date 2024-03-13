# Golden-Arduino
## Aim:
The project targets the creation of a standalone 4-layer instrument droid(Arduino base) focusing on:

- Utilizing a 328 microcontroller and data acquisition system.
- Prioritizing non-compatibility with Arduino Uno R3.
- Ensuring access to essential pins for bootloading.
- Emphasizing proficiency in 4-layer design.
- Measuring and characterizing the output impedance of diverse voltage sources, including dynamic Thevenin resistance.
- Providing thorough documentation focusing on design, assembly, testing, and code development.

## POR (Plan of Record):
The Plan of Record (POR) outlines various features and requirements of the project, including:

- Incorporating a power plug for an external 5V AC to DC charger.
- Implementing a voltage regulator for efficient operation of components.
- Including USB mini support for programming and powering the board.
- Integrating a power selector switch to choose between USB and external power supply.
- Utilizing a Low Drop-Out (LDO) regulator for stable 3.3V.
- Installing indicator LEDs for visual confirmation of power status.
- Implementing a power isolator switch and reset switch.
- Ensuring compatibility for bootloading and programming.
- Developing functionality to measure in-rush current and protect against static voltage damage.
- Providing extra headers for convenient ground connections.
- Planning test points for critical signals.
- Placing decoupling capacitors and implementing a copper poured ground plane.

## Risk Reduction Steps:
To mitigate risks associated with the project, various steps have been taken, including:

- Thorough research and validation of components.
- Prototyping and simulating critical sections of the board design.
- Performing comprehensive analysis of the board layout.
- Conducting in-depth testing of each feature.
- Implementing feedback mechanisms and standardizing signal lines.

## Demonstration Goals:
The demonstration goals include bootloading the Atmega 328, maintaining compatibility with standard header pin footprints, achieving noise levels lower than commercial boards, and more.

## Expectations of "Work":
Expectations include reliable power-up, efficient voltage regulation, accurate current measurement, smooth bootloading processes, and effective noise reduction measures.

## Significant Parts Used:
Significant parts used in the project include ATMEGA328, LDO (AMS1117), CH340g, Crystal Oscillators, DAC MCP4725, ADC ADS111x, and OP-AMP MCP6002.

##  Design:
Various visuals and diagrams are provided to illustrate the project's design, layout, and assembly process.
![Schematic](https://github.com/Shri2401/Golden-Arduino/blob/main/pictures/Screenshot%202024-03-13%20161227.png)
![Bare Board](https://github.com/Shri2401/Golden-Arduino/blob/main/pictures/Golden_Arduino_Schematic.jpg)
![PCB](https://github.com/Shri2401/Golden-Arduino/blob/main/pictures/Golden_Arduino.jpg)

## Bring-Up Process Summary:
The bring-up process involved short testing of the bare board, precise component placement, soldering, testing, bootloading, and code execution.

## Learning Outcomes
Through the process of developing the circuit design and implementing strategic routing techniques, several valuable learning outcomes have been achieved:

1. Thorough Circuit Design: By deeply understanding and incorporating insights from available references, this project has emphasized the importance of meticulous circuit design. Prioritizing best design practices and optimizing layout have been essential steps in ensuring precision and reliability.

2. Signal Integrity Management: Employing strategic routing techniques and grounding practices has enabled the mitigation of potential signal integrity issues. Understanding the impact of layout and routing on signal quality has been crucial in optimizing performance.

3. Noise Resistance Improvement: Implementing best routing techniques and measures has led to better noise resistance compared to previous designs. By carefully considering the placement of components and utilizing techniques such as ferrite beads, noise interference has been minimized, resulting in improved overall performance.

4. Anticipating Expected Outcomes: Learning to anticipate the expected outcome based on design decisions and implementation choices has been a central aspect of this project. Understanding the role of each component and technique in achieving specific project goals has been essential in maintaining a systematic approach to circuit design and testing.

In conclusion, by incorporating these best practices and maintaining a systematic approach to circuit design and testing, the reliability and success of future projects can be greatly enhanced. Learning from both successes and challenges encountered during this project will contribute to further improvements and best implementations in future endeavors.
