# Surya S

Designing High-Performance Hardware from RTL to Silicon & AI

[![Email](https://img.shields.io/badge/Email-suryaa.senthilr%40gmail.com-0A66C2?style=flat-square&logo=gmail&logoColor=white)](mailto:suryaa.senthilr@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Surya%20S-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/surya-s-b05907337/)
[![Portfolio](https://img.shields.io/badge/Portfolio-View%20Portfolio-0A66C2?style=flat-square&logo=vercel&logoColor=white)](https://surya-vlsi.vercel.app/)

---

## About Me

I design digital ICs, computer architectures, and hardware accelerator subsystems from synthesizable RTL to verified silicon and FPGA implementations. My work focuses on parallel compute engines, memory hierarchies, post-quantum cryptographic arithmetic, and hardware-software co-design.

---

## What I Work On

- **Computer Architecture**: SIMT execution pipelines, warp schedulers, systolic arrays, non-blocking cache controllers, and memory coherence.
- **RTL & Digital Design**: Synthesizable SystemVerilog/Verilog, AMBA AXI4/AXI4-Lite interconnects, and cycle-accurate verification.
- **Hardware Security & Cryptography**: Post-quantum lattice cryptography (FIPS 203 / 204 NTT) with zero memory stalls.
- **Silicon Reliability & Mixed-Signal**: In-situ voltage droop mitigation, analog chaotic oscillators, and physical design flows.
- **Autonomous AI Systems**: Multi-agent software engineering architectures and stateful graph workflows (LangGraph).

---

## Technical Toolbox

| Category | Tools & Technologies |
| :--- | :--- |
| **HDLs & Modeling** | SystemVerilog, Verilog-2001, Python Co-Simulation, C++ Reference Models |
| **Verification & Simulation** | Icarus Verilog, Verilator, GTKWave, Waveform Analysis |
| **Synthesis & Physical Design** | Yosys, OpenROAD, OpenSTA, KLayout, TritonCTS, Magic VLSI |
| **Target Platforms** | Nangate 45nm (FreePDK45), Xilinx Artix-7 FPGA, AMBA AXI4 / AXI4-Lite |
| **Analog & Mixed-Signal** | LTspice XVII, Monte Carlo Yield Analysis, Nonlinear Dynamical Systems |
| **AI & Software** | Python, PyTorch, LangGraph, Multi-Agent Systems |

---

## Selected Projects

### [Apex-TPU: 2D Systolic Array Tensor Core](https://github.com/suryasenthilr/apex-tpu)
Synthesizable 2D systolic array accelerator core implementing Weight-Stationary spatial dataflow for GEMM and Transformer neural network workloads. Features 64 MACs, 64-bit AXI4 Master DMA, and 45nm physical signoff.

### [Apex-GPU: 8-Lane SIMT Multiprocessor](https://github.com/suryasenthilr/apex-gpu)
General-purpose GPU compute core executing parallel warps with hardware branch divergence stack, 8-lane SIMT vector pipelines, and 256-bit AXI4 memory burst interface.

### [PolyFlex-NTT: Post-Quantum Cryptography Accelerator](https://github.com/suryasenthilr/polyflex-ntt)
Reconfigurable hardware accelerator for polynomial multiplication in lattice-based cryptography, supporting both ML-KEM (Kyber / FIPS 203) and ML-DSA (Dilithium / FIPS 204). Achieves zero-stall conflict-free SRAM memory mapping across both ASIC (45nm) and FPGA (Xilinx Artix-7).

### [Apex-Cache: Non-Blocking L1 Data Cache](https://github.com/suryasenthilr/apex-l1cache)
High-performance non-blocking L1 data cache subsystem with Miss Status Holding Registers (MSHR), 4-way set associativity, Tree-PLRU replacement, and multi-core MESI snooping coherence.

### [VoltTensor: Voltage-Aware Microarchitecture](https://github.com/suryasenthilr/VoltTensor)
Voltage droop mitigation co-design combining hardware current slew ($di/dt$) smoothing with software neural network weight scheduling and in-situ delay slack monitors.

### [LTspice Chua: Chaotic Communications Circuit](https://github.com/suryasenthilr/ltspice-chua-chaotic-communications)
Nonlinear analog circuit implementing Chua's diode with dual op-amp negative impedance converter for secure chaotic carrier modulation and Pecora-Carroll synchronization.

### [LangGraph Multi-Agent Software Engineering](https://github.com/suryasenthilr/multi-agent-software-engineering-system-LangGraph)
Autonomous collaborative multi-agent architecture orchestrating Product Manager, Architect, Coder, and QA agents via cyclic graph state machines with self-healing feedback loops.

---

## Education

**Vellore Institute of Technology (VIT), Chennai**  
*B.Tech in Electronics and Communication Engineering (2024 – 2028)*  
Focus: Digital VLSI Design, Computer Architecture, CMOS Integrated Circuits, Microprocessors
