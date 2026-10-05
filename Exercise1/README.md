# Exercise 1

## Objective

The objective of this exercise is to become familiar with the vnmsim simulator and identify the main components of the Von Neumann architecture.

## Interface Components

The vnmsim interface represents several important components of a computer processor. The main components visible in the simulator are RAM, IR, Decoder, ALU, ACC, PC, Data Bus and Address Bus.

### RAM (Random Access Memory)

RAM represents the memory of the Von Neumann architecture. It stores program instructions and data.

### IR (Instruction Register)

IR stores the instruction that is currently being processed by the CPU.

### Decoder

The Decoder is part of the control unit. It decodes the current instruction and determines which operation should be performed.

### ALU (Arithmetic Logic Unit)

The ALU performs arithmetic and logical operations.

### ACC (Accumulator)

ACC is a CPU register used to temporarily store data and intermediate results of calculations.

### PC (Program Counter)

PC stores the address of the next instruction that should be fetched from memory.

### Data Bus

The Data Bus is used to transfer data between the processor and memory.

### Address Bus

The Address Bus transfers memory addresses and determines the location from which data or instructions should be accessed.

## Relationship with the Von Neumann Architecture

The vnmsim simulator demonstrates the main principles of the Von Neumann architecture. Both instructions and data are stored in memory (RAM). The PC identifies the address of the next instruction, which is loaded into the IR. The Decoder interprets the instruction, and the ALU performs the required operation. The ACC can store intermediate or final results.

Therefore, the simulator provides a visual representation of the main CPU and memory components of the Von Neumann architecture and shows how they communicate through buses.

## Conclusion

The vnmsim interface represents the main components of the Von Neumann architecture: memory, processor, control unit, ALU, registers and buses. Understanding these components helps to understand how a computer fetches, decodes and executes instructions.
