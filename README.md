# Simple JS Visual CPU Simulator

## Description

The **Simple JS Visual CPU Simulator** is an interactive tool that simulates basic CPU operations in JavaScript. It allows users to input two numbers, which are then added together using a set of CPU instructions. This simulator visually represents the execution process step-by-step, showing how the CPU manipulates data in registers and performs basic operations.

This project is designed to help learners understand fundamental CPU concepts such as registers, program counters, and instruction flow.

## Features

- **Input Fields**: Enter two numbers that will be added together using CPU instructions.
- **Registers Visualization**: Shows the state of CPU registers (`R0`, `R1`, `R2`) which are updated during execution.
- **Program Counter (PC)**: Displays the current position in the program, incrementing after each instruction.
- **Step-by-Step Execution**: Each CPU instruction (`MOV` and `ADD`) is highlighted and executed in sequence.
- **Real-Time Updates**: As the program executes, register values are updated to reflect the result of each instruction.

## How It Works

1. **MOV**: Moves the input values into CPU registers (`R0` and `R1`).
2. **ADD**: Adds the value in `R1` to `R0` and stores the result back into `R0`.
3. **Program Counter (PC)**: Increments after each instruction, showing the progression of the program.
4. The current instruction is highlighted in real-time, providing a visual walkthrough of the CPU's operations.

### Example Execution:
- Input: `3` and `4`.
- The CPU performs the following steps:
  1. Moves `3` into `R0`.
  2. Moves `4` into `R1`.
  3. Adds `R1` to `R0`, updating `R0` to `7`.

## Setup

To run this project locally:

1. **Clone the repository**:

```bash
git clone https://github.com/sebastian-collab/Simple-JS-Visual-CPU-Simulator.git
