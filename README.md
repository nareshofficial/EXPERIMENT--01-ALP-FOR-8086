# EXPERIMENT--01-ALP-FOR-8086




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

## Addition  of 16 bit ALP 

 ```

mov Ax, 5782H
mov Bx, 23ABH
add Ax,Bx
mov [3001H],Ax
hlt

```


## Output  

<img width="1640" height="827" alt="image" src="https://github.com/user-attachments/assets/79bdc80a-48e2-450f-958d-13c1966872b6" />


 
## Subtraction   of 16 bit numbers  ALP 

 ```


mov Ax, 5782H
mov Bx, 23ABH
sub Ax,Bx
mov [3003H],Ax
hlt


```

## Output



<img width="1643" height="837" alt="image" src="https://github.com/user-attachments/assets/4e48b92b-b9d6-4a83-9f45-84f439ffc550" />

## Multiplication  of 16 bit numbers  ALP 


```

mov Ax, 5782H
mov Bx, 23ABH
mul Bx
mov [3005H],Ax 
mov [3007H], Dx
hlt

```

 ## Output  

<img width="1635" height="821" alt="image" src="https://github.com/user-attachments/assets/d4136850-9102-4558-b8ee-28f2e03c9dbd" />


## Division  of 16 bit numbers  ALP 

```
mov Ax,5782H
mov Bx,23ABH
div Bx
mov [3009H],Ax
mov [300BH],Dx
hlt

```


## Output  

<img width="1640" height="808" alt="image" src="https://github.com/user-attachments/assets/4e59e057-ea95-4c4a-b867-eb93809546f7" />


## AND of 16 bit numbers ALP
```

mov Ax,5782H
mov Bx,23ABH
and Ax,Bx
mov [4001H],Ax
hlt

```
## OUTPUT

<img width="1216" height="626" alt="image" src="https://github.com/user-attachments/assets/7cb3a4cf-5c04-4794-9b39-e742f7fd894d" />



## OR of 16 bit numbers ALP

```

mov Ax,5782H
mov Bx,23ABH
or Ax,Bx
mov [4003H],Ax
hlt

```

## OUTPUT


<img width="1427" height="703" alt="image" src="https://github.com/user-attachments/assets/04e9b7ce-65d2-462e-b6a4-baf0c262adba" />

## NOT of 16 bit number ALP

```

mov Ax,5782H
not Ax
mov [4005H],Ax
hlt

```

## OUTPUT 

<img width="1427" height="718" alt="image" src="https://github.com/user-attachments/assets/25a8428d-f923-48d9-85e3-68f5d591b568" />


## XOR of 16 bit numbers ALP

```

mov Ax,5782H
mov Bx,23ABH
xor Ax,Bx
mov [4007H],Ax
hlt
```

## OUTPUT

<img width="1431" height="726" alt="image" src="https://github.com/user-attachments/assets/b0e240fc-c2e0-4403-ab84-e59785a9699e" />

## Result :
 
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.







