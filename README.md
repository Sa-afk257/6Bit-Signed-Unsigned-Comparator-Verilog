# 6-Bit Signed and Unsigned Comparator System

## Overview

This project implements a complete 6-bit comparator system in Verilog HDL capable of performing both signed and unsigned comparisons.

The design combines structural and behavioral modeling approaches and includes reusable digital components such as multiplexers, comparators, two's complement circuits, and flip-flops.

## Main Features

- 6-bit Unsigned Comparator
- 6-bit Signed Comparator
- Structural Design Implementation
- Behavioral Design Implementation
- Two's Complement Conversion
- Multiplexer-Based Mode Selection
- D Flip-Flop Registers
- Timing Analysis and Glitch Handling
- Simulation and Verification

## Implemented Modules

### Comparator Modules
- Comparator_1bit
- Comparator_unsigned
- Comparator_signed
- General_Comparator

### Supporting Modules
- Mux
- Twos_complement_for_signed
- DFlipFlop
- FlipFlop_13bit
- FlipFlop_3bit

### System Modules
- system
- behavioral_System
- TestBench_System

## Design Methodology

The system compares two 6-bit inputs (A and B) and generates:

- EQ (Equal)
- GT (Greater Than)
- LT (Less Than)

A multiplexer selects between signed and unsigned comparison modes using a control signal.

## Timing Analysis

To reduce glitches caused by gate delays:

- Maximum latency = 70 ns
- Minimum clock period = 70 ns
- Maximum clock frequency = 1/70

## Verification

The design was verified using:

- Structural Simulation
- Behavioral Simulation
- Testbench Validation
- Error Verification Cases

Simulation results demonstrated correct operation for both comparator implementations.

## Tools Used

- Verilog HDL
- ModelSim / Simulation Tools
- Digital Logic Design
- Structural Modeling
- Behavioral Modeling

## Author

Sara Al Souqi

Birzeit University
