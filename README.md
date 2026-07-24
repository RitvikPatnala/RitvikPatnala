## Hi, I'm Ritvik Patnala 👋

ECE student at the University of Illinois Urbana-Champaign (BS '26, MEng '27), focused on digital design and computer architecture. I've built projects across the hardware stack — custom PCBs, embedded firmware, and FPGA systems — and what I enjoy most is RTL design: currently building a pipelined RISC-V CPU core in SystemVerilog.

## 🔧 Featured Projects

### RV32I RISC-V CPU Core 🚧 in progress
Single-cycle RV32I processor core in SystemVerilog — register file, ALU, and instruction/data memory — verified with self-checking testbenches covering same-cycle read/write hazards, x0 semantics, and signed/unsigned comparison boundaries. Now extending it into a 5-stage pipeline with data forwarding, load-use stall handling, and branch flushing. 

**Tools**: SystemVerilog, Icarus Verilog (Simulation), Surfer (Waveform Viewing)

### [FPGA Tetris System](https://github.com/RitvikPatnala/fpga-tetris)
Complete hardware gaming system on a Xilinx FPGA: grid-based game logic in SystemVerilog, ROM/palette VGA rendering pipeline with HDMI (TMDS) output, and USB keyboard input via a MAX3421E over SPI, bridged to a MicroBlaze soft core through AXI4-Lite memory-mapped registers. RTL verified with testbenches and a logic analyzer to isolate SPI protocol faults. ~17K LUTs / 58.5 BRAM. 

**Tools**: SystemVerilog, Vivado, Vitis, MicroBlaze, AXI4-Lite

### [Auto Guitar Tuner](https://github.com/RitvikPatnala/auto-guitar-tuner)
Handheld device that detects a guitar string's pitch and physically tunes the peg. Custom ESP32-S3 PCB (schematic → routed layout in KiCAD) with dual buck converters, piezo + LM386 analog front end, and RC anti-aliasing filtering. Firmware implements time-domain autocorrelation pitch detection, chosen over FFT for harmonic rejection and ~22 ms latency, with Hann windowing, interpolation, and PID servo control. Tuned to ±12 cents. All rails verified within ±1%. 

**Tools**: KiCAD, LTSpice, C (Programming Language), DSP, SPI/I2C/PWM

## 💼 Experience Highlights

*Code from industry work is proprietary: descriptions only. Happy to discuss the technical details in depth.*

### KPIT Technologies: Middleware Intern - AUTOSAR Configuration and AI Automation 
Configured and validated AUTOSAR Basic Software modules for automotive ECUs, managing network interfaces like CAN and LIN protocols while coordinating in cross-functional teams with software, systems, and validation engineers. Prototyped an AI-driven framework by engineering LLM agents to parse vector and relational databases and dynamically update ECU configuration files based on natural language user queries. 

### KPIT Technologies: Middleware Intern -  Test Script Automation
Developed a Python-based scripting tool to automate translation of test cases into executable CMM scripts and generated test reports, supporting ECU verification and validation workflows and improving test execution efficiency by 20%. Rolled out tools to ~30 engineers across validation teams via a week-long training program with written documentation.

## 📁 More Projects

**[Automated DJ System](https://github.com/RitvikPatnala/Automated-DJ-System)** — Android app that automatically mixes two songs like a DJ. Detecting beats, structural sections, and energy levels via digital signal processing to choose musically coherent transition points, then crossfading and tempo-matching in real time. Hybrid architecture: Java/Android UI with all real-time DSP, and prototyping done on Python. 

**Tools**: C++, Java/Android, JNI, Python, DSP (STFT, mel spectrograms, autocorrelation)

**GPU-Accelerated CNN Inference** — CUDA C++ forward pass in MXNet with
  shared-memory tiling, cuBLAS SGEMM, and Tensor Core (WMMA) integration.
  Profiled with Nsight to cut inference latency 19%. *(Code
  available on request.)*

**Tools**: CUDA C++, MXNet, cuBLAS, Tensor Cores (WMMA), NVIDIA Nsight Systems/Compute
  
**LDO Regulator** — Two-stage LDO voltage regulator designed in Cadence Virtuoso on a 0.18µm CMOS process, regulating a 1.8V ±10% supply down to a 1.0–1.4V output across a 0.1–10 mA load range. Phase margin ≥60°  at full load, with DC load/line regulation and PSR characterized in simulation across the load current range.

**Tools**: Cadence Virtuoso, Analog IC design

## 🛠️ Skills
**Digital Design & RTL:** SystemVerilog, VHDL, RTL design, digital verification (self-checking testbenches), FSM design, pipelining & hazard resolution

**Computer Architecture:** RISC-V (RV32I), pipelined microarchitecture (forwarding, hazard detection, branch resolution), MicroBlaze soft-core integration, AXI/AXI4-Lite

**FPGA & Simulation Tools:** Xilinx Vivado, Vitis, Altera Quartus, Icarus Verilog, Surfer (waveform viewing)

**Embedded & PCB Design:** KiCAD, Altium Designer, LTSpice, ESP32/MCU firmware (C), PCB bring-up & validation

**Programming:** C/C++, Python, MATLAB, CUDA

**Protocols & Lab Equipment:** SPI, I2C, UART, AXI, CAN, LIN | Oscilloscope, logic analyzer, function generator, DMM, bench power supply

## 📫 Reach Me

[LinkedIn](https://www.linkedin.com/in/ritvik-patnala-927206214) | patnala3@illinois.edu | ritvikpatnala851@gmail.com
