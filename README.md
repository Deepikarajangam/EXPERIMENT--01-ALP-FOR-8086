# EXPERIMENT--01-ALP-FOR-8086
## Name :DEEPIKA R
## Roll no:212224040061 
## Date of experiment :27.04.2026





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
MOV AL,27H
MOV BL,15H
ADD AL,BL
MOV [3001H],AL
HLT
```


## Output  
 <img width="806" height="618" alt="image" src="https://github.com/user-attachments/assets/1d5e5358-c423-4563-af07-a541cd12400e" />

## Subtraction   of 8 bit numbers  ALP 
 ```
MOV AL,27H
MOV BL,15H
SUB AL,BL
MOV [3001H],AL
HLT
```
## Output 
<img width="809" height="619" alt="image" src="https://github.com/user-attachments/assets/e08fda10-a296-4838-a278-06cf276ddc83" />

## Multiplication of 8 bit 
```
MOV AL,12H
MOV BL,04H
MUL BL
MOV [3001H],AL
HLT
```
 ## Output  
<img width="800" height="622" alt="image" src="https://github.com/user-attachments/assets/405be02c-e291-4d63-aa8f-877fbc9a2ba2" />


## Division of 8 bit 
```
MOV AX,0024H
MOV BL,06H
DIV BL
MOV [3001H],AL
HLT
```
## Output  
<img width="806" height="621" alt="image" src="https://github.com/user-attachments/assets/ff549c9d-9021-4a21-ae9a-df807fbd28aa" />

## 16 bit
## Addition of 16 bit ALP
```
MOV AX,1234H
MOV BX,1111H
ADD AX,BX
MOV [3001H],AX
HLT
```
## output
<img width="803" height="623" alt="image" src="https://github.com/user-attachments/assets/cd7c860c-6edf-4736-9196-80fe1b44b5fa" />
## Subtraction of 16 bit numbers ALP
```
MOV AX,1234H
MOV BX,0011H
SUB AX,BX
MOV [3001H],AX
HLT
```
## output
<img width="810" height="614" alt="image" src="https://github.com/user-attachments/assets/01027f31-72ef-4055-bb78-f745ec7dc9ff" />
## Multiplication of 16 bit numbers alp
```
MOV AX,0012H
MOV BX,0004H
MUL BX
MOV [3001H],AX
HLT
```
## output
<img width="804" height="630" alt="image" src="https://github.com/user-attachments/assets/2a754612-4484-4e43-9fc3-82856347934b" />
## Division of 16 bit numbers alp
```
MOV DX,0000H
MOV AX,1234H
MOV BX,0002H
DIV BX
MOV [3001H],AX
HLT
```
## output
<img width="804" height="605" alt="image" src="https://github.com/user-attachments/assets/93844b39-91d3-433c-b10d-a4b9420faab0" />
## Programs for logical operations
## 8 bit
## AND (8 bit)
```
MOV AL,27H
MOV BL,15H
AND AL,BL
MOV [3001H],AL
HLT
```
## output
<img width="804" height="620" alt="image" src="https://github.com/user-attachments/assets/b9d8cd71-2b97-4998-a034-e84552c440a2" />

## OR (8 bit)
```
MOV AL,27H
MOV BL,15H
OR AL,BL
MOV [3001H],AL
HLT
```
## output
<img width="806" height="613" alt="image" src="https://github.com/user-attachments/assets/f5370a5c-8397-4688-81e4-e0cf65466274" />

## XOR (8 bit)
```
MOV AL,27H
MOV BL,15H
XOR AL,BL
MOV [3001H],AL
HLT
```
## output
<img width="812" height="618" alt="image" src="https://github.com/user-attachments/assets/f84f88dc-1ebc-43a0-979b-3f252a4426f9" />

## NOT (8 bit)
```
MOV AL,27H
NOT AL
MOV [3001H],AL
HLT
```
## output
<img width="811" height="607" alt="image" src="https://github.com/user-attachments/assets/5d1f2d16-070c-49f7-968b-4ba0bd7329a3" />

## 16 bit
## AND (16 bit)
```
MOV AX,1234H
MOV BX,4321H
AND AX,BX
MOV [3001H],AX
HLT
```
## output
<img width="804" height="620" alt="image" src="https://github.com/user-attachments/assets/c7fd1ec3-516a-4f70-9172-6e3653d8c4bd" />

## OR (16 bit)
```
MOV AX,1234H
MOV BX,4321H
OR AX,BX
MOV [3001H],AX
HLT
```
## output
<img width="806" height="615" alt="image" src="https://github.com/user-attachments/assets/76431276-3dea-4fc9-85df-dbbb441c1997" />

## XOR (16 bit)
```
MOV AX,1234H
MOV BX,4321H
XOR AX,BX
MOV [3001H],AX
HLT
```
## output
<img width="835" height="605" alt="image" src="https://github.com/user-attachments/assets/6334c9af-aa2b-430c-a351-1db14b855f84" />

## NOT (16 bit)
```
MOV AX,1234H
NOT AX
MOV [3001H],AX
HLT

```

## output
<img width="798" height="614" alt="image" src="https://github.com/user-attachments/assets/f9d29cd6-a633-49d0-b5df-ae8ee77c63c5" />



## Result :
 The execution of ALP on fundamental arithmetic and logical operations is successful.








