# LPDDR-Style Memory Subsystem (SystemVerilog + UVM)

**Status: In progress**

## Goal
A simplified memory controller with an AXI4 interface, SECDED ECC,
refresh and low-power modes, verified with UVM, SVA and functional coverage.

## Roadmap
- [ ] Sync FIFO + self-checking testbench
- [ ] Async FIFO (Gray-code CDC)
- [ ] ECC SECDED (72,64)
- [ ] DRAM behavioral model with timing checks
- [ ] Controller FSM + refresh engine
- [ ] AXI4 slave interface
- [ ] UVM environment, SVA, coverage
- [ ] Low-power modes (power-down, self-refresh)

## Repository structure
- `rtl/` design files
- `tb/` testbenches
- `docs/` specs and diagrams
- `sim/` simulation scripts
- `scripts/` Python helper scripts
- `bugs.md` bugs found and how they were fixed

## Tools
Xilinx Vivado, Python

## Author
L. Ramya Sri
