#  [Nand2tetris](https://www.nand2tetris.org/)
Nand to Tetris is a journey of discovery, synthesizing key topics in applied CS in one unified framework. This is done constructively, by building a general-purpose computer system from the ground up. We’ll explore key ideas and techniques used in the design of modern hardware and software systems, and discuss major trade-offs and future trends. As we go through this journey, you will gain many cross-section views of the computing field, from the details of bare bone switching circuits to the compilation of high-level software abstractions. We will also provide a historical perspective, narrating the key people, circumstances and innovations that paved the way to the digital computer.

# What I learn

## Week 1 - Boolean logic: Basic concepts in gate logic and Boolean algebra

Used HDL to build a set of elementary logic gates (And, Or, Not, Mux, Xor, Mux, Dmux) from primitive Nand gates, and extend it to multiple bit version such as n-bit gate(And16, Or16) and multiple way gate(Or8way, Mux8Way16)

## Week 2 - Boolean arithmetic: logic gates for realizing arithmetic operations on bitwise representations. 

Built a family of adder chips, culminating in the construction of an Arithmetic-Logic Unit and built a ALU, using the logic gates built in project 1.

## Week 3 -  Memory and State withData flip-flops time-dependent gate

Built a memory hierarchy, from single-bit cells to registers to RAM units of arbitrary sizes based on time-dependent gates called flip-flops which can be used to maintain state and realize memory units.

## Week 4 -  Assembly and Handle input / output devices (a screen and a keyboard) using memory-resident bitmap

Machine language: This is the delicate software-hardware interface where high-level programs are ultimately reduced to concrete binary codes committed to silicon. We’ll introduce an instruction set and an abstract computer architecture, and learn how to write low-level programs in this framework. We’ll also learn how to handle input / output devices (a screen and a keyboard) using memory-resident bitmaps. In project 4 you will write some low-level interactive programs in assembly language and execute them on a supplied CPU emulator, running on your PC.

## Week 5 -  

Computer architecture: We’ll describe the stored program concept, the fetch-execute cycle, a general computing framework that informs the design of all computer architectures, and the microchip revolution. We will then show how the chips built in weeks 1-3 can be integrated into a computer platform capable of running programs written in the instruction set introduced in week 4. In project 5 you will build this computer, known as Hack, and use it to run the programs you wrote in project 4.

## Week 6 -  

Assembler: In 1843, Ada Lovelace showed how symbolic instructions can liberate programming from the obscure tyranny of binary codes. We will learn how to translate the symbolic instructions introduced in week 4 into the binary micro-codes understood by the computer built in week 5. In order to develop this translator, known as assembler, we will learn how to perform parsing, code generation, and symbol resolution. This will set the stage for project 6, in which you will build this assembler, using a high-level language of your choice. From Nand to Tetris • Shimon Schocken • 2021 • www.nand2tetris.org Part II: Software Using the computer built in Part I as a point of departure, we will build a multi-tier software hierarchy consisting of a virtual machine, a compiler for a simple java-like programming language, and a basic operating system. Acting as the systems architects, we’ll provide elaborate implementation guidelines, scaffolding, and APIs.

## Week 7 -  

Virtual machine I: Modern compilers typically translate high-level programs into an intermediate code designed to run on an abstract virtual machine. Following a discussion of pushdown automata and stack processing, we’ll discuss the role of virtual machines in software architectures like Java, Python, and .NET. We will then present a simple VM language, modeled after Java’s JVM. In project 7 you will write a JRE-like program that translates the push/pop and arithmetic VM commands into assembly code, designed to run on the Hack computer built in part I of the course.

## Week 8 -  

Virtual machine II: We’ll discuss two critically important programming abstractions –
branching and subroutines – and show how they can be realized on our virtual machine.
In particular, we’ll discuss algorithms for realizing goto and function-call-and-return
commands on a global stack. In project 8 you will extend the basic translator built in
project 7 into a full-blown VM translator. This translator will become the backend of
compilers that translate high-level programs into VM code (similar to Bytecode).

## Week 9 -  

High Level Language: We’ll introduce Jack – a simple, high-level, object-based, java-
like language. We’ll discuss language design issues and trade-offs, and how Jack can be
realized over the Hack platform. In project 9 you will select a computer game idea, and
implement it in Jack. It will be thrilling to see this game running on the computer that
you’ve built in Part I of the course. You will develop this program using executable
versions of the compiler and OS that we now turn to describe.

## Week 10 -  

Compiler I: We’ll discuss context-free grammars and recursive parsing algorithms, and
guide how they can be used for building a syntax analyzer (tokenizer and parser) for the
Jack language presented in week 9. In project 10 you will implement this analyzer,
using a proposed software architecture and API.

## Week 11 -  


Compiler II: We’ll discuss how to realize high-level programming abstractions
(classes, methods, statements, expressions, objects, etc.) by generating VM code for the
virtual machine built in weeks 7-8. In project 11 you will morph the syntax analyzer
built in week 10 into a full-scale compiler that translates Jack programs into VM code.

## Week 12 -  


Operating system: The OS is designed to close gaps between Jack and Hack. We’ll
discuss classical OS algorithms for managing memory, realizing mathematical
operations, rendering graphics, handling strings, and more – and a bootstrapping
technique for realizing these services efficiently on the Hack platform. In project 12 you
will implement this OS in Jack, in the spirit of how Unix was implemented in C.