# Digital-to-Analog-Converters
This Repo contains Full-Custom Designs for various DACs. Design and Simulation done using Cadence Virtuoso. Cadence Virtuoso is an industry-standard tool for designing and simulating integrated circuits, and particularly popular for custom design and analysis in MOS technologies.

## Table of Contents

- [Introduction](#introduction)
- [Designs](#designs)
- [Opamp Applications](#opamp-applications)

## Introduction

Digital-to-Analog Converters (DACs) are fundamental components in electronic systems, responsible for converting digital signals into analog signals. This repository showcases full-custom designs implemented using Cadence Virtuoso.

## Designs
### All the design starts with a basic block - Two Stage OPAMP
A Two Stage OPAMP consists of three parts - A differential Amplifier, Voltage Amplifier and a Output Amplifier.

![amp](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/Picture.png)

The Schematic is given as - 

![2stageopamp](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/opamp.png)

### Inverter

![inverter](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/inverter.png)

### Logic gates
2 Input NAND Gate 

![2innand](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/2_in_nand.png)

2 Input NOR Gate 

![2innor](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/2_in_nor.png)

2 Input AND Gate 

![2inand](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/2_in_and.png)

2 Input OR Gate 

![2inor](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/2_in_or.png)

3 Input AND Gate 

![3inand](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/3_in_and.png)

3 Input OR Gate 

![3inor](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/3_in_or.png)

## OPAMP Applications
OPAMP can act as 
- Buffer (Non-Inverting Unity Gain OPAMP)

  ![buffer_sch](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/buffer_sch.png)

  Buffer with Vin = 900mV +50mV/-50mV
  
  ![buffer](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/buffer.png)
 
  ![buffer_tb](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/buffer_tb.png)
 
- Non-Inverting Amplifier

  ![non_inv_amp_sch](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/non_inverting_amp_sch.png)

  Non-inverting Amp with Vin = 900mV +50mV/-50mV, Rf = 10k, R1 = 1k

  ![non_inverting_amp](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/non_inverting_amp.png)
 
  ![non_Inverting_amp_tb](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/non_inverting_amp_tb.png)
 
- Inverting Amplifier

  Inverting Amplifiers are the same except Vin+ and Vin- are switched, as the Figure below shows

  ![inverting_amp](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/inverting_amp_sch.png)
  
- Summing Amplifier

  ![Summingamp](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/summming_amp.png)

  Non-inverting Amp with V1 = V2 = 900mV, Rf/R1 = 10

  ![summingamp_tb](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/summming_amp.png)
