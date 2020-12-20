# Mic-2 processor
In fact, this project is not only about a processor, but contain a whole Von Neumann architecture, with in addition a RAM an input unit and an output unit. The project is a simplistic educative realisation of a whole 8 bit architecture in [Logsim](http://www.cburch.com/logisim/), the processor called Mic-2 was inspired from [Mic-1](https://en.wikipedia.org/wiki/MIC-1) processor whom was described in the popular book [Structured Computer Organization](https://www.amazon.com/Structured-Computer-Organization-Andrew-Tanenbaum/dp/0132916525) by A. Tanenbaum, however the detailed implementation was guided by D.C. Schuurman paper [Step-by-step design and simulation of a simple CPU architecture](https://dl.acm.org/doi/abs/10.1145/2445196.2445296).
This project was first prescribed like a mini project for college students, it was required for students to implement two basic programs, Factorial program and Fibonacci program.
# Mic-2 architecure schematic on Logisim
![Mic-2 architecture](https://github.com/kara-abdelaziz/Mic-2/blob/master/Mic-2.png)
# How to use it
It is very simple to use Mic-2 architecture, all you have to do, is to open the file _Mic-2 Architeture.circ_ with [Logsim](http://www.cburch.com/logisim/) and you have the entire architecture to play with.

You probably want to execute a program on it, to do so go inside the **Memory** bloc, then the **RAM** bloc and load the image of one of the programs found in the directory _/Programs_, you need to load one of the memory image file with the extension **.RAM**.

You can also write your own program in machine language, although you have to use hexadecimal values to represent instructions opcode of 8 bit each (2 hexadecimal digits), to do so you have to use the list of instructions opcode found in the file _/Micro-code/Micro _Prgram ROM.pdf_. You have 16 different instructions, the instructions opcode are black shaded.
# Files and directories description
1. Mic-2 Architeture.circ : the main circuit, contains all the components, sufficient to run all the architecture.
2. Mic-2.png : the image above.
3. README.md : this text.
4. Micro-code : directory that contains 3 files related to the micro-program and the op-codes of all instructions.
  1. MicroProgram.ROM : the ROM to be used inside the Command and Control Unit (UCC), exactly within MP-ROM, it contains the micro-instructions.
  2. Micro Prgram ROM.pdf : this table contains all the micro-instructions and their interpretation, the op-codes for instructions are black shaded.
  3. Micro Prgram ROM.odt : it's the source of the pdf version above, it is only meant to allow its modification by libre office when adding more instructions.
5. Programs : directory that contains 3 elementary programs to use within Mic-2; factorial, fibonacci and 2 integers multiplication.
5.1. Factorial.RAM : the binary file of the factorial program to put in the RAM.
5.2. Factorial.txt : the assembler code of the factorial program, its allow understanding the generation of the binary version of the program.
5.3. Fibonacci.RAM : the binary file of the fibonacci program to put in the RAM.
5.4. Fibonacci.txt : the assembler code of the factorial program, its allow understanding the generation of the binary version of the program.
5.5. Multiplication.RAM : the binary file of the multiplication program to put in the RAM.
5.6. Multiplication.txt : the assembler code of the multiplication program, its allow understanding the generation of the binary version of the program.
6. Project statement : directory containing text files for the description in french language of the processor and the architecture working.
6.1. mini-projet.pdf : contains the project statement for students on how to implement Mic-2 (in french language).
6.2. mini-projet.pdf : same as the PDF version above, to be open with libre office.
7. 

## Notes:
- Multiple seven segment displays were added to the datapath in the simulation for debugging purposes, allowing the user to see the evolution of the information through the processor.

## Website:
- [www.el-kalam.com](https://www.el-kalam.com/): my personal website, contains this project and others.
