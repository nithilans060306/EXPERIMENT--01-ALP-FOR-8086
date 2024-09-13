# EXPERIMENT--01-ALP-FOR-8086
```
Name : Nithilan S
Roll no : 212223240108
Date of experiment : 
```





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
mov AL,53H;
mov BL,24H;
Add AL,BL;
HLT;
```
## Output  
![emu8086_add](https://github.com/user-attachments/assets/ba44c952-3a73-493b-b785-f80594a13569)

## Subtraction   of 8 bit numbers  ALP 
 ```
mov AL,53H;
mov BL,24H;
sub AL,BL;
HLT;
```
## Output  
![emu8086_sub](https://github.com/user-attachments/assets/421ddaf3-ce5f-4e45-b6ca-83ab4fce9ae8)

## Multiplication alp 
```
mov AL,53H;
mov BL,24H;
mul AL,BL;
HLT;
```
 ## Output  
![emu8086_mul](https://github.com/user-attachments/assets/6ab50953-3d06-427c-a186-849fd575c28e)

## Division alp 
```
mov AL,53H;
mov BL,24H;
Div AL,BL;
HLT;
```
## Output  
![emu8086_div](https://github.com/user-attachments/assets/c33fa7b3-e9c5-4ea4-849a-4d565341eac7)


# Programs for Logical  operations
## Logical AND:
```
mov AL,53H;
mov BL,24H;
AND AL,BL;
HLT;
```
## OUTPUT:
![emu8086_and](https://github.com/user-attachments/assets/4ee9b344-fd6a-41e4-8165-c2dc0d86441b)

## Logical OR:
```
mov AL,53H;
mov BL,24H;
OR AL,BL;
HLT;
```
## OUTPUT:
![emu8086_or](https://github.com/user-attachments/assets/639e8316-7cb3-4b08-bd3c-9a8a65de29c8)

## Logical NOT:
```
mov AL,53H;
not AL;
HLT;
```
## OUTPUT:
![emu8086_not](https://github.com/user-attachments/assets/40ad8128-5e5f-4eb9-921c-b6257c40b680)

## Logical XOR:
```
mov AL,53H;
mov BL,24H;
XOR AL,BL;
HLT;
```
## OUTPUT:
![emu8086_xor](https://github.com/user-attachments/assets/53815422-bd5b-4f35-9048-e4e3b3c807db)

## Result :
Thus the program for arithmetic operations and logical operations are complete
