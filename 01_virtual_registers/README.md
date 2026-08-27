# Virtual Hardware Register Simulator

## Overview

A C program that simulates an 8-bit hardware register and allows individual bits to be set, cleared, toggled, checked, and reset. The project was built to practice low-level bit manipulation concepts commonly used in embedded systems and hardware programming.

## Problem Statement

Hardware registers are often represented as groups of individual bits, where each bit controls or represents a specific hardware feature. This project simulates such a register using an 8-bit integer and provides operations for manipulating individual bits.

## Requirements

* Set a particular bit
* Clear a particular bit
* Toggle a particular bit
* Check whether a particular bit is set
* Print the register in binary
* Reset the register

## Concepts Practiced and learnt

* `uint8_t` and fixed-width integer types
* Bitwise AND (`&`)
* Bitwise OR (`|`)
* Bitwise XOR (`^`)
* Bitwise NOT (`~`)
* Left shift (`<<`)
* Right shift (`>>`)
* Functions
* `for` loops

## Implementation

The register is represented using a `uint8_t`, which provides exactly 8 bits, unsigned.

Each operation is implemented as a separate function that receives a pointer to the register and the bit position to operate on.

## Example Output

```text
8
136
128
129
Bit is 1
10000001
0
```