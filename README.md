# RISC-V ON FPGA FOR HIGH SCHOOL
<details>
  <summary><h2>CONTENTS OF THE COURSE</h2> </summary>

CONTENTS OF THE COURSE

Integer addition, mul/div instructions 

* Pseudo Instructions
* Base Integer instructions RV64I
* Multiply extension RV64M

Floating point addition, mul/div instructions

* Single and double precision
* Floating point extension RV64F or RV64D

Other concepts 

* Application binary interface (ABI)
* Memory allocation and stack pointer.
* Integer representation.
  </details>

<details>
  <summary><h2>INTRODUCTION TO RISC-V</h2> </summary>
RISCV

  * RISC (Reduced Instruction Set Computer) refers to a processor design philosophy that uses a streamlined set of simple, efficient instructions. This approach enables faster execution, lower power consumption, and simplified hardware implementation.
  * RISC-V is an open, extensible, and freely available Instruction Set Architecture (ISA) that provides a standardized foundation for designing a wide range of computer processors. Its openness encourages innovation, collaboration, and customization across both academic and industrial applications.
  * A CPU relies on instructions to perform operations, and RISC-V defines the fundamental set of instructions that a processor can interpret and execute. By specifying these core operations, RISC-V ensures consistency, interoperability, and flexibility in processor design.

ISA

* An Instruction Set Architecture (ISA) serves as the formal interface between computer software and hardware. To execute any software application on a given hardware platform, there must be a well-defined method for communication between the two. The ISA provides this bridge by specifying how software instructions translate into hardware-level operations.
* The ISA defines the complete set of machine instructions a processor can execute, along with the rules governing how these instructions interact with system resources. These rules cover several key aspects of processor behavior, including:
  1. Data operations – specifying how arithmetic, logical, and other computations are performed.
  2. Memory access mechanisms – defining how data is read from and written to memory.
  3. Register management – outlining how the processor utilizes and manipulates its internal registers.
  4. Program flow control – detailing how instructions are sequenced, including branching, jumping, and handling control structures.

WHY DO WE REQUIRE RISC-V ISA

* Software applications are typically written in high-level programming languages such as C or C++. These languages are designed to be readable and understandable by humans, but they cannot be directly interpreted by computer hardware, which only understands low-level machine instructions.
* To execute these programs on hardware, the high-level code must be translated into assembly language. Assembly language is a low-level, human-readable representation of machine code that corresponds closely to the instructions a processor can execute. RISC-V assembly specifically refers to the assembly language that adheres to the rules and instruction formats defined by the RISC-V ISA.

HDL AND RTL

* Between the RISC-V architecture and the physical hardware layout lies the Hardware Description Language (HDL) stage. This stage serves as the bridge between the abstract ISA and the actual circuit implementation.
* A processor is a hardware component, and all instructions must ultimately be executed by physical circuits within the processor. Translating architectural concepts into functioning circuitry requires a precise method for describing hardware behavior.
* HDL (Hardware Description Language) is a specialized programming language used to model and describe electronic circuits. It allows designers to specify how hardware components behave, interact, and respond to signals, enabling simulation, verification, and synthesis of digital systems.
* RTL (Register Transfer Level) is a design abstraction used within HDL to describe hardware at the level of data flow between registers and the logical operations performed on that data. It provides a structured way to represent circuit behavior before converting it into detailed gate-level or physical layouts.

FLOW FROM SOFTWARE TO HARDWARE
<img width="766" height="313" alt="image" src="https://github.com/user-attachments/assets/e0103b1f-fedf-4b8b-9c34-767d37843ceb" />

STEP-BY-STEP FLOW -

* Software applications are typically written in high-level programming languages such as C or C++. These languages are designed to be readable and manageable for developers but cannot be executed directly by hardware.
* A compiler translates the C/C++ source code into RISC-V assembly language. This assembly code expresses the program using the instruction set defined by the RISC-V ISA, making it compatible with RISC-V processors.
* An assembler then converts the assembly code into machine code, typically represented in hexadecimal format. This machine code consists of binary instructions that the processor can interpret and execute.
* The machine code is finally executed on the hardware, where the processor carries out each instruction through its underlying circuits.

  </details>

<details>
  <summary><h2>LABWORK FOR RISC-V SOFTWARE TOOLCHAIN</h2> </summary>

  
  </details>

<details>
  <summary><h2>INTEGER REPRESENTATION</h2> </summary>

Human's understand the decimal number system. However computers work on Binary number system.

Let have a number in the decimal number system -

(17,446,744,073,708,551,615)

In binary number system it will be -

  </details>  
