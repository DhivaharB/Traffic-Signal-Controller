FPGA Based Traffic Signal Controller

Project Overview

This project implements a traffic signal controller using Verilog HDL on the Digilent Nexys A7 FPGA development board.

Features

- Two-way traffic signal control
- North-South and East-West traffic management
- Finite State Machine (FSM)
- 100 MHz FPGA clock
- Clock divider for traffic timing
- Emergency override
- Automatic traffic light sequence

Hardware Requirements

- Digilent Nexys A7 FPGA board
- USB programming cable
- Computer with Xilinx Vivado

Software Requirements

- Xilinx Vivado Design Suite
- Verilog HDL

Traffic Signal Timing

Signal| Duration
North-South Green| 5 seconds
North-South Yellow| 2 seconds
East-West Green| 5 seconds
East-West Yellow| 2 seconds
All Red| 1 second

Project Files

- "traffic_signal_controller.v" – Main Verilog source code
- "Nexys_A7.xdc" – FPGA pin constraints
- "README.md" – Project documentation

Implementation Flow

1. RTL Design
2. Simulation
3. Synthesis
4. Implementation
5. Bitstream Generation
6. FPGA Hardware Programming

FPGA Board

Digilent Nexys A7 (Artix-7)

Author

Dhivahar B

B.Tech Electronics and Communication Engineering