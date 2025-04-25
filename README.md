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
mov Al,76H
mov Bl,96H
ADD Al,Bl
HAl
```
## Output  

![Screenshot 2025-03-07 131816](https://github.com/user-attachments/assets/1e1067ee-b284-464c-9d07-0dc3d737f5cf)

## Subtraction   of 8 bit numbers  ALP 
```
mov Al,85H
mov Bl,46H
SUB AL,BK
HLT
``` 
## Output  

![Screenshot 2025-03-07 132018](https://github.com/user-attachments/assets/6e775663-02e3-41ef-af9d-63166f7547ef)

## Multiplication alp 
```
mov Al,86H
mov Bl,75H
MUL Bl
HLT
```
 ## Output  

![Screenshot 2025-03-07 135400](https://github.com/user-attachments/assets/3d6fad4f-4416-4f5a-9ea1-6eaaf2034293)

## Division alp 
```
mov Al,42H
mov Bl,87H
DIV Bl
HLT
```
## Output  

![Screenshot 2025-03-07 132406](https://github.com/user-attachments/assets/16daf33e-718d-4504-9b20-343973f1415a)


## AND Of 8 bit numbers ALP
```
mov Al,71H
mov Bl,35H
AND Al,Bl
HLT
```
## Output

![Screenshot 2025-03-07 132606](https://github.com/user-attachments/assets/6100e10a-6140-4858-bbd7-af5fe49ad742)

## OR if 8 bit numbers ALP
```
MOV AL,46H
MOV BL,73H
OR AL,BL
HLT
```
## Output

![Screenshot 2025-03-07 132701](https://github.com/user-attachments/assets/43d4870e-f5d8-47fb-af9c-5140588377ac)

## NOT of 8 bit numbers ALP
```
MOV AL,78H
NOT AL
HLT
```

## Output

![Screenshot 2025-03-07 133217](https://github.com/user-attachments/assets/663c10ab-fd84-4e2e-941d-f7dd5d167e72)

## XOR of 8 bit numbers ALP
```
mov Al,25H
mov Bl,98H
XOR Al,Bl
HLT
```

## Output

![Screenshot 2025-03-07 132805](https://github.com/user-attachments/assets/4d00cd79-1d0f-4e9d-b70c-6a097f8c80e0)


## Result

The execution of ALP on fundamental arithmetic and logical operations is successfully completed.

