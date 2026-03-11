# Hi! I'm Jose Andres Vargas Torres

**Computer Engineering Student @ TEC**
**Hardware Verification | Architecture | SystemVerilog | C++**

*Specializing in hardware verification and computer architecture with hands-on experience in cache coherence protocols, multiprocessor systems, and FPGA design. Combining technical expertise in SystemVerilog/Verilog with strong C++ programming skills for performance-critical applications.*

---

## About Me

- **Education:** Computer Engineering student at Costa Rica Institute of Technology (Graduation: July 2027)
- **Focus Areas:** Hardware Verification, Computer Architecture, Cache Coherence, FPGA Design
- **Currently:** Computer Area Operator at TEC (since June 2023) - maintaining technological equipment and resolving technical incidents
- **Leadership:** Table Tennis Coach at Santo Domingo Sports Committee (since May 2025)
- **Learning:** UVM/OVM verification methodologies, advanced SystemVerilog assertions

---

## Technologies & Tools

**Hardware Design & Verification:**
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-EE4C2C?style=for-the-badge&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-543978?style=for-the-badge&logoColor=white)
![VHDL](https://img.shields.io/badge/VHDL-543978?style=for-the-badge&logoColor=white)
![FPGA](https://img.shields.io/badge/FPGA-0071C5?style=for-the-badge&logoColor=white)
![Quartus](https://img.shields.io/badge/Quartus-0071C5?style=for-the-badge&logoColor=white)
![ModelSim](https://img.shields.io/badge/ModelSim-00629B?style=for-the-badge&logoColor=white)

**Programming Languages:**
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)

**Software Development:**
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Tools & Platforms:**
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)

---

## Featured Projects

### [ARMv4 Single-Cycle Processor Design & Verification](https://github.com/JoseAndresVargasTorres/jVargas_kZheng_jEspinoza_final_proyect_2024)
*Complete ARMv4 single-cycle processor in SystemVerilog with functional verification*
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-EE4C2C?style=flat-square&logoColor=white)
![FPGA](https://img.shields.io/badge/FPGA-0071C5?style=flat-square)
![ModelSim](https://img.shields.io/badge/ModelSim-00629B?style=flat-square)

**Key Achievements:**
- Designed complete **ARMv4 single-cycle processor** with datapath, control unit, and memory subsystem
- Implemented **ALU** with parameterized bitwidth and flag generation (N, Z, C, V)
- Built **register file** with read/write ports and **control unit** with conditional execution
- Developed individual **testbenches** (`alu_tb.sv`, `file_register_tb.sv`, `unit_control_tb.sv`, `arm_tb.sv`) using **SystemVerilog assertions**
- Synthesized design on **Altera DE1-SoC FPGA** (Cyclone V) with iterative bring-up and debug

**Technical Highlights:**
- SystemVerilog HDL design and synthesis
- Assertion-based testbench development for processor verification
- FPGA implementation and timing analysis on Intel/Altera Cyclone V

---

### [Custom-ISA Pipelined Processor (ASIP for Image Interpolation)](https://github.com/kunZhen/Proyecto-Grupal-1---Arqui-I)
*Pipelined processor with custom ISA designed for bilinear interpolation on images*
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-EE4C2C?style=flat-square&logoColor=white)
![FPGA](https://img.shields.io/badge/FPGA-0071C5?style=flat-square)
![ModelSim](https://img.shields.io/badge/ModelSim-00629B?style=flat-square)
![Quartus](https://img.shields.io/badge/Quartus-0071C5?style=flat-square)

**Key Achievements:**
- Contributed to a **5-stage pipelined processor** (IF/ID/EX/MEM/WB) with a custom ISA for image bilinear interpolation
- Pipeline includes **data forwarding** (`forwarding_unit.sv`), **hazard detection** (`hazard_detection_unit.sv`), and **branch flush logic**
- Responsible for **JTAG integration** and **VGA/HDMI controller** development for displaying processed images from memory
- Team wrote comprehensive testbenches (`pipeline_tb.sv`, `datapath_unit_tb.sv`, `alu_tb.sv`, `imm_gen_tb.sv`) with assertions
- Synthesized and verified on **Intel/Altera FPGA** using Quartus Prime and ModelSim

**Technical Highlights:**
- Pipelined datapath with hazard resolution and forwarding
- JTAG debugging interface integration
- VGA/HDMI video output controller for real-time image display

---

### [MESI Cache Coherence Multiprocessor Simulator](https://github.com/JoseAndresVargasTorres/Proyecto-01-MP-MESI-ArquitecturadeComputadoresII-II25)
*Complete multiprocessor system implementing MESI cache coherence protocol*
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Multithreading](https://img.shields.io/badge/Multithreading-FF6B6B?style=flat-square)
![FLTK](https://img.shields.io/badge/FLTK-00599C?style=flat-square)
![Architecture](https://img.shields.io/badge/Architecture-4CAF50?style=flat-square)

**Key Achievements:**
- Designed **4-PE parallel system** with shared bus interconnect for dot product computation
- Implemented full **MESI protocol** (Modified, Exclusive, Shared, Invalid) with snooping mechanisms (BusRd, BusRdX, Invalidate, Flush)
- Built **interactive GUI** (FLTK) for real-time visualization of cache states, MESI transitions, and memory operations
- Developed **write-back cache** with LRU replacement policy and 2-way set associativity
- Applied **C++ multithreading** with mutexes, semaphores, and scoped locks
- Generated comprehensive **performance metrics**: hit/miss rates, bus traffic, writebacks
- Achieved **83.6% memory bandwidth reduction** through cache optimization

**Technical Highlights:**
- Cache coherence verification in multicore environment
- Race condition debugging and false sharing prevention
- Performance analysis and optimization techniques

---

### [SystemVerilog Digital Design Labs](https://github.com/JoseAndresVargasTorres/jVargas_kZheng_jEspinoza_digital_design_lab_2024)
*Comprehensive collection of digital design projects with verification*
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-EE4C2C?style=flat-square)
![FPGA](https://img.shields.io/badge/FPGA-0071C5?style=flat-square)
![Testbench](https://img.shields.io/badge/Testbench-4CAF50?style=flat-square)

**Key Projects:**
- **VGA Controller:** Video generation pipeline with FSM-based timing control
- **Arithmetic Units:** Multipliers, dividers, shifters, parametrizable ALUs
- **Sequential Logic:** FSMs, counters, registers with comprehensive testbenches
- **Battleship Game:** Complex FSM logic with hardware randomization and VGA display
- **Verification:** Assertions, structured test cases, corner case testing

**Technical Highlights:**
- SystemVerilog testbench development
- Verification methodologies and best practices
- FPGA synthesis and implementation on DE1-SoC (Cyclone V)

---

### [NFL Fantasy Football Platform](https://github.com/Caro186/dise-o_NFL)
*Full-stack application with clean architecture and cloud deployment*
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)

**Key Features:**
- **Backend:** ASP.NET Core API with clean architecture
- **Frontend:** Angular with TypeScript
- **Cloud:** Azure deployment with C2 architecture diagrams
- **Testing:** Comprehensive unit tests and API documentation
- **Methodology:** Agile/Scrum with code reviews

---

### [Synchronized Process Communication](https://github.com/JoseAndresVargasTorres/Proyecto1-Comunicaci-n-de-procesos-sincronizada)
*Synchronization techniques for concurrent systems using POSIX shared memory*
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![POSIX](https://img.shields.io/badge/POSIX-FCC624?style=flat-square)
![Multithreading](https://img.shields.io/badge/Multithreading-FF6B6B?style=flat-square)

**Key Achievements:**
- Implemented **POSIX shared memory** (`shm_open`, `mmap`) with named semaphores for inter-process communication
- Built a multi-process system (initializer, emitter, receiver, finalizer) with **producer-consumer synchronization**
- Solved **race conditions** using mutex semaphores and per-slot empty/full semaphore arrays
- Designed **Makefile** with POSIX flags, automated test targets, and multi-terminal execution support
- Focused on **deadlock prevention**, graceful termination, and resource cleanup

**Technical Highlights:**
- POSIX IPC: shared memory, named semaphores, memory-mapped files
- Debugging concurrency issues across multiple independent processes
- Performance tuning for shared resources

---

**View all repositories:** [github.com/JoseAndresVargasTorres](https://github.com/JoseAndresVargasTorres?tab=repositories)

---

## Relevant Coursework

- **Computer Architecture I:** Single-cycle and pipelined processor design, ISA design, FPGA synthesis
- **Computer Architecture II:** Cache coherence (MESI), multiprocessor systems, performance optimization
- **Digital Design:** SystemVerilog/Verilog HDL, FPGA synthesis, testbench development
- **Concurrent Programming:** Process synchronization, POSIX IPC, shared memory, semaphores
- **Operating Systems:** Process management, resource scheduling, deadlock prevention
- **Software Design:** Clean architecture, design patterns, Agile methodologies

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jose-andres-vargas-torres-43020228b/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tamiguisimo@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JoseAndresVargasTorres)

**Phone:** +506 8368 9388
**Location:** San Jose, Costa Rica
**Status:** Open to internship opportunities in hardware verification and computer architecture

---

## Current Focus

**I'm currently working on:**
- Deepening knowledge in UVM/OVM verification methodologies
- Exploring advanced SystemVerilog assertions
- Contributing to open-source hardware verification projects

**I'm currently learning:**
- Universal Verification Methodology (UVM)
- Advanced cache coherence protocols (MOESI, MESIF)
- GPU architecture and parallel computing

---

*"Discipline and precision drive excellence in both hardware verification and competitive sports."*
