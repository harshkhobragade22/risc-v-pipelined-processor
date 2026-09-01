# 5-Stage Pipelined RISC-V Processor

## Overview

This project presents a Verilog RTL implementation of a pipelined RISC-V processor.

The design is organized into multiple pipeline stages to enable instruction-level parallelism and improve processor throughput.

## Processor Architecture

The processor consists of the following pipeline stages:

1. Instruction Fetch (IF)
2. Instruction Decode (ID)
3. Execute (EX)
4. Memory Access (MEM)
5. Write Back (WB)

## Main Modules

- Program Counter (PC)
- PC Adder
- Instruction Memory
- Register File
- ALU
- Main Decoder
- ALU Decoder
- Control Unit
- Data Memory
- Hazard Unit
- Pipeline Stage Modules

## Project Structure

```text
risc-v-pipelined-processor/
│
├── README.md
├── .gitignore
│
├── rtl/
│   ├── ALU.v
│   ├── ALU_Decoder.v
│   ├── Control_Unit_Top.v
│   ├── Data_Memory.v
│   ├── Decode_Cycle.v
│   ├── Execute_Cycle.v
│   ├── Fetch_Cycle.v
│   ├── Hazard_Unit.v
│   ├── Instruction_Memory.v
│   ├── Main_Decoder.v
│   ├── Memory_Cycle.v
│   ├── Mux.v
│   ├── PC.v
│   ├── PC_Adder.v
│   ├── Pipeline_Top.v
│   └── Register_File.v
│
├── testbench/
│   └── pipeline_tb.v
│
├── program/
│   └── memfile.hex
│
├── simulation/
│   ├── dump.vcd
│   └── waveform.png
│
└── docs/
    └── architecture.png

## Author

Harsh Kumar Khobragade