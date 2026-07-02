# Pipelined RISC-V Processor 

## Overview

This project implements a fully functional **pipelined RISC-V processor** using Verilog and deploys it on a **PYNQ-Z2 FPGA** board. The processor is capable of executing a wide range of RISC-V instructions with improved performance through pipelining.

## Features

- Five-stage pipelined architecture: **Fetch, Decode, Execute, Memory, Writeback**
- Supports **base RISC-V RV32I instruction set**
- Handles **data and control hazards** using forwarding and stalling
- Improved throughput over a single-cycle implementation
- Supports **base RISC-V RV32I instruction set**
- Synthesized and deployed on **PYNQ-Z2 FPGA**
- Simulated and verified using **testbench programs**

## Datapath Design

## Datapath Design

![Datapath Design](https://github.com/user-attachments/assets/a5f49b91-5b1c-43f8-bbd1-61a300c4ff9b)
<img width="842" height="525" alt="image" src="https://github.com/user-attachments/assets/a5f49b91-5b1c-43f8-bbd1-61a300c4ff9b" />

## Instruction Set Formats

<img width="920" height="190" alt="image" src="https://github.com/user-attachments/assets/c48e7544-7cf9-4859-8c07-e1c427a0883d" />

## Instruction Opcodes

<img width="448" height="651" alt="image" src="https://github.com/user-attachments/assets/f536614a-7785-46ec-8985-ac7a7914367f" />

## Author
Raghav Yatgiri
