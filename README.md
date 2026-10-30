<h1 align="center">Brayden Leone</h1>

<p align="center">
  Computer Science @ UMass Dartmouth ('29)<br>
  Interested in compiler design, systems programming, computer architecture, operating systems, and graphics programming.
</p>

<p align="center">
  Building a custom AArch64 toolchain, including a C compiler, assembler, CPU simulator, and virtual machine.
</p>

<p align="center">
  <a href="mailto:brayden.j.leone@gmail.com">Email</a> •
  <a href="https://www.linkedin.com/in/brayden-leone/">LinkedIn</a> •
  <a href="https://codehs.com/blog/coding-beyond-the-curriculum">Featured on CodeHS</a>
</p>

---

### Currently Building
**[ARM Operating System](https://github.com/BJL156/ARM-Operating-System)**

Developing an operating system from scratch for AArch64, with boot support, exception handling, interrupt management, and memory management. The long-term goal is to run programs compiled with my custom C compiler and assembler.

### AArch64 Toolchain Roadmap
I'm implementing each stage of the toolchain myself rather than relying on existing compiler toolchain (such as GNU), with the goal of understanding the entire path from source code to a final executable.

<p align="center">
  <img src="toolchain.svg" width="800">
</p>

- [x] **[Expression VM Calculator](https://github.com/BJL156/Expression-VM-Calculator)**: Lexer, Reverse Polish conversion, bytecode generation, and virtual machine executor.
- [x] **[Custom ISA + CPU Simulator](https://github.com/BJL156/CPU-Simulator)**: Designed a custom instruction set (ISA) and CPU bytecode simulator for it.
- [x] **[ARM Assembler](https://github.com/BJL156/ARM-Assembler)**: Converts AArch64 assembly directly into ELF64 executables.
- [x] **[ARM C Compiler](https://github.com/BJL156/ARM-C-Compiler)**: Converts a subset of C into AArch64 assembly for use with my assembler.
- [ ] **[ARM Operating System](https://github.com/BJL156/ARM-Operating-System)** (*Current Project*): Compile code using the toolchain on a custom-built operating system.
---

### Software Rasterizer & Graphics Engine
**[Mini Raster 3D](https://github.com/BJL156/Mini-Raster-3D)**

Built a 3D software rasterizer from scratch in C++, implementing core graphics pipeline operations on the CPU without relying on graphics APIs for rasterization.

- Implemented triangle rasterization, depth buffering, and perspective-correct interpolation.
- Developed 3D transformation pipelines and texture-mapped mesh rendering.
- Created a custom vector and matrix mathematics library for 3D graphics calculations.
- Built a rendering loop for continuous frame generation and display.

### Tech Stack
<p>
  <img src="https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white">
  <img src="https://img.shields.io/badge/AArch64_ASM-red?style=flat">
  <img src="https://img.shields.io/badge/GLSL-5586A4?style=flat">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black">
</p>

---

> Fun fact: The Toyota FJ Cruiser has three windshield wipers because the windshield is too short and wide for just two.
