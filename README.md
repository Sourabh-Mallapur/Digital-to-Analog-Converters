# Digital-to-Analog-Converters
This Repo contains Full-Custom Designs for various DACs. Design and Simulation done using Cadence Virtuoso. Cadence Virtuoso is an industry-standard tool for designing and simulating integrated circuits, and particularly popular for custom design and analysis in MOS technologies.

## Table of Contents

- [Introduction](#introduction)
- [Designs](#designs)
- [Opamp Applications](#opamp-applications)
- [DAC Designs](#dac-designs)

## Introduction

Digital-to-Analog Converters (DACs) are fundamental components in electronic systems, responsible for converting digital signals into analog signals. This repository showcases full-custom designs implemented using Cadence Virtuoso.

## Designs
### The design starts with a basic block - Two Stage OPAMP
A Two Stage OPAMP consists of three parts - A differential Amplifier, Voltage Amplifier and a Output Amplifier.

![amp](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/Picture.png)

### The Schematic is given as - 

![2stageopamp](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/opamp.png)

### Inverter

![inverter](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/inverter.png)

## Logic gates
### 2 Input NAND Gate 

![2innand](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/2_in_nand.png)

### 2 Input NOR Gate 

![2innor](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/2_in_nor.png)

### 2 Input AND Gate 

![2inand](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/2_in_and.png)

### 2 Input OR Gate 

![2inor](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/2_in_or.png)

### 3 Input AND Gate 

![3inand](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/3_in_and.png)

### 3 Input OR Gate 

![3inor](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/3_in_or.png)

## OPAMP Applications
### OPAMP can act as 
- ## Buffer (Non-Inverting Unity Gain OPAMP)

  ![buffer_sch](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/buffer_sch.png)

  ### Buffer with Vin = 900mV +50mV/-50mV
  
  ![buffer](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/buffer.png)
 
  ![buffer_tb](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/buffer_tb.png)
 
- ## Non-Inverting Amplifier

  ![non_inv_amp_sch](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/non_inverting_amp_sch.png)

  ### Non-inverting Amp with Vin = 900mV +50mV/-50mV, Rf = 10k, R1 = 1k

  ![non_inverting_amp](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/non_inverting_amp.png)
 
  ![non_Inverting_amp_tb](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/non_inverting_amp_tb.png)
 
- ## Inverting Amplifier

  ### Inverting Amplifiers are the same except Vin+ and Vin- are switched, as the Figure below shows

  ![inverting_amp](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/inverting_amp_sch.png)
  
- ## Summing Amplifier

  ![Summingamp](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/summing_amp.png)

  ### Summing Amp with V1 = V2 = 900mV, Rf/R1 = 10

  ![summingamp_tb](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/summing_amp_tb.png)

- ## Comparator
  
 ![comparator](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/comparator.png)

## Other Importnant blocks for DAC Design
- ### 2:1 mux

  ![21mux](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/2_1_mux.png)

- ### 4:1 mux

  ![41mux](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/4_1_mux.png)

- Transmission gate
  
  ![txgate](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/tx_gate.png)

  ### Simulation
  ![txgatetb](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/tx_gate_tb.png)

  ![txgatetbres](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/tx_gate_tb_res.png)

- ### 3 to 8 Decoder

  ![38decoder](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/3_8_decoder.png)

  ### Simulation
  ![38decodertb](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/3_8_decoder_tb.png)

  ![decodertb](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/decoder_tb.png)

- ### DFF

  ![dff](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/dff.png)

- ### XOR and XNOR

  #### These blocks are avaliable in the gpdk_090nm libraries

## DAC Designs

### Resistor String DAC (8 bit)

![resstrin6dacgsch](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/res_string_dac_sch.png)

![resstrings](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/res_string_dac.png)

### Simulation
![resstringtbsch](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/res_string_dac_tb_sch.png)

![resstringtb](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/res_string_dac_tb.png)

### R-2R DAC (8 bit)

![R2Rsch](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/r2r_sch.png)

![R2R](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/r2rdac.png)

### Simulation
![R2R_tb](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/r2rdac_tb.png)

### Charge Scaling DAC (8 bit)

![chargescallingdacsch](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/charge_scaling_dac_sch.png)

![chargescallingdac](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/charge_scaling_dac.png)

### Simulation
![chargescalingdac_tb](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/charge_scaling_dac_tb.png)

### Binary Weighted SR DAC

![binweightedrsdacsch](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/bin_weighted_sr_dac.png)

![binweightedrsdac](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/binwsr_dac.png)

### Simulation
![binweightedrsdactb](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/binwsr_dac_tb.png)

![binweightedrsdactbres](https://github.com/Sourabh-Mallapur/Digital-to-Analog-Converters/blob/main/assests/binw_sr_dac_tb.png)
