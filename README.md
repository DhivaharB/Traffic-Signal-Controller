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

Results and Hardware Verification

The Traffic Signal Controller was successfully designed and implemented using Verilog HDL in Xilinx Vivado.

Implementation Results

- RTL simulation completed successfully.
- Synthesis completed successfully.
- Design implementation completed successfully.
- Bitstream generation completed successfully.
- FPGA programming completed successfully.

Hardware Verification

The generated bitstream was programmed onto the Digilent Nexys A7 FPGA board. The onboard LEDs were tested and verified to display the traffic signal sequences correctly.

Conclusion

The Traffic Signal Controller was successfully simulated, implemented, and tested on FPGA hardware. The project demonstrates the practical application of Verilog HDL, finite state machines (FSM), and FPGA-based digital system design.

Tools and Hardware

- HDL: Verilog
- Software: Xilinx Vivado
- FPGA Board: Digilent Nexys A7
- Programming Language: Verilog HDL

Project Status

Successfully Completed
