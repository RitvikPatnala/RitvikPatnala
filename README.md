## Hi, I'm Ritvik Patnala 👋

ECE student at the University of Illinois Urbana-Champaign (BS '26, MEng '27), focused on digital design and computer architecture. I've built projects across the hardware stack — custom PCBs, embedded firmware, and FPGA systems — and what I enjoy most is RTL design: currently building a pipelined RISC-V CPU core in SystemVerilog.

## 🔧 Featured Projects

### RV32I RISC-V CPU Core 🚧 in progress
Single-cycle RV32I processor core in SystemVerilog — register file, ALU, and instruction/data memory — verified with self-checking testbenches covering same-cycle read/write hazards, x0 semantics, and signed/unsigned comparison boundaries. Now extending it into a 5-stage pipeline with data forwarding, load-use stall handling, and branch flushing. 
Tools: SystemVerilog, Icarus Verilog (Simulation), Surfer (Waveform Viewing)

### FPGA Tetris System
Complete hardware gaming system on a Xilinx FPGA: grid-based game logic in SystemVerilog, ROM/palette VGA rendering pipeline with HDMI (TMDS) output, and USB keyboard input via a MAX3421E over SPI, bridged to a MicroBlaze soft core through AXI4-Lite memory-mapped registers. RTL verified with testbenches and a logic analyzer to isolate SPI protocol faults. ~17K LUTs / 58.5 BRAM. 
Tools: SystemVerilog, Vivado, Vitis, MicroBlaze, AXI4-Lite

### [Auto Guitar Tuner] ([https://github.com/RitvikPatnala/auto-guitar-tuner])
Handheld device that detects a guitar string's pitch and physically tunes the peg. Custom ESP32-S3 PCB (schematic → routed layout in KiCAD) with dual buck converters, piezo + LM386 analog front end, and RC anti-aliasing filtering. Firmware implements time-domain autocorrelation pitch detection, chosen over FFT for harmonic rejection and ~22 ms latency, with Hann windowing, interpolation, and PID servo control. Tuned to ±12 cents. All rails verified within ±1%. 
Tools: KiCAD, LTSpice, C (Programming Language), DSP, SPI/I2C/PWM

## 💼 Experience Highlights

### KPIT Technologies: Middleware Intern - AUTOSAR Configuration and AI Automation 
Configured and validated AUTOSAR Basic Software modules for automotive ECUs, managing network interfaces like CAN and LIN protocols while coordinating in cross-functional teams with software, systems, and validation engineers. Prototyped an AI-driven framework by engineering LLM agents to parse vector and relational databases and dynamically update ECU configuration files based on natural language user queries. 

### KPIT Technologies: Middleware Intern -  Test Script Automation
Developed a Python-based scripting tool to automate translation of test cases into executable CMM scripts and generated test reports, supporting ECU verification and validation workflows and improving test execution efficiency by 20%. Rolled out tools to ~30 engineers across validation teams via a week-long training program with written documentation.

## 📁 More Projects



## 🛠️ Skills

## 📫 Reach Me
