# 3 Stage Piplined Processor #

## Overview: ##
This repository contains the System Verilog code for a simple processor design. The processor is written in System Verilog and supports various RISC-V instructions. The design includes modules for different components like the ALU, register file, memory, and control unit.

## Files: ##
- `Processor.sv:` The main module that instantiates all the components of the processor.
- `alu.sv:` The Arithmetic Logic Unit responsible for executing arithmetic and logic operations.
- `reg_file.sv:` The Register File module for handling register read and write operations.
- `data_mem.sv:` The Data Memory module for managing data memory operations.
- `csr_reg.sv:` The Control and Status Register module for handling system control operations.
- `controller.sv:` The Controller module that generates control signals based on the opcode and function codes.
- `PC.v:` The Program Counter module for managing the program counter.
- `inst_mem.sv:` The Instruction Memory module for storing instructions.
- `Inst_decode.sv:` The Instruction Decoder module for decoding instructions.
- `imm_gen.sv:` The Immediate Generator module for generating immediate values.

## HowToUse ##
The design can be simulated using a Verilog simulator like ModelSim. By running the command `./cc.bat`

## System Diagram ##
![System Diagram](/system%20diagram/1.png)

## Author ##
- Muhammad Hamza Ikram
- 2020-CE-06
