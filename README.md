# FPGA-Based-Two-Input-Addition-Calculator-with-Decimal-7-Segment-Display
Real-time FPGA calculator using Verilog HDL for adding two 4-bit binary inputs and displaying the decimal result on a dual 7-segment display.
FPGA Cyclone IV Addition Calculator

This project is a digital calculator implementation based on FPGA Cyclone IV that performs addition operations between two 4-bit binary inputs and displays the result in decimal format using a dual 7-segment display. The system utilizes slide switches as input devices and is developed using Verilog HDL following a complete digital system development workflow, from design and implementation to hardware testing.

The calculator receives two binary numbers from FPGA slide switches, processes the addition operation in real time, converts the binary result into Binary-Coded Decimal (BCD) format, and displays the corresponding decimal value on a multiplexed 7-segment display. This project demonstrates the practical implementation of an Arithmetic Logic Unit (ALU), digital combinational logic, FPGA input-output interfacing, and display control techniques.

Objectives

Develop and implement a simple addition calculator using FPGA Cyclone IV.

Apply the concept of Arithmetic Logic Unit (ALU) in digital hardware design.

Perform a complete FPGA development cycle including coding, synthesis, pin assignment, implementation, and hardware testing.

Integrate hardware logic with physical input and output devices such as slide switches and 7-segment displays.

Convert binary calculation results into decimal representation for easier user interaction.

System Features

Two 4-bit binary inputs using FPGA slide switches.

Real-time addition operation.

Binary-to-BCD conversion for decimal output representation.

Multiplexed dual-digit 7-segment display.

Verilog HDL implementation.

FPGA Cyclone IV compatible design.

System Architecture

The system consists of three main modules:

1. Calculator Top Module
   Handles input processing, performs the addition operation, and coordinates communication between all modules.

2. BCD Converter Module
   Converts the 5-bit binary addition result into decimal tens and units digits using combinational logic.

3. Seven Segment Multiplexer Module
   Controls multiplexing and decoding of decimal digits for display on the dual 7-segment interface.

Development Process

System analysis and requirement definition.

Verilog HDL module design.

Simulation and functional verification.

Pin assignment configuration.

FPGA synthesis and compilation.

Hardware implementation on FPGA Cyclone IV.

Real-time testing and validation.

Input and Output

Inputs:
4-bit Binary Input A (Slide Switches)
4-bit Binary Input B (Slide Switches)
50 MHz FPGA Clock Signal

Outputs:
Dual 7-Segment Display
Decimal Result Display

Example Results

0 + 0 = 0

1 + 1 = 2

4 + 5 = 9

7 + 3 = 10

8 + 8 = 16

12 + 8 = 20

15 + 15 = 30

All tested combinations produced results consistent with expected mathematical calculations.

Technologies Used

FPGA Cyclone IV

Verilog HDL

Quartus Prime

Digital Logic Design

7-Segment Display Multiplexing

Binary-to-BCD Conversion

Learning Outcomes

Understanding FPGA-based digital system development.

Practical implementation of ALU concepts.

Experience with Verilog HDL programming.

Integration of hardware interfaces with digital logic.

Design and testing of real-time digital systems.
