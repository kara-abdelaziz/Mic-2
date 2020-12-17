# Mic-2 processor
In fact, this project is not only about a processor, but contain a whole Von Neumann architecture, with in addition a RAM an input unit and an output unit. The project is a simplistic educative realisation of a whole 8 bit architecture in [Logsim](http://www.cburch.com/logisim/), the processor called Mic-2 was inspired from [Mic-1](https://en.wikipedia.org/wiki/MIC-1) processor whom was described in the popular book [Structured Computer Organization](https://www.amazon.com/Structured-Computer-Organization-Andrew-Tanenbaum/dp/0132916525) by A. Tanenbaum, however the detailed implementation was guided by D.C. Schuurman paper [Step-by-step design and simulation of a simple CPU architecture](https://dl.acm.org/doi/abs/10.1145/2445196.2445296).
This project was first prescribed like a mini project for college students, it was required for students to implement two basic programs, Factorial program and Fibonacci program.
# Mic-2 architecure schematic on Logisim
![Mic-2 architecture](https://github.com/kara-abdelaziz/Mic-2/blob/master/Mic-2.png)
# How to use it
It is very simple to use Mic-2 architecture, all you have to do, is to open the file _Mic-2 Architeture.circ_ with [Logsim](http://www.cburch.com/logisim/) and you have the entire architecture to play with.

You probably want to execute a program on it, to do so go inside the **Memory** bloc, then the **RAM** bloc and load the image of one of the programs found in the directory _/Programs_, you need to load one of the memory image file with the extension **.RAM**.

You can also write your own program in machine language, although you have to use hexadecimal values to represent instructions opcode of 8 bit each (2 hexadecimal digits), to do so you have to use the list of instructions opcode found in the file _/Micro-code/Micro _Prgram ROM.pdf_. You have 16 different instructions, the instructions opcode are black shaded.



