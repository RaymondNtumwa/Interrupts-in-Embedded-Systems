# Interrupts-in-Embedded-Systems

## Overview

This project contains a Beamer presentation on **Interrupts in Embedded Systems**.  
The slides explain the concept of interrupts, their types, internal working mechanisms, timer interrupts, vector tables, performance considerations, and real-world applications.

The presentation also includes a register-level AVR code example to demonstrate how interrupts are configured and handled in embedded systems.

---

## Topics Covered

- Definition of Interrupts
- Importance of Interrupts in Embedded Systems
- Types of Interrupts (Hardware & Software)
- Interrupt Flow Mechanism
- Timer Interrupt Working Principle
- Interrupt Vector Table
- Performance Concepts:
  - Interrupt Latency
  - Masking
  - NVIC (ARM)
  - Tail-Chaining
- Register-Level AVR Interrupt Example
- Real-World Applications

---

## Technologies Used

- LaTeX (Beamer Class)
- TikZ (for diagrams)
- Listings package (for C code formatting)
- Madrid Beamer Theme

---

## Compilation Instructions

This project can be compiled using:

- **Overleaf (Recommended)**
- Or locally using:

```bash
pdflatex main.tex
