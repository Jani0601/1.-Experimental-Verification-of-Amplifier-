## **EX.NO:** 1 EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS



## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM
<img width="624" height="269" alt="image" src="https://github.com/user-attachments/assets/635c9837-d5f5-4d6f-acc9-8a47a4368230" />

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
<img width="779" height="440" alt="image" src="https://github.com/user-attachments/assets/a14d8bc1-9dc7-4a49-98b0-f5320f450a63" />

MODEL GRAPH 

<img width="543" height="357" alt="image" src="https://github.com/user-attachments/assets/1836d120-768e-454f-bfe4-682ce70ea7a1" />



DESIGN:
Inverting amplifier:
<img width="969" height="1205" alt="image" src="https://github.com/user-attachments/assets/74402e13-1a6d-4785-a99f-699b725e62df" />



PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION

<img width="892" height="776" alt="image" src="https://github.com/user-attachments/assets/277e6f8c-9ce9-4254-b2a2-a350682fe097" />

 
---
## GRAPH
<img width="830" height="1087" alt="image" src="https://github.com/user-attachments/assets/403fd030-7452-4bad-b9c4-85624649b398" />



---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.

## design
<img width="1080" height="1075" alt="image" src="https://github.com/user-attachments/assets/af581781-db23-4899-8774-d017aa53072b" />



---

## CIRCUIT DIAGRAM


<img width="704" height="397" alt="image" src="https://github.com/user-attachments/assets/1b4b170f-cf21-4fa9-9dc7-96db30b3c153" />

---

## MODEL GRAPH

<img width="456" height="340" alt="image" src="https://github.com/user-attachments/assets/00c7aaec-b4d8-414e-afa3-e985eb3dd902" />

---
PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION

<img width="1080" height="673" alt="image" src="https://github.com/user-attachments/assets/8cb2c9c1-8902-41ad-a7e2-5ba3bac9701d" />
/>

---
## GRAPH
<img width="1070" height="1451" alt="image" src="https://github.com/user-attachments/assets/b83b6856-dd21-4c7d-b95b-9fcb0bc741f5" />



---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
<img width="706" height="522" alt="image" src="https://github.com/user-attachments/assets/917f2544-3735-4a23-a9b7-1264966d0d20" />

## MODEL GRAPH
<img width="678" height="334" alt="image" src="https://github.com/user-attachments/assets/6aa1b9dd-b112-4be1-a37a-d5ee19607b1d" />

---

## DESIGN
<img width="881" height="1023" alt="image" src="https://github.com/user-attachments/assets/5c115aae-706d-4450-a061-0ac8c7c3e0cd" />

---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)
<img width="1080" height="455" alt="image" src="https://github.com/user-attachments/assets/16b55514-47b3-455d-8637-b029f10ef285" />




---
## GRAPH
<img width="947" height="1175" alt="image" src="https://github.com/user-attachments/assets/52124c9b-8344-4319-aa99-6f758127d2b0" />


---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

<img width="1006" height="1087" alt="image" src="https://github.com/user-attachments/assets/636c08f9-7940-470e-a89e-4891d57a9ac7" />

PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)
<img width="906" height="484" alt="image" src="https://github.com/user-attachments/assets/31d8ffb2-3578-4de2-862d-afc33034db36" />



---
## GRAPH
<img width="1006" height="1286" alt="image" src="https://github.com/user-attachments/assets/89d660d6-375a-4b88-b34b-87808ea221e0" />


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.
<img width="1280" height="632" alt="image" src="https://github.com/user-attachments/assets/6dcff6a9-0383-442d-9de9-2f75939d98ae" />

---
