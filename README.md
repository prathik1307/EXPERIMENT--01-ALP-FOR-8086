# EXPERIMENT--01-ALP-FOR-8086

  ### Name :PRATHIKSHA R
 ### Roll no :212224040244
 ### Date of experiment :30.01.2026





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
mov al,75h
mov bl,66h
add al,bl 
hlt
```
## Output
![ss2pmcadd](https://github.com/user-attachments/assets/2051293f-2b3a-483c-9595-100e363a6390)


 
## Subtraction   of 8 bit numbers  ALP 
```
mov al,75h
mov bl,66h
sub al,bl 
hlt
```
 ## Output
 ![ss2pmcsub](https://github.com/user-attachments/assets/a48466a2-3f70-4327-880b-73a3f794b5c2)


## Multiplication alp 
```
mov ax,0075h
mov bx,0066h
mul ax
hlt
```
 ## Output  
<img width="1919" height="1132" alt="Screenshot 2026-02-04 112158" src="https://github.com/user-attachments/assets/40a439c6-d179-493c-a4d8-e9a1e238b14b" />


## Division alp 
```
mov ax,0075h
mov bx,0066h
div ax 
hlt
```


## Output  
<img width="1919" height="1139" alt="image" src="https://github.com/user-attachments/assets/67c749bc-20c5-4420-841a-866801690015" />



## And of 8 bit numbers ALP
```
mov al,75h
mov bl,66h
and al,bl 
hlt
```
## output
![Screenshot 2025-03-10 084528](https://github.com/user-attachments/assets/003815f9-ef08-45de-b5b0-3bb8e3c6c73a)

## Or of 8 bit numbers ALP
```
mov al,75h
mov bl,66h
or al,bl 
hlt
```

## output
![Screenshot 2025-03-10 084556](https://github.com/user-attachments/assets/88e9db92-d89d-4e3f-9c8f-265ee55c304e)

## Not of 8 bit numbers ALP
```
mov al,75h
mov bl,66h
not al,
hlt
```

## output
![Screenshot 2025-03-10 084649](https://github.com/user-attachments/assets/80a8119d-88d6-48e6-9369-9273f0c90e9c)

## xor of 8 bit numbers ALP
```
mov al,75h
mov bl,66h
xor al,
hlt
```

## output
![Screenshot 2025-03-10 085416](https://github.com/user-attachments/assets/8edaa50d-6a2a-47a0-9bc5-2ba152d57c49)






## Result :
Thus the program has been successfully completed
 







