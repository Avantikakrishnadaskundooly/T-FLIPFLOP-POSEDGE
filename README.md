# T-FLIPFLOP-POSEDGE

**AIM:**

To implement  T flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**T Flip-Flop**

T flip-flop is the simplified version of JK flip-flop. It is obtained by connecting the same input ‘T’ to both inputs of JK flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of T flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/T-FLIPFLOP-POSEDGE/assets/154305477/458a68fe-2d08-4a9d-ac4f-7ae0480ce0bd)

 
This circuit has single input T and two outputs Qtt & Qtt’. The operation of T flip-flop is same as that of JK flip-flop. Here, we considered the inputs of JK flip-flop as J = T and K = T in order to utilize the modified JK flip-flop for 2 combinations of inputs. So, we eliminated the other two combinations of J & K, for which those two values are complement to each other in T flip-flop. The following table shows the state table of T flip-flop.

Here, Qtt & Qt+1t+1 are present state & next state respectively. So, T flip-flop can be used for one of these two functions such as Hold, & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of T flip-flop. Inputs Present State Next State

![image](https://github.com/naavaneetha/T-FLIPFLOP-POSEDGE/assets/154305477/cdd7fb32-539f-4b66-bb8d-f305a153c886)

 
From the above characteristic table, we can directly write the next state equation as Q(t+1)=T′Q(t)+TQ(t)′ ⇒Q(t+1)=T⊕Q(t)

**Procedure**


![image](https://github.com/user-attachments/assets/1204ee14-88b4-4f5c-893a-08575bc06521)
![image](https://github.com/user-attachments/assets/537fd8b0-6e97-43a6-8dd4-9bac3b5e2c58)

/* write all the steps invloved */

**PROGRAM**


![image](https://github.com/user-attachments/assets/b3b6f0eb-865a-46fd-9459-bbb6f976f9c9)

/* Program for flipflops and verify its truth table in quartus using Verilog programming. 

Developed by: Avantika Krishnadas Kundooly

RegisterNumber: 212224040040
*/

**RTL LOGIC FOR FLIPFLOPS**


![image](https://github.com/user-attachments/assets/1cba79ea-38c8-4935-8622-d55a10f556fc)

**TIMING DIGRAMS FOR FLIP FLOPS**


![image](https://github.com/user-attachments/assets/9a1ce190-01e6-4dcb-96d4-8f28e9b4506c)

**RESULTS**

Thus the truthtable of T flipflop is verified in quartus using Verilog programming.
