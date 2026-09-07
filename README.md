# SR-FLIPFLOP-USING-CASE

**AIM:**

To implement  SR flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

SR Flip-Flop SR flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, SR latch operates with enable signal. The circuit diagram of SR flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/0f710028-ad52-4d3e-9276-8714cf023a25)

 
This circuit has two inputs S & R and two outputs Qtt & Qtt’. The operation of SR flipflop is similar to SR Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of SR flip-flop.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/dabfc4f4-87e3-4cbc-9472-f89ee1b5ed30)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, SR flip-flop can be used for one of these three functions such as Hold, Reset & Set based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of SR flip-flop. Present Inputs Present State Next State

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/dd90d16c-aec5-4290-a586-e2346b1e9eb5)

 
By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. The three variable K-Map for next state, Qt+1t+1 is shown in the following figure.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/473efad6-d70b-4ca7-aeb7-898bbfca319f)

 
The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=S+R′Q(t)Q(t+1)=S+R′Q(t)

**Procedure**

/* write all the steps invloved */

**PROGRAM**
<img width="391" height="120" alt="503652964-97795ed0-f069-4aa7-9ddd-23a187327c3f" src="https://github.com/user-attachments/assets/3e91746c-dc49-44bd-af1d-338173ff10f0" />

/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:212225240044
*/

**RTL LOGIC FOR FLIPFLOPS**
<img width="1742" height="599" alt="503653385-1f21b22c-0ed2-46a5-8a5b-0e7db144941a" src="https://github.com/user-attachments/assets/6ba83859-33a8-4343-a3d2-42b2ebe64627" />

**TIMING DIGRAMS FOR FLIP FLOPS**
<img width="551" height="254" alt="503653670-d857b2a6-af5f-4640-bfde-2bd0754d1d91" src="https://github.com/user-attachments/assets/4fc817e9-db93-4028-a762-c1db464ce79a" />

**RESULTS**
Successfully implemented SR flipflop using verilog and validating their functionality using their functional tables
