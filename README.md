# D-FLIPDLOP-NEGEDGE

**AIM:**

To implement  D flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**D Flip-Flop**

D flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, D latch operates with enable signal. That means, the output of D flip-flop is insensitive to the changes in the input, D except for active transition of the clock signal. The circuit diagram of D flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/48c81fe8-bc3f-40e7-95e2-519fc155ad51)

This circuit has single input D and two outputs Qtt & Qtt’. The operation of D flip-flop is similar to D Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of D flip-flop.

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/e5f3fda7-68ec-4a3a-a0a4-cf6f9cc4ab55)

Therefore, D flip-flop always Hold the information, which is available on data input, D of earlier positive transition of clock signal. From the above state table, we can directly write the next state equation as Qt+1t+1 = D

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/8592c0d8-2917-4142-91b9-d6c30dd891d2)

Next state of D flip-flop is always equal to data input, D for every positive transition of the clock signal. Hence, D flip-flops can be used in registers, shift registers and some of the counters.

**Procedure**

License
D-FLIPDLOP-NEGEDGE
AIM:

To implement D flipflop using verilog and validating their functionality using their functional tables

SOFTWARE REQUIRED:

Quartus prime

THEORY

D Flip-Flop

D flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, D latch operates with enable signal. That means, the output of D flip-flop is insensitive to the changes in the input, D except for active transition of the clock signal. The circuit diagram of D flip-flop is shown in the following figure.

image

This circuit has single input D and two outputs Qtt & Qtt’. The operation of D flip-flop is similar to D Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of D flip-flop.

image

Therefore, D flip-flop always Hold the information, which is available on data input, D of earlier positive transition of clock signal. From the above state table, we can directly write the next state equation as Qt+1t+1 = D

image

Next state of D flip-flop is always equal to data input, D for every positive transition of the clock signal. Hence, D flip-flops can be used in registers, shift registers and some of the counters.

Procedure

Open Quartus Prime and create a new Verilog project.

Write the Verilog code for the D flip-flop.

Compile the design to check for errors.

Generate the RTL schematic to verify the correct connections of the flip-flop.

Create a testbench to simulate the functionality of the D flip-flop.

Apply test cases for D input to verify the expected output behavior.

Verify that the output Q follows the input D only on the rising clock edge.

Generate the timing diagram to visualize the signal transitions and ensure correct synchronization.

Validate the simulation results against the functional table.

**PROGRAM**

/* Program for flipflops and verify its truth table in quartus using Verilog programming.
Developed by:T Isaac Raja 
RegisterNumber:24900178

![image](https://github.com/user-attachments/assets/ddfc849a-2560-4ffa-8519-d58100dd5180)

*/

**RTL LOGIC FOR FLIPFLOPS**

![image](https://github.com/user-attachments/assets/de8e052e-7c15-4d01-9eab-c5cd00c562f9)


**TIMING DIGRAMS FOR FLIP FLOPS**

![image](https://github.com/user-attachments/assets/3ddcd589-791e-4154-96ec-5c9a11f001eb)


**RESULTS**

The D flip-flop was successfully implemented in Verilog, and its functionality was validated with the truth table and timing diagrams. The output Q correctly follows the input D on each rising clock edge.
