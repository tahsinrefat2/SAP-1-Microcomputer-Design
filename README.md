# SAP-1-Microcomputer-Design
 1. Introduction
The SAP-1 (Simple as Possible) microcomputer is a foundational model for understanding basic computer architecture. This project implements a SAP-1 design in Logisim, a digital logic circuit simulation tool. The microcomputer supports five operations: LDA (Load Accumulator), ADD, SUB, OUT (Output), and HLT (Halt), demonstrating the core functionalities of a basic von Neumann architecture.

 2. System Overview
The SAP-1 microcomputer consists of the following key components:
Program Counter (PC): Manages the sequencing of instructions by keeping track of the memory address being executed.
Memory Address Register (MAR): Temporarily stores the address of the instruction to be fetched from RAM.
Random Access Memory (RAM): Stores instructions and data for execution.
Instruction Register (IR): Holds the current instruction fetched from memory.
Controller/Sequencer: Generates control signals to coordinate the execution of instructions.
Arithmetic Logic Unit (ALU): Performs arithmetic operations like addition and subtraction.
Accumulator (ACC): Stores the result of ALU operations.
B Register: Temporarily holds data to be used in arithmetic operations.
Output Register: Displays results for the user.
Clock: Synchronizes the operations across components.
