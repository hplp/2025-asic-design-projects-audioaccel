# Project_Template

## Team Name: 
AudioAccel

## Team Members:
-Maiva Ndjiakou
-Jazzmin Poitier

## Project Title:
AudioAccel

## Project Description:
Our goal is to design a custom ASIC that can accelerate FFT operations, offering a more optimized, energy-efficient, and faster alternative for analyzing audio signals in real-time applications such as sound analysis, noise reduction, or audio filtering.The problem we are addressing is the inefficiency and high power consumption of general-purpose processors and FPGAs in performing real-time audio signal processing tasks, specifically the Fast Fourier Transform (FFT).

## Key Objectives:
Objective 1: Design and implement an efficient FFT algorithm in Verilog/VHDL tailored for audio signal processing. Objective 2: Synthesize, verify, and optimize the ASIC design using industry-standard EDA tools such as DC Shell, FM Shell, and ICC2 Shell. Objective 3: Demonstrate real-time FFT processing on audio signals using simulation and visualization through DVE, ensuring both functional accuracy and performance targets are met.

## Technology Stack:
Hardware Platform: Microphone 
Software Tools:
•	Synopsys Design Compiler (DC Shell) – for RTL synthesis -Formal Verification (FM Shell) – for logic equivalence checking
•	IC Compiler II (ICC2 Shell) – for place-and-route and physical design
•	Verdi/DVE – for simulation and waveform analysis 
Programming Languages:
•	Verilog or VHDL for RTL design
•	TCL scripts for EDA automation
•	Python for Audio waveform generation and conversion tools pre and post processing

## Expected Outcomes:
•	A fully synthesized and verified FFT-based ASIC design capable of real-time audio signal processing.
•	Optimized performance in terms of speed, power, and area usage.
•	Functional simulation and verification results displayed via DVE.
•	Documentation and analysis of FFT performance improvements compared to general-purpose solutions.

## Tasks:
FFT Algorithm Design Implement FFT in Verilog/VHDL, focusing on modular and scalable architecture - Jazzmin RTL Synthesis Use DC Shell to synthesize and optimize design for area, power, and timing - Maiva Formal Verification Verify design correctness using FM Shell - Jazzmin Place-and-Route Complete physical design using ICC2 Shell - Maiva Simulation & Testing Integrate and test design using DVE; analyze simulation output - Jazzmin Documentation Record all procedures, results, and observations throughout the project - Jazzmin and Maiva

## Timeline:
Week 1 literature review, and basic FFT design in Verilog/VHDL - Completed Week 2 Synthesis with DC Shell and functional verification using FM Shell and Design optimization for speed, power, and area Week 3 -Place-and-route using ICC2 Shell and power/timing closure Week 4- Final simulation with DVE, testing on audio signals, documentation, and presentation prep
