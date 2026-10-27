# dual-port-ram-uvm
UVM-based Design Verification of a Dual-Port Synchronous RAM using uvm

# Dual-Port RAM – UVM-Based Design Verification

## Overview
This project demonstrates the design and functional verification of a
parameterized Dual-Port Synchronous RAM using Verilog/SystemVerilog and UVM.

## Features
- Dual-port synchronous RAM
- Independent read/write operations
- Simultaneous access through two ports
- Same-address conflict verification
- Different-address simultaneous access
- Overwrite scenario verification
- Directed and constrained-random transactions
- Reference memory model
- Scoreboard-based data checking

## Verification Environment
The UVM environment contains:
- Sequence Item
- Sequence
- Sequencer
- Driver
- Monitor
- Agent
- Environment
- Scoreboard
- Reference Model

## Tools
- SystemVerilog
- UVM
- Synopsys VCS
- Synopsys Verdi

## Verification Scenarios
1. Single-port read/write
2. Simultaneous read/write
3. Simultaneous different-address writes
4. Same-address conflict
5. Overwrite operation
6. Randomized transactions

## Result
The design was verified using directed and randomized transactions,
with scoreboard-based checking for expected versus actual data.

## Author
Sarif Ahmad

M.Tech – Electronic Circuits & Systems Design  
Aligarh Muslim University
