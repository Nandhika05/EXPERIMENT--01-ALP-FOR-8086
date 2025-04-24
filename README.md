# EXPERIMENT--01-ALP-FOR-8086
Name : Nandhika P

Roll no : 212223040125

Date of experiment : 20-04-2025

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
MOV AX,1400H 
MOV BX,1400H
ADD AX,BX
ret
```
## Output  

 ![Screenshot 2025-04-24 203654](https://github.com/user-attachments/assets/3a15d71a-df89-457a-be3f-d9f061e5d506)

## Subtraction   of 8 bit numbers  ALP 
```
org 100h 
MOV AX,[5000h] 
MOV BX,[5002h]
SUB AX,BX
ret
``` 
## Output  

![Screenshot 2025-04-24 203725](https://github.com/user-attachments/assets/156f6944-2492-4804-9b80-a8d0858f37c8)

## Multiplication alp 
```
org 100h 
MOV BX,1234H
MOV CX,123H 
MOV AX,CX
mul BX
ret
```
 ## Output  

![Screenshot 2025-04-24 203759](https://github.com/user-attachments/assets/71a30e5a-10bc-4bf2-a4c4-c5be2c5e894d)

## Division alp 
```
org 100h 
MOV BX,50H
MOV AX,BX
MOV CX,05H
DIV CX
ret
```
## Output  

![Screenshot 2025-04-24 203816](https://github.com/user-attachments/assets/5780cc31-c476-4e9b-98e1-6d6b17b7fb9e)

## AND Of 8 bit numbers ALP
```
assembly
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```
## Output

![Screenshot 2025-04-24 203846](https://github.com/user-attachments/assets/b0456f54-52a9-4ecf-b5d7-5056c420e296)

## OR if 8 bit numbers ALP
```
assembly
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT
```
## Output

![Screenshot 2025-04-24 203907](https://github.com/user-attachments/assets/62dc5f12-fec8-4b5b-a9d8-ade093ba301f)


## NOT of 8 bit numbers ALP
```
assembly
MOV AL,65H
NOT AL
HLT
```

## Output

![Screenshot 2025-04-24 203927](https://github.com/user-attachments/assets/bfe162d2-e5f0-4cde-bf47-492576af5a06)

## XOR of 8 bit numbers ALP
```
assembly
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
```

## Output

![Screenshot 2025-04-24 203943](https://github.com/user-attachments/assets/cdfafbb5-77fb-455b-9e03-0dad8032a922)

## Result

The execution of ALP on fundamental arithmetic and logical operations is successfully completed.

