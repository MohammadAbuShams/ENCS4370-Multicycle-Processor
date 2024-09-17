# ENCS4370 Multicycle Processor

This repository contains the project for the COMPUTER ARCHITECTURE – ENCS4370 course at the Faculty of Engineering & Technology, Electrical & Computer Engineering Department. The project focuses on designing, implementing, and verifying a multi-cycle RISC processor using Verilog.

## Project Overview

This project aimed to create a 16-bit RISC processor capable of handling multiple instruction formats such as R-type, I-type, J-type, and S-type, each with its specific opcode and set of functionalities. The processor is designed to utilize a multi-cycle approach to instruction execution, enhancing the efficiency of resource usage and optimizing functional unit operations like the ALU and memory accesses.


## Features

- **Multi-cycle Instruction Execution**: Breaks down the instruction execution into multiple cycles, allowing for efficient use of the processor's ALU and memory.
- **Diverse Instruction Set**: Supports a variety of operations including arithmetic, logical, load/store, and branch instructions.
- **Separate Instruction and Data Memories**: Implements separate memories for instructions and data, adhering to the principles of Harvard architecture.
- **Detailed Verification**: Utilizes extensive simulation and test benches to ensure the correct functionality of all implemented instructions.

## Design and Implementation

The processor features a comprehensive design with a focus on the following components:

- **Program Counter (PC)**
- **Register File**
- **ALU (Arithmetic Logic Unit)**
- **Control Unit**
- **Data Memory and Instruction Memory**

Each component is meticulously designed to handle specific tasks within the processor's operation, ensuring a robust and efficient computational system.

## Simulation and Testing

Simulation tests are included to verify the functionality of each component and the processor as a whole. These tests cover various scenarios to ensure all parts of the processor work together seamlessly and correctly.


