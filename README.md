# Microprocessor8bit
This is an 8-bit microprocessor that is designed to implement a set of 16 instructions as per the project specifications.

## Project specifications:
<img width="836" alt="Screenshot 2024-08-24 at 10 13 30 PM" src="https://github.com/user-attachments/assets/5b85f993-1e6b-4125-83f5-11ffc57da8ee">

The whole microprocessor design is divided into 5 parts:

* Instruction Memory
* Control Unit(CU)
* Data Memory
* Arithmetic Logic Unit(ALU)
* Multiplexers(MUX)

## Working of microprocessor:
* User writes the instructions to the instruction memory which will be fetched by the Control unit later on.
* User provides input to Data memory which is required for performing the operation after the control unit decodes the instruction.
* Control unit fetches instructions one-by-one and decodes them to perform operations.
* Now, the Control unit performs operations on the data present in the data memory with the help of ALU.
* Once the operation is finished in the ALU, then the required result will be obtained as the output.

## Input handling:

* As mentioned in the question, a sign extension is used for handling the inputs.
* Because the provided input is of either 2 bits or 4 bits but we need an 8-bit input based on the register size. So, we used a 6-bit sign extension in the case of 2-bit input and a 4-bit sign extension in the case of 4-bit input.
* Eg: 01 input is taken as 00000001 and 1001 input is taken as 11111001.

## Microprocessor Architecture:
<img width="836" alt="Screenshot 2024-08-24 at 10 27 52 PM" src="https://github.com/user-attachments/assets/80bb4b5a-a44a-4add-b688-5bde616186af">

## State Diagram:
This is a state diagram that shows the process of obtaining output based on the given input.







