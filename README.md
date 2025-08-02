# mini_cpu

A 32-bit classic five-stage pipelined processor core designed using Verilog HDL, based on the RV32I instruction set.
This is an implementation of a RISC-V 32-bit five-stage pipelined CPU, developed as a learning project after studying computer architecture courses.

[中文版 README](README_zh.md)

## Features
- Based on RISC-V RV32I instruction set
- Classic five-stage pipeline architecture
- Implemented in Verilog HDL
- Simulation and testing support

## Build and Run

### Compile Assembly Test Program
```bash
make asm
```

### Run CPU Simulation
```bash
make cpu
```

### View Simulation Waveforms
```bash
make wave
```

### Clean Temporary Files
```bash
make clean
```

## Project Structure
- `rtl/` - Verilog source code (CPU core modules)
- `sim/` - Simulation related files
- `tb/` - Testbench files
- `tmp/` - Temporary files directory

## Dependencies
- RISC-V Toolchain (riscv64-linux-gnu)
- Icarus Verilog (iverilog)
- GTKWave (waveform viewer)
- Python3

## Reference
[Computer Architecture Course](https://time.geekbang.org/column/intro/100117801?utm_campaign=geektime_search&utm_content=geektime_search&utm_medium=geektime_search&utm_source=geektime_search&utm_term=geektime_search)
