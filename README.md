# 1.Design-implement-and-simulation-of-Inverting-noninverting-and-Differential-amplifier

**AIM:**
To design , implement and simulate  an inverting, non- inverting and differential amplifiers

**APPARATUS  and SOFTWARE REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,10K	2
7.	Connecting wires and probes	As required	
8.  LT SPICE software

**THEORY:**
Op-amp in open-loop configuration has a very few application because of its enormous open-loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1.	Inverting amplifier.
2.	Non-inverting amplifier.
3.	Differential amplifier.
The entire configuration can be operated with either AC or DC input.

**INVERTING AMPLIFIER:**
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

**NON - INVERTING AMPLIFIER:**
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

**DIFFERENTIAL AMPLIFIER**
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
𝐴	= 	𝑉𝑜/(V2-V1) = −𝑅𝑓/R1

**DESIGN:**

**Inverting amplifier:**
    Gain is     A = -Rf/R1
        Take  A = 10
        Rf =10 R1
        Choose R1 = 1kΩ, Rf=10kΩ
        
**Non inverting amplifier:**
    Gain is    A = 1+ Rf/R1
      Take A = 2
      Rf = R1
      Choose Rf = 10kΩ, R1=10kΩ
      
**Differential amplifier**
  Gain is 𝐴=	𝑉𝑜/(𝑉1− V2)= − 𝑅𝑓/𝑅1
Take  A = 10
 Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

**PROCEDURE:**
**Inverting and Non-inverting amplifier:**
1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
   
** Differential amplifier:**
1.	Select the value of R1, R2, R3 & Rf such that R1=R2 and R3=Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Provide constant input voltage Vin1 to Non-inverting terminal of op-amp through R1 & constant input voltage Vin2 to inverting terminal of op-amp through R2.
4.	Measure the output voltage using DSO.
5.	Calculate the theoretical Vo and compare it with practical Vo.
6.	Practical output & theoretical calculation should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
 
**PIN DIAGRAM:**
<img width="1600" height="866" alt="image" src="https://github.com/user-attachments/assets/8ae58871-4cb3-4dfc-a472-a739dc66d32c" />


**INVERTING AMPLIFIER:**

  **CIRCUIT DIAGRAM**
<img width="1600" height="996" alt="image" src="https://github.com/user-attachments/assets/db8a3b78-0ee7-4221-901f-08e8a5ac0e6d" />



  **MODEL GRAPH:**
<img width="1600" height="1252" alt="image" src="https://github.com/user-attachments/assets/454b96ca-cbc4-489e-9e2b-a251a39a5eb2" />



  **TABULATION:**
<img width="1599" height="921" alt="image" src="https://github.com/user-attachments/assets/a8233f48-83ff-4877-a5ea-eaa41eafb9af" />



**MODEL CALCULATION:**
<img width="862" height="1361" alt="image" src="https://github.com/user-attachments/assets/8c1b886d-8fdf-4c77-8b34-463beafbd81d" />


**NON INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="1600" height="946" alt="image" src="https://github.com/user-attachments/assets/e6cd9843-8791-414f-9569-dbe2ddf1384a" />


  **MODEL GRAPH:**
<img width="1600" height="1326" alt="image" src="https://github.com/user-attachments/assets/601f148f-a125-4636-9518-e5216ccb9cdf" />



  **TABULATION:**
<img width="1600" height="813" alt="image" src="https://github.com/user-attachments/assets/b4314eb0-14bd-4158-b3a8-483eb96611b4" />

  **DIFFERENTIAL AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="1600" height="1259" alt="image" src="https://github.com/user-attachments/assets/5065f3b2-6817-4ffe-91b8-05ae385df8f4" />



  **MODEL GRAPH:**
<img width="1547" height="895" alt="image" src="https://github.com/user-attachments/assets/d62c234d-5c5c-4b9f-ba5a-14ca4f31a117" />



  **TABULATION:**
<img width="1600" height="1012" alt="image" src="https://github.com/user-attachments/assets/3f97a740-795d-49e2-bdcf-956a707744aa" />

**LT-SPICE Tool:PROCEDURE:**
•	Double click on LT-Spice icon.
•	New schematic window open.
•	Pick and paste the required component from the library and draw the circuit diagram .
•	Complete the connection.
•	Save the file by giving file name.
•	Click on the run option ->click advanced open ->select Ac analysis->enter the amplitude time delay stop time value.
•	Click on the run option ->simulation window opens->place the probe ->output graph is obtained.
 
  **LT SPICE**
  **CIRCUIT and Waveform**
<img width="1600" height="900" alt="WhatsApp Image 2026-09-13 at 7 39 53 PM" src="https://github.com/user-attachments/assets/0f371aeb-58f1-4754-b0e9-9a4bf9ccac6e" />

  
  <img width="1600" height="900" alt="WhatsApp Image 2026-09-13 at 7 39 54 PM" src="https://github.com/user-attachments/assets/d972059a-00e2-489c-ba63-a3d5df941fcf" />

  <img width="821" height="413" alt="WhatsApp Image 2026-09-13 at 8 03 02 PM" src="https://github.com/user-attachments/assets/5fd879c2-3f82-4a2d-87b9-53413a0417e7" />


**RESULT:**
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and simulated performance was successfully tested using op-amp IC 741 and LT SPICE.
 






