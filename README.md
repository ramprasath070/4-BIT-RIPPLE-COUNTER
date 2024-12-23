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

1. Understand the Ripple Counter Behavior
Inputs:

clk: Clock signal driving the first flip-flop.
reset: Asynchronous signal to reset all flip-flops to 0.
Outputs:

count: 4-bit binary value representing the counter state.
Behavior:

Each flip-flop toggles on the falling or rising edge of its clock.
The first flip-flop (LSB) toggles on every clock pulse, and subsequent flip-flops toggle based on the output of the preceding flip-flop.


**PROGRAM**

![DE ex12 code](https://github.com/user-attachments/assets/e7834987-13c6-4db4-8824-147e9507a567)


 Developed by: RAM PRASATH S RegisterNumber:24900195


**RTL LOGIC FOR 4 Bit Ripple Counter**

![DE ex12 diagram](https://github.com/user-attachments/assets/dafe13af-c4d5-4fcd-af25-b62fe98387f8)


**TIMING DIGRAMS FOR 4 Bit Ripple Counter**

![DE ex12 waveform](https://github.com/user-attachments/assets/27020a47-fa19-4b56-8199-46fcb9f8e034)


**RESULTS**
The implementation of  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

