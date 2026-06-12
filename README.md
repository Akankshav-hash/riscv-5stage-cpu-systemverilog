# 5-Stage RISC-V CPU in SystemVerilog

## Overview

This project implements a **32-bit 5-stage pipelined RISC-V processor** using SystemVerilog. The processor follows the standard pipeline stages: Instruction Fetch (IF), Instruction Decode (ID), Execute (EX), Memory Access (MEM), and Write Back (WB). The design demonstrates fundamental computer architecture concepts such as pipelining, hazard handling, and efficient instruction execution.

## Features

* 32-bit RISC-V architecture
* Five-stage instruction pipeline
* ALU for arithmetic and logical operations
* Register file implementation
* Instruction decode and control logic
* Memory access stage
* Write-back stage
* Modular SystemVerilog design

## Project Structure

* `rtl/` – RTL source files with testbench (.sv files)
* `docs/` – Block diagrams and simulation screenshots

## Tools Used

* SystemVerilog
* Cadence Xcelium / ModelSim / EDA Playground

## How to Run

1. Compile the RTL and testbench files.
2. Run the simulation using a supported simulator.
3. Observe waveform outputs and verify processor functionality.

## Results

The processor successfully executes pipelined instructions and demonstrates correct operation across all pipeline stages through simulation.

## Future Improvements

* Data forwarding
* Hazard detection unit
* Branch prediction
* Cache integration

## Author

Akanksha V
