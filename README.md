### NAME:SACHIN .S
### REG NO.:24900576
### EXP-6:IMPLEMENTATION OF SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

# AIM:

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

# SOFTWARE REQUIRED:

Quartus prime

# THEORY

# SISO shift Register

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

# Procedure:
Implementing shit in Verilog HDL (Hardware Description Language) involves translating the simplified Boolean expressions into Verilog code to describe the behavior of digital circuits. The basic building blocks in Verilog is module. The module represent a combinational circuit. Use logical operators (&, |, ~, ^) to implement Boolean functions directly. Use built-in gate primitives for basic functions. Use University program VWF to verify the functionality of your Verilog modules. Create waveform and check outputs against expected results.
# PROGRAM
![Screenshot 2024-12-12 133040](https://github.com/user-attachments/assets/235fb92a-ade3-4bb6-808a-6c93883a02df)

# RTL LOGIC FOR SISO Shift Register
![Screenshot 2024-12-12 133011](https://github.com/user-attachments/assets/0568ed57-6898-4480-ad54-87757247b2dd)

# TIMING DIGRAMS FOR SISO Shift Register
![Screenshot 2024-12-12 132927](https://github.com/user-attachments/assets/f740fa0a-4223-486c-8cb6-4d3d8cfa6062)

# RESULTS:
Implemented SISO Shift Register using verilog and validating their functionality using their functional tables.
