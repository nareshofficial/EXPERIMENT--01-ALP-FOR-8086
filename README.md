# EXPERIMENT--01-ALP-FOR-8086
# Name : NARESH PS

# Roll no : 212223040127






## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)


## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
org 100h

MOV CL,00H
MOV AL,[4200H]
MOV BL,[4201H]
ADD AL,BL
JNC L
INC CL
L:MOV [4202H],AL
MOV [4203H],CL

ret
```






## Output  
![Screenshot (755)](https://github.com/user-attachments/assets/d528e05c-e16a-481d-ab30-4d82798a6c21)


## Multiplication alp 
```
org 100h

MOV AL,[4400H]
MOV BL,[4401H]
MUL BL
MOV [4402H],AL
MOV [4403H],AH

ret
```
 ## Output  
![Screenshot (757)](https://github.com/user-attachments/assets/e8f25332-db6c-4f26-9b76-71f7eee0a9b7)


## Division alp
```
org 100h
MOV AL,[4500H]
MOV BL,[4501H]
DIV BL
MOV [4502H],AX
ret

```
## Output  
![Screenshot (758)](https://github.com/user-attachments/assets/3bb46e6e-cd97-4727-aba0-2c92673df97f)

## Logical Operation
```
org 100h
MOV AX,0A32H
MOV BX,0B31H
MOV SI,5000H
OR AX,BX
MOV [SI],AX
MOV AX,0A32H
AND AX,BX
MOV [SI+2],AX
MOV AX,0A32H
XOR AX,BX
MOV [SI+4],AX
MOV AX,0A32H
NOT AX
MOV [SI+6],AX
ret
```
## Output
![Screenshot (768)](https://github.com/user-attachments/assets/bd5a96c9-c995-4b2d-a864-0439b6c91157)


## Result :
Thus , the fundamental Arithmetic and Logical operations are excuted successfully.
 













