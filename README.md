# EXPERIMENT--01-ALP-FOR-8086
### Name : NARESH PS
### Roll no : 212223040127
### Date of experiment : 27-07-2026





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








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
org 100h

mov ax,[1100h]

mov bx,[1102h]
add ax,bx
mov 1200h,ax
hlt
```
## Output

<img width="1895" height="995" alt="image" src="https://github.com/user-attachments/assets/4e12bbd9-2403-4a9f-9ab3-160757912f96" />

 
## Subtraction   of 8 bit numbers  ALP 
```
org 100h

mov ax,[1100h]

mov bx,[1102h]
sub ax,bx
mov 1200h,ax
hlt
```
## Output  
<img width="1919" height="1022" alt="image" src="https://github.com/user-attachments/assets/2dfc9c83-fd00-4da8-9376-7e3937a4d596" />

## Multiplication alp 
```
org 100h

mov ax,[1100h]
mov bx,[1102h]
mul bx
mov 1200h,ax
mov 1202h,dx
hlt
```
## Output
<img width="1901" height="1025" alt="image" src="https://github.com/user-attachments/assets/fa91a6b2-1cb5-4e3b-a701-16ed40da2160" />

## Division alp 
```
org 100h

mov ax,[1100h]
mov bx,[1102h]
div bx
mov 1200h,ax
mov 1202h,dx
hlt
```
## Output  
<img width="1895" height="1017" alt="image" src="https://github.com/user-attachments/assets/aec998b5-c0c0-44f6-9625-2cc78aba9884" />

## AND for 8 bit alp:
```
org 100h

mov al,[1100h]

mov bl,[1102h]
AND al,bl
mov [1200h],al
hlt

ret
```
## Output:
<img width="1759" height="1123" alt="Screenshot 2026-02-11 230740" src="https://github.com/user-attachments/assets/68b4aa8f-e012-4c42-aad3-c2a89f124d35" />

## OR for 8 bit alp:
```
org 100h

mov al,[1100h]

mov bl,[1102h]
OR al,bl
mov [1200h],al
hlt
```
## Output:
<img width="1651" height="1090" alt="Screenshot 2026-02-11 231834" src="https://github.com/user-attachments/assets/70cecf81-14e8-4a81-a6d9-b4bd7d7d5399" />

## NOT for 8 bit alp:
```
org 100h
mov al,[1100h]
NOT al
mov [1200h],al
hlt
```
## Output:
<img width="1916" height="1174" alt="Screenshot 2026-02-11 233029" src="https://github.com/user-attachments/assets/cf80301b-cf5e-49dc-a567-807db753a0b4" />

## XNOR for 8 bit alp:
```
org 100h

mov al,[1100h]

mov bl,[1102h]
XOR al,bl
not al
mov [1200h],al
hlt
```
## Output:
<img width="1921" height="1190" alt="Screenshot 2026-02-11 234416" src="https://github.com/user-attachments/assets/ce3e8e3c-aa97-4d51-bd44-cff827ebfa51" />

## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed. 








