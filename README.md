# SIC-XE-ASSEMBLER
What is an assembler: Assembler is a program that converts programs written in low-level assembly language into relocatable machine code. It is done by evaluating the mnemonics in the operation field and finding the corresponding value and literal to produce machine code. There are assemblers that do this work in a single pass- we can call them single pass assemblers. Otherwise, assemblers do this in multiple scans- and such assemblers are called multi-pass assemblers.

Here I am creating a two-pass assembler using in CPP.

Two-pass assembler: A two-pass assembler converts assembly language code to machine code in two passes. In the first pass the program will output an intermediate file and symbol table. This intermediate file will be input to the pass 2 program. The output of pass2 will be a listing file containing the input assembly code and address, block number, and object code of each instruction. Also pass 2 will generate an object program including following type of record: H,D, R,T, M and E types. An error file is also generated if there is any error in the assembly program. A file containing symbol table, literal table, and table for external definition and external reference is also generated.

Features: The two pass assembler we implemented includes all SIC/XE instructions, supports all 4 formats: format1,2,3 and 4, addressing modes and program relocations. It supports machine-independent features like 1.Literals 2. Symbol defining statements 3. Expressions 4. Program blocks
