# Ex No: 03 - Design & Implementation of 2:1 MUX using Synopsys EDA Tools

## Aim

The aim is to design and simulate a 2:1 multiplexer (MUX) using Synopsys EDA tools, ensuring accurate logic operation through waveform analysis and verification.

## Tools Required

### Synopsys EDA Suite
- Synopsys Custom Compiler – For CMOS schematic design.
- Synopsys PrimeWave Design Environment – For simulation setup and waveform analysis.
- Synopsys PrimeSim HSPICE / PrimeSim – For circuit simulation and analysis.

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**
- Linux-based operating system compatible with the installed Synopsys tools.

## Procedure:
### 1. Launch Synopsys Custom Compiler Environment :
     Open Synopsys Custom Compiler and set up the working library.
     Create a new design library and associate it with the appropriate CMOS technology PDK.
     Create a new schematic cell view for the CMOS circuit design.
### 2. Schematic Design:
    Launch Synopsys Custom Compiler and create a new design library associated with the appropriate CMOS technology PDK.
    Create a new schematic cell view for the required CMOS complex gate.
    Select the required NMOS and PMOS transistors from the technology library based on the given Boolean expression.
    Connect the NMOS and PMOS transistors appropriately to implement the required pull-down and pull-up networks.
    Connect the transistor gate terminals to the corresponding input signals.
    Connect the supply terminals to VDD and GND, ensuring that the bulk terminals are connected to the appropriate supply potentials.
    Connect DC voltage sources (VDC) to provide the required supply voltage and pulse voltage sources (VPULSE) to apply the input signals.
    Connect the output terminal to the common node of the pull-up and pull-down networks.
### 3. Simulation:
    Check the schematic for errors and verify the electrical connections.
    Create a testbench for the CMOS design.
    Launch Synopsys PrimeWave Design Environment.
    Select the appropriate simulator, such as PrimeSim HSPICE.
    Configure transient analysis to study the time-domain response.
    Set the simulation parameters, including supply voltage, input pulse period, rise time, fall time, and simulation stop time.
    Run the simulation and verify the simulation results.

## Circuit Diagram

### 1. 2:1 MUX USING CMOS
<img width="734" height="589" alt="Screenshot 2025-03-10 101825" src="https://github.com/user-attachments/assets/09a499d0-4d83-4955-97e8-56e12a6a8f4d" />



### 2. Schematic of 2:1 MUX

![alt text](<WhatsApp Image 2026-10-29 at 3.12.55 PM-1.jpeg>)

### 3. Transient Response Setup

![alt text](<WhatsApp Image 2026-10-29 at 3.19.17 PM-1.jpeg>)

## Output

### 1. Transient Analysis Output

![alt text](<WhatsApp Image 2026-10-29 at 3.11.22 PM-1.jpeg>)

## Results
1. Successfully designed the 2:1 MUX schematic using Synopsys EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
