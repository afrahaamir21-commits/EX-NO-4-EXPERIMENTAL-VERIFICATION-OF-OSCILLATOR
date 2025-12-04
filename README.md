# EX-NO-4-EXPERIMENTAL-VERIFICATION-OF-OSCILLATOR
4. ##**EX.NO:* ## EXPERIMENTAL VERIFICATION OF RC Phase Shift and Wien Bridge oscillators 
	DATE:
 ##AIM:
To construct a RC phase shift and Wien bridge oscillator to generate sine wave using op-
amp.
---
 ##THEORY:
 ##RC PHASE SHIFT OSCILLATOR
RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .
---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 6   | Connecting wires and probes     | As required   | —        |
| 



---
## CIRCUIT DIAGRAM
RC PHASE SHIFT OSCILLATOR

![WhatsApp Image 2025-12-04 at 11 08 27_21227a87](https://github.com/user-attachments/assets/90364d77-7fe1-4542-a9b3-96f412d6ab28)


---

## MODEL GRAPH
![WhatsApp Image 2025-12-04 at 11 08 43_d56165bc](https://github.com/user-attachments/assets/253bfb88-d6f6-48a4-aedb-a87fb4486dd8)

## DESIGN

## RC PHASE SHIFT OSCILLATOR
fo = 1 /  6 (2RC) Rf  29 R1
C = 0.01F, fo = 200 Hz.
R = 1 /  6 (2  f C ) = 3.3 k
Therefore, Choose R = 3.3k
To prevent loading,
R1   10 R
R1 =10 R = 33 k. Rf = 29R1=1MΩ

---
## PROCEDURE
1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude.
---
## TABULATION/OBSERVATION

![WhatsApp Image 2025-12-04 at 11 08 57_e86cb1de](https://github.com/user-attachments/assets/5517d87a-3176-4db5-a0ad-054f2136bc69)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-04 at 11 10 47_03f2929c](https://github.com/user-attachments/assets/dd1b652e-ec86-4b9a-ac1d-55a02d49b2f5)


---
## THEORY
 ##WIEN BRIDGE
A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC
## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 7 | Connecting wires and probes     | As required   | —        |

---

## CIRCUIT DIAGRAM
WIEN BRIDGE OSCILLATOR
![WhatsApp Image 2025-12-04 at 11 09 24_628f0ea7](https://github.com/user-attachments/assets/e38dc8a4-0ad3-4ff9-bb7c-15f864e5c6a4)

---
## MODEL GRAPH
![WhatsApp Image 2025-12-04 at 11 09 41_7d97c400](https://github.com/user-attachments/assets/e84937a2-6238-4519-8762-b2afc78c1a12)

---

## DESIGN

## WIEN BRIDGE OSCILLATOR
Select frequency f0 = 1KHz
fo = 1/2πRC
A = 1+(Rf / R1) = 3.
To find R & Rf.
Therefore Rf = 2R1 & assume C = 0.1μf & find R from
R=1/2πfC
=1/2*3.14*1*103*0.1*10-6
= 1.59KΩ.
Assume R1 = 10R & find Rf from Rf = 2R1
Therefore R1 = 1.5K *10=15KΩ
Rf = 15K *2=30KΩ
---

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.
---
## TABULATION/OBSERVATION
![WhatsApp Image 2025-12-04 at 11 10 10_c928e08c](https://github.com/user-attachments/assets/e778bb44-e6df-4eaf-a462-a3f90420e677)


## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-04 at 11 10 22_999f0ec9](https://github.com/user-attachments/assets/034ef607-3501-4c9c-9bef-0225e223bb15)


---
## RESULT:

Thus the RC Phase Shift and Wien Bridge oscillators are designed and tested using op-amp IC 741.
