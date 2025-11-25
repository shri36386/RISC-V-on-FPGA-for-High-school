# RISC-V ON FPGA FOR HIGH SCHOOL
<details>
  <summary><h2>INTRODUCTION TO RISC-V</h2> </summary>
RISCV

  * RISC stands for Reduced Instruction Set Computer.
  * RISC-V is a open standard Instruction Set Architecture (ISA) used for designing computer processors.
  * A CPU requires instructions to function. RISC-V is a set of basic nstructions a processor can understand.

ISA

* It is the formal interface between a computer software and Hardware. To run a software application on any hardware, there must exist a way to communicate between the two. The ISA makes this communication possible.
* It defines the set of machine instructions a processor can excecute along with rules for -
  1. How to operate on data
  2. How to access memory
  3. How to manage registers
  4. How to control program flow.

WHY DO WE REQUIRE RISC-V ISA

* The software application we run are programmed in the C or C++ languages, languages with are high-level and are easily understandable by humans.However, they cannot be understood by computers.
* To implement these software programmes on a hardware, we must convert it to assembly language. Assembly language is a low-level human readable version of machine code. RISC-V assembly is the assembly that follows the RISC-V ISA rules.

HDL AND RTL

* Another thing between the RISC-V Architecture and the layout is HDL.
* A Processor is hardware. All instrutions need to be excecuted by circuits in Processor
* HDL (Hardware Description Language) is a programming language but for the hardware. We use HDL to explain how a circuit behaves.
* RTL (Register transfer level) is a way of describing circuits in HDL. It focuses on how the data moves between registers and what operations happen on the data.

FLOW FROM SOFTWARE TO HARDWARE
<img width="766" height="313" alt="image" src="https://github.com/user-attachments/assets/e0103b1f-fedf-4b8b-9c34-767d37843ceb" />

STEP-BY-STEP FLOW -

* Software is programmed in the C or C ++ Programming languages.
* The compiler converts the C/C++ language into RISC-V Assembly language.
* The Assembler assembles this into machine code (in hexadecimal formal).
* The machine code runs on the Hardware.

  </details>

