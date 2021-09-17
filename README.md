# Audio-Power-Amplifier-PCB
Given a  schematic for an audio power amplifier, I simulated the circuit in PSPICE, built the circuit on a breadboard, and finally created a PCB with soldered components.

## Circuit Schematic
<img src =Schematics/circuit_schematic.jpg height=500>
The given circuit consists of 3 Bipolar Junction Transistors, 2 Diodes, a 9V DC power supply, and numerous resistors and capacitors. The goal of the circuit is to amplify an input signal, allowing it be played on an attached speaker, while minimizing noise.

## PSPICE Simulations
I first built the circuit using PSPICE, an application that is used to simulate and test circuits. By performing [transient analyses and frequency sweeps](<PSPICE Simulation/graphs_pspice.xlsx>) in PSPICE, I verified that the circuit produced a smooth output over the desired frequency range.

## Breadboard
I then constructed the circuit on a breadboard. Using a digital multimeter, I verified that the measured voltages and currents matched those produced in the PSPICE simulation.

<img src=Breadboard/breadboard.jpg height=500>

## PCB Design
Next I used EAGLE software to build a PCB design of the circuit. Components were placed to minimize the size of the board and the number of drill holes needed.

<img src=PCB/top_side.png height=300>
<img src=PCB/bottom_side.png height=300>
After having the design manufactured, I soldered all components to the board. Finally, I tested the finished product by having it play an audio file, and verified that the circuit worked as designed!
<img src=PCB/PCB.JPG height=500>
