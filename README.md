# EXPERIMENT--01-ALP-FOR-8086
### Name               : Shivaram M.
### Roll no            : 212223040195
### Date of experiment : 22/04/2025





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
Mov AL,74H
MOV BL,69H
ADD AL,BL
HLT
```

## Output  
 ![WhatsApp Image 2025-04-22 at 13 23 25](https://github.com/user-attachments/assets/3acac823-a4da-49b3-8be3-0e36dbec6792)

## Subtraction   of 8 bit numbers  ALP 
```
Mov AL,74H
MOV BL,69H
SUB AL,BL
HLT
```

## Output  
![WhatsApp Image 2025-04-22 at 13 23 22](https://github.com/user-attachments/assets/e1f95549-763c-40eb-a94a-22453f5f6252)

## Multiplication alp 
```
org 100h
Mov AL,74H
MOV BL,69H
MUL BL
HLT
ret
```

## Output  
![WhatsApp Image 2025-04-22 at 13 23 23 (1)](https://github.com/user-attachments/assets/0ef70a4d-0338-4e38-914f-e2fd78c1e670)

## Division alp 
```
MOV AL,68H
MOV BL,18H
DIV BL
HLT
```

## Output  
![WhatsApp Image 2025-04-22 at 13 23 24](https://github.com/user-attachments/assets/4abd9685-7e75-4ab4-b662-d10a2ae42fe9)

## And of 8 bit numbers ALP
```
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```

## Output 
![WhatsApp Image 2025-04-22 at 13 23 24 (1)](https://github.com/user-attachments/assets/acba50b6-a65e-4e9b-958f-f0671a950505)

## OR of 8 bit numbers ALP
```
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT
```

## Output
![WhatsApp Image 2025-04-22 at 13 23 22 (1)](https://github.com/user-attachments/assets/bc094c9b-6ce3-4161-820b-f1a1388bd3d3)

## NOT of 8 bit number ALP
```
MOV AL,65H
NOT AL
HLT
```

## Output
![WhatsApp Image 2025-04-22 at 13 23 23](https://github.com/user-attachments/assets/527f8dfb-e43d-4705-87a8-6cd6f8602be3)

## XOR of 8 bit number ALP
```
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
```

## Output
![WhatsApp Image 2025-04-22 at 13 23 21](https://github.com/user-attachments/assets/fbfb4b4a-6b75-43c6-a1f2-081057dac381)

## Result :
 
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
