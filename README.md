# Project_Template

## Team Name: 
AudioAccel

## Team Members:
-Maiva Ndjiakou
-Jazzmin Poitier

## Project Title:
AudioAccel

## Project Description:
The goal of this project is to design a custom ASIC that accelerates audio signal processing using a Cascaded Integrator-Comb (CIC) filter, targeting efficient sample rate conversion for real-time audio applications. The main problem we are addressing is the inefficiency of traditional signal processing pipelines, especially in devices like wireless audio systems, hearing aids, and professional audio equipment, which require efficient downsampling and upsampling. By implementing the CIC filter directly in hardware, we aim to reduce power consumption and latency, improving both performance and energy efficiency for audio processing tasks.

## Key Objectives:
•	Objective 1: Implement a highly efficient CIC filter in Verilog/VHDL for real-time audio processing (decimation and interpolation).
•	Objective 2: Synthesize and optimize the ASIC design using industry-standard EDA tools (DC Shell, ICC2 Shell).
•	Objective 3: Verify functional correctness and optimize performance for area, speed, and power consumption using formal verification and simulation tools.

## Technology Stack:
Hardware Platform: ASIC design targeting integration with audio front-end components (e.g., microphones, ADCs) for real-time processing.
•	Software Tools:
Synopsys Design Compiler (DC Shell): For RTL synthesis, logic synthesis, and optimization.
IC Compiler II (ICC2 Shell): For place-and-route and physical design.
Formal Verification (FM Shell): For functional verification and logic equivalence checking.
Verdi/DVE: For simulation and waveform analysis.
•	Programming Languages:
Verilog/VHDL: For RTL design of the CIC filter.
TCL scripts: For EDA automation (e.g., running synthesis, simulation).


## Expected Outcomes:
•	CIC-based ASIC Design capable of efficient sample rate conversion for real-time audio processing.
•	Optimized Performance: Significant improvements in speed, power, and area usage compared to software-based or FPGA implementations.
•	Functional Verification: Successful simulation and verification with DVE, ensuring the CIC filter performs as expected in various audio signal scenarios.
•	Documentation & Analysis: Comprehensive report covering design, optimizations, performance metrics, and comparisons with traditional software-based or FPGA solutions


## Tasks:
RTL Design Implementation
•	Task: Implement the CIC filter design in Verilog/VHDL, focusing on the structure and modularity to make it scalable for different audio sample rates.
•	Lead: Jazzmin
3. RTL Synthesis
•	Task: Use DC Shell for RTL synthesis, focusing on optimizing the design for power, area, and timing.
•	Lead: Maiva
4. Formal Verification
•	Task: Perform functional verification using FM Shell to ensure the design works as expected for different audio sample rate inputs.
•	Lead: Jazzmin
5. Place-and-Route
•	Task: Use ICC2 Shell to perform physical design, focusing on power and timing closure.
•	Lead: Maiva
6. Simulation & Testing
•	Task: Integrate the design and test it with audio signal simulations. Use Verdi/DVE for analyzing waveforms and ensuring the design meets performance targets.
•	Lead: Jazzmin
7. Documentation & Reporting
•	Task: Document the entire design process, results, optimizations, and performance analysis. Prepare the final report and presentation.
•	Lead: Jazzmin & Maiva


## Timeline:
Week 1 literature review, and basic CIC design in Verilog/VHDL - Completed Week 2 Synthesis with DC Shell and functional verification using FM Shell and Design optimization for speed, power, and area Week 3 -Place-and-route using ICC2 Shell and power/timing analysis Week 4- Final simulation with DVE, testing on audio signals, documentation, and presentation prep
