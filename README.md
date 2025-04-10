# EXPERIMENT--01-ALP-FOR-8086
Name : VIGNESH V

Roll no : 21223110062

Date of experiment :11/03/2025





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
MOV AX, 1125H
MOV BX, 2345H
ADD AX,BX
MOV [6000H],AX

```


## Output  
 ![add](https://github.com/user-attachments/assets/4323f43d-9a32-4856-a4cb-03f912265c34)

## Subtraction   of 8 bit numbers  ALP 
```
MOV AX,[5000H]
MOV BX,[5002H]
SUB AX,BX
MOV [6010H],AX

```
## Output  
![sub](https://github.com/user-attachments/assets/cd0fefcd-49e6-41a2-b9ef-45df441cd876)

## Multiplication alp 
```
MOV BX,4444H
MOV AX,BX
MOV CX,3333H           
MOV DX,CX
MUL DX
MOV [6020H],AX
```
 ## Output  
 
![mul](https://github.com/user-attachments/assets/aee038bf-6570-44a6-84a5-96845d5aa742)

## Division alp 
```
MOV AL,70H
MOV BL,10H
DIV BL
MOV [6030h],AL
```
## Output  
![div](https://github.com/user-attachments/assets/6417f5eb-775d-4ef3-96b9-ec3716e9a3e9)

## Programs For Logical Operation
## AND Operation of 8 bit ALP
```
org 100h

MOV AX,125Bh
MOV BX,6F67h
AND AX,BX
MOV [6000h],CX
ret
```
## Output:
![image](https://github.com/user-attachments/assets/63c09a5d-ba61-4595-85de-88f99e6572cd)

## OR Operation of 8 bit ALP
```
org 100h

MOV AX,[5000h]
MOV BX,[5002h]
OR AX,BX  
MOV [6010h],AX
ret
```
## Output:
![image](https://github.com/user-attachments/assets/46525010-b313-403f-8e50-56f15aa70052)

## NOT Operation of 8 bit ALP
```
org 100h
MOV BX,4444h
NOT BX
MOV [6020h],AX
ret
```
## Output:
![image](https://github.com/user-attachments/assets/e4ba9493-303d-4a14-978f-b7f126ecff79)

## XOR Operation of 8 bit ALP
```
org 100h          
MOV AX,702H
MOV BL,10H
XOR [6030h],AL
HLT
ret
```
## Output
![image](https://github.com/user-attachments/assets/f3cd500a-f023-4988-a94d-339763a6f15d)

## Result :
Hence,The logiacl opertaion and arithmetic operation has been executed successfully.










