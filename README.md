# 16-bit CPU Simulator

A custom 16-bit CPU built from the ground up using basic logic gates, inside a simulator ([Digital-Logic-Sim](https://github.com/SebLague/Digital-Logic-Sim) by Sebastian Lague)

<img width="1400" height="801" alt="image" src="https://github.com/user-attachments/assets/93bb776b-7999-4ac7-b76c-96bf959659b8" />

## Current Features
- 16-bit architecture
- Hardwired Control Unit
- Custom Instruction set (inspired by _Digital Logic and Computer Design_ by M. Morris Mano)
- Single Accumulator based architecture
- Arithmetic Logic Unit
- Programmable Memory
- 1KB of RAM and ROM
- Tri-State Bus architecture

## Architecture Overview
### Register Architecture
- **PC** (Program Counter) : Holds address of next memory instruction to be executed
- **IR** (Instruction Register): Stores current 16-bit Instruction
- **AR** (Address Register): Supplies address information to Main Memory
- **AC** (Accumulator): Active register for performing operations
- **DR** (Data Register): Accepts read data word from Main Memory

### Instruction Cycle
- **Fetch** Instruction from memory and increment PC
- **Decode** Instruction
- **Execute** Operation
- **Write** Back result

### Inside Register
<img width="1200" height="620" alt="image" src="https://github.com/user-attachments/assets/2a76c149-e438-498b-989b-0993c6782a95" />


  
