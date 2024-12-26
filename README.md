# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

1.Type the Verilog program in Quartus Prime to implement the 4-bit Serial-In Serial Out
(SISO) Shift Register. 2.Compile and run the program to ensure the design is error-free.
3.Generate the RTL schematic to visualize the cascading D flip-flop connections and
save it for documentation. 4.Create nodes for the serial input (SI), clock (CLK), and serial
output (SO) to observe the shifting process during simulation. 5.Simulate the design for
different input serial data patterns and observe the timing diagrams.


**PROGRAM**

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed by: Sanjit A RegisterNumber: 24005054

![WhatsApp Image 2024-12-26 at 10 30 39_9d4cfb13](https://github.com/user-attachments/assets/4e5fe8e3-0617-443a-9c06-c1a34b19096c)


*/

Truth Table:

![image](https://github.com/user-attachments/assets/547537cc-66aa-40b2-83e5-c86e0a074793)


**RTL LOGIC FOR 4 Bit Ripple Counter**

![image](https://github.com/user-attachments/assets/9e854bbd-00a5-4e94-bc02-8510f24cfbcc)


**TIMING DIGRAMS FOR 4 Bit Ripple Counter**

![image](https://github.com/user-attachments/assets/37de0b18-cf3a-4697-8f79-d2df27874c09)


**RESULTS**

Thus, the 4-bit Ripple Counter was successfully implemented, and its
functionality was validated using the truth table.
