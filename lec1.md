# Lecture 1: Digital System Basics

## Introduction to a System

At the simplest level, a system takes some input value, and returns an output value.
- Also can be represented in many different ways (block diagram, table, graph, etc.)

Systems can be characterized as analog or digital:
- Analog: inputs and outputs are from a continuous, infinite set
- Digital: finite amount of inputs and outputs

In this class we mainly cover digital systems as they are prevalent in many areas of
information processing, transmission, and storage.

Few reasons why digital systems are used:
1. Usable in both numerical/nonnumerical processing
2. Can use a general-purpose system (i.e, a computer)
3. Utilizes binary signals (simple devices, just an open and close state)
4. Insensitive to variation (round noise to nearest integer/finite value)
5. Can easily scale accuracy by increasing digit representations
6. Corresponding advances in microelectronics (Moore's Law, etc.)
7. Speed vs. Hardware trade-off

On a side note, a lot of complex devices we use now are mixed analog digital systems.
- this means they use ADC and DAC converters to work with both types of data

## Digital Systems at a High Level

At its core, we have an Input Set, Output Set, and a specification of the Input-Output
function (system)

Input and Output Sets:
- Vector of any type (i.e: digit, character, set, bit). Examples:

$$x = (7, 0, 6, 3), \enspace c = (B, O, O, K)$$

Input and Output Functions:
- Tables
- Arithmetic Expressions (i.e $z = 3x + 2y - 2$
- Conditional Expressions (piecewise functions)
- Logical Expressions
- Function Compositions


## Combinational and Sequential Systems



