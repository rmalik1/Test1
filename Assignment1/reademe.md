## Executive Summary 
This assignment provides detailes information on how to install MySQL ( Server and Workbench) on personal machines and how to use MYSQL Workbench to start and stop a MySQL server and to enter and execute SQL Statements.The Lab also provides detailed knowledge for coding SLEECT statements using :
+ serveral functions like LEFT,DATE ,Format and Round etc
+ using WHERE Clause


is to review various Hardware components and their functions. It provides detailed information about the functioning of a CPU, Logic gates and Circuits and the role of IEEE in ensuring compliance with ethics for device and AI designs. The lab also discusses the Data Representation in computing and disusses the conversion of numbers to binary, hexadecimal, etc. It also discusses the Hexadecimal Color Representation for displaying color on the web.

## Hardware 
Hard Drives and Memory are internal storage spaces in a computer.
Hard Drives are used to record data for a long period of time. Once Data is saved to the hard drive, it is always available for user regardless of how many the users turn off / reboots the computer. Thus, Hard Drives are considered non-volatile storage.

The central processing unit (CPU) of a computer is the core of a computer. It performs the basic arithmetical, logical, and input/output operations of a computer system. The CPU is considered the brains of the computer.  The main components of a CPU are: 
+ Arithmetic Logic Unit (ALU): Performs arithmetic and logical operations
+ Control Unit:  Review Instructions from memory and calls upon ALU to perform calculation
+ Cache:  High speed Memory where instructions can be copied to and retrieved

### Solid State Hard Drives (SSD): 
SSD : A storage Device that stores data on information on flash memory, which consists of individual memory cells storing bits that are instantly accessible by the controller.  The main difference between an SSD and a traditional hard drive is that SSD stores data on instantly accessible memory chips instead of mechanical platters and a moving read/write head to access data used by a traditional hard drive. As a result, SSD is much faster.
### Random Access Memory
RAM is the computer’s main memory and stores the data/document while the user is actively working on it. When the user turns off the computers, information on RAM disappears. Thus, RAM is used as a working memory.  By increasing RAM on a computer, more data can be saved on the RAM instead of constantly retrieving data from a slower hard drive, thereby making the computer much faster. 
#### 64 bit data path vs 32 bit data path:  
RAM Module DIMM (64 bit data path) transfers 64 bits of data at a time versus 32 bits of data at a time under RAM Module SIM (32 bit data path).

### Hardware: ALU and the Control Unit
Arithmetic logic unit (ALU) is a digital circuit used to perform arithmetic and logic operations.
Operations of a CPU are performed by one of the ALUs, which load data from input registers. A register is a small amount of high-speed memory contained within the CPU. The control unit tells the ALU what operation to perform on that data, and the ALU stores the result in an output register. The control unit moves the data between these registers, the ALU, and memory.
### Hardware: CPU, Input & Output
Hardware: CPU, Input and Output: All computers do the same 4 functions: Input- Store - Process - Output. When we go a self-check-out at a grocery store, we scan the item with the bar code reader (the input device).  This code identifies the product and this information is transferred as binary into the store’s register/computer. The CPU accesses the price file from the memory and then automatically prints the product details and prices for us.
### Hardware: Logic Gates and Circuits
Logic Gate is ab electronic circuit having two inputs and only one output. The relationship between the input and output is based on a certain logic. The Most common types of Logic gates are called AND, OR, NOT, XOR (Exclusive Or), NAND (NOT AND), and NOR (NOT OR).
A truth table is a breakdown of a logic function by listing all possible values a function can attain. Truth table help us summarize how computer chips work 
For example, the AND Gate Accepts two inputs and if both the inputs are 1, then it outputs 1 and if either of the input is 0, then it outputs 
### Hardware: IEE -Ethically Aligned Designn
The Institute of Electrical and Electronics Engineers (IEEE) is a professional association that develops, defines, and reviews electric, electronics and computer science standards in order to promote technological innovation and excellence for the benefit of humanity.
It is very important to ensure that we have ethics built into the concept of designing a device. Ethics helps us to ensure that the proposed device design will not violate any moral/ social values and laws and will generate economic and societal benefit/s. 

## Data Representation
Data representation is the interpretation of data (numeric or non-numeric or integer) using a binary code. A binary digit (called bit) is represented by either a 0 or a 1.  Modern computers can process 64 bits at once 
### Data Representation: Numeric Conversions: 
+ Decimal number: Numbers with base 10 and require the digits 0,1,23,4,5,6,7,8,9
+ Binary Numbers: Numbers with base 2 and use only two digits 0 and 1
+ Hexadecimal: Numbers with base 16 and use the digits 0,1,23,4,5,6,7,8,9,a,b,c,d,e,f
### Data Representation: Hexadecimal Color Representation 
Hexadecimal Color Code #abb0ff means that Hex #abb0ff is composed of 67.1% red, 69 % green and 100 % blue.
This estimation is explained as follows:
#ab b0 ff
Now, first two characters indicate red color, second two characters indicate green color and the third two characters indicate the blue color. Hex Numbers use 16 digits as listed below:
0 ,1,2,3,4,5,6,7,8,9, A, B, C D, E, F.
One thing to keep in find that A represents 10, B Represents 11, C Represents 12, D Represents 13, E Represents 14 and F Represents 15.
+ For the Red Panel, 
we multiply the first number a (i.e. 10) by 16 and the second number (i.e. 11) by 1.
Now we add the sum of the values.
Thus, #ab will tell the computer to add 171(16*10+11*1) level of red color. 
+ For the Green Channel,
we multiply the first number b (i.e. 11) by 16 and the second number (i.e. 0) by 1.
Now we add the sum of the value
Thus, #b0 will tell the computer to add 176 (16*11+1*0) level of green color.
+ Similarly, the Blue Channel will tell the computer to add 255 (16*15+15*1) level of green color.
+ Now the total value of RGB = 171+176+255= 602.
The percentage of the color is as follows:
   + R: 67.1% - 171/255
   + G: 69% - 176/255
   + B: 100% - 255/255
   
The # Hex #abb0ff will result in a light shade of blue.
Also, CMYK value of the #abb0ff is 50.366, 46.928, 101.007.

Additionally, the #abb0ff is not a web safe color since it results in a pale /light blue color which does not provide enough contrast between content and the background for anybody with low vision impairments and color deficiencies. Thus, the Hex Coe #9999ff should be used that results in a darker blue color and thereby providing a better contrast between content and background. 

## Conclusion
Through the course of this lab I learned about functioning of the CPU, relation between CU and ALU and various hardware components like the RAM, Hard Disk,etc. I had to face some difficulty with understanding the Hex color codes. Overall, I found this lesson very informative and interesting and I plan to continue learning and establish my career in the filed of IT.

