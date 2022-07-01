# SIC-XE-Assembler-
The Objective is to implement a version of two-pass SIC/XE assembler: Pass 1 and Pass 2.
The Assembler implemented here includes all the SIC/XE instructions and supports all four formats 1, 2, 3, 4, addressing modes and program relocation.
It also supports all the machine independent features-
1.	Literals
2.	Symbol Defining Statements 
3.	Expressions
4.	Program Blocks
5.	Control Sections and Program Linking

Input to assembler- Assembler source program using the instruction set of SIC/XE.
Output- Assembler will generate the following files as output-
1.	Pass 1 will generate a Symbol Table.
2.	Pass 1 will also generate Intermediate File for the Pass 2.
3.	Pass 2 will generate a listing file containing the input assembly code and address, block number, object code of each instruction.
4.	Pass 2 will also generate an object program including following type of record: H, D, R, T, M and E types.
5.	An error file is also generated displaying the errors in the assembly program (if any).
6.  A file including symbol table,literal table and table for External definition and External reference is also generated.

Steps to compile and run the program:-
1.compile and run pass2.cpp file using any C++ compiler. 
2.Or using commands g++ pass2.cpp. Then doing ./pass2.cpp to run the program.
2.It will  generate an executable file named pass2.exe in the current directory.
3.Open the exe file and enter the name of the input file of format "ABC.asm". (The input file should be in the same folder as the exectuable file!)
4.An object file along with listing file, error file, intermediate file will be generated for the given input file.
