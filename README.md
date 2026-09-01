# 5-Stage Pipelined RISC-V Processor

## Overview

This project implements a pipelined RISC-V processor using Verilog HDL.

The processor is divided into multiple pipeline stages to allow instruction-level parallelism and improve processor throughput.

## Architecture

The processor contains the following major stages:

- Instruction Fetch
- Instruction Decode
- Execute
- Memory Access
- Write Back

## Main Components

- ALU
- Register File
- Control Unit
- Instruction Memory
- Data Memory
- Program Counter
- Hazard Unit
- Pipeline Stages

## Repository Structure

```text
rtl/          - Verilog RTL modules
testbench/    - Simulation testbench
program/      - Instruction memory/program files
simulation/   - Simulation results and waveforms
docs/         - Architecture diagrams and documentation