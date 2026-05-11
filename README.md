# 8086 Assembly Language Problem Solutions

A collection of 8086 Assembly language programs for microprocessor and assembly-language practice. The repository includes solved exercises for arithmetic, input/output, number conversion, overflow detection, string printing, Fibonacci generation, and exam-style problems.

## Contents

- `hello_world.asm` - Basic DOS interrupt output example.
- `solution/` - Focused solutions such as 16-bit addition, binary/decimal conversion, Fibonacci, square root, exchange, and string printing.
- `micro/` - Microprocessor lab and midterm-style assembly problems.
- `question1.jpg`, `question2.jpg`, `question3.jpg` - Problem statement images.

## Requirements

Use any DOS-compatible 8086 assembler/emulator, for example:

- EMU8086
- MASM/TASM in DOSBox
- Other 16-bit x86 educational simulators

## Running a Program

Typical MASM/TASM workflow:

```bash
tasm filename.asm
tlink filename.obj
filename.exe
```

For EMU8086, open the `.asm` file in the IDE, compile, and run it in the emulator.

## Learning Goals

- Practice DOS interrupt-based input and output.
- Understand register-level arithmetic and data movement.
- Convert numbers between decimal and binary representations.
- Detect signed and unsigned overflow.
- Build confidence with `.data`, `.code`, procedures, and program termination.
