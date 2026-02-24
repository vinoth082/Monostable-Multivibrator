## Experiment No: 6
MONOSTABLE MULTIVIBRATOR USING 555 TIMER 
## Aim
To design and simulate a Monostable Multivibrator using NE555 in Proteus Design Suite and verify the time duration of the output pulse.
## Apparatus Required
•	NE555 Timer IC
•	Resistor R = 100 kΩ
•	Capacitor C = 10 µF
•	Push Button (Trigger)
•	DC Power Supply (5V or 9V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
<img width="1911" height="1023" alt="image" src="https://github.com/user-attachments/assets/16893c3c-a97f-4746-a69e-50921c6680d3" />

Pin Connections:
•	Pin 1 → Ground
•	Pin 2 → Trigger (Connected to push button)
•	Pin 3 → Output
•	Pin 4 → Reset (Connected to Vcc)
•	Pin 5 → Control Voltage (Optional 0.01 µF capacitor to ground)
•	Pin 6 → Threshold
•	Pin 7 → Discharge
•	Pin 8 → Vcc
## Circuit Connections:
•	Resistor R → Between Vcc and Pin 7
•	Capacitor C → Between Pins 6 & 7 and Ground
•	Trigger → Pin 2
•	Output → Pin 3
## Theory
A Monostable Multivibrator has only one stable state and one quasi-stable state. It produces a single output pulse when triggered externally.
In monostable mode:
•	The circuit remains in stable LOW state.
•	When a negative trigger pulse is applied at Pin 2 (below 1/3 Vcc), the output becomes HIGH.
•	The capacitor starts charging through resistor R.
•	When capacitor voltage reaches 2/3 Vcc, the output returns to LOW state automatically.
Thus, a single pulse is generated for a fixed time duration.
The NE555 operating in monostable mode acts as a one-shot pulse generator. It has one stable state and one quasi-stable state. Normally, the output remains LOW. When a negative trigger pulse is applied to the trigger pin (Pin 2) below 1/3 Vcc, the output becomes HIGH and remains HIGH for a fixed time interval. During this period, the capacitor connected in the circuit charges through the resistor. When the capacitor voltage reaches 2/3 Vcc, the output automatically returns to LOW state. The pulse width of the output is determined by the resistor and capacitor values and is given by the expression T=1.1RCT = 1.1 RCT=1.1RC. Thus, the 555 timer in monostable mode produces a single output pulse for each trigger input and is widely used in timer and delay applications.
## Procedure
1.	Open Proteus software.
2.	Select NE555 timer, resistor, capacitor, push button, and CRO.
3.	Connect circuit in monostable configuration.
4.	Apply 5V supply.
5.	Press trigger button.
6.	Observe output pulse on CRO.
7.	Measure pulse width.
## Tabulation
S.No	        R (kΩ)	          C (µF)	        Theoretical Pulse Width	            Practical Pulse Width

<img width="1025" height="285" alt="image" src="https://github.com/user-attachments/assets/29fc870c-e52a-44cb-af6b-b42d4e572095" />

## Waveform
<img width="1041" height="657" alt="image" src="https://github.com/user-attachments/assets/da379f34-f187-4d94-bd46-d6c25d8ca1fb" />

•	Trigger → Short negative pulse
•	Output → Single positive pulse
•	Capacitor voltage → Exponential charging waveform
## Result
The Monostable Multivibrator using NE555 Timer IC was successfully designed and simulated in Proteus.
A single output pulse of duration approximately 1.1 seconds was obtained.
The practical value closely matches the theoretical value.
## Conclusion
•	The circuit produces one output pulse for each trigger.
•	Pulse width depends on R and C values.
•	Increasing R or C increases pulse duration.
•	Used in timers, delay circuits, and pulse generation applications.
## Viva Questions
1.	What is a monostable multivibrator?
<img width="985" height="115" alt="image" src="https://github.com/user-attachments/assets/82f0d8d4-3279-4456-a342-5a231adfe34e" />

2.	Write the pulse width formula.
<img width="781" height="272" alt="image" src="https://github.com/user-attachments/assets/bea70a4f-bb36-47c6-afc8-118a1b8010a0" />

3.	What is the stable state of monostable?
<img width="1145" height="92" alt="image" src="https://github.com/user-attachments/assets/df356dc8-0241-4b66-83ee-e29ef0e70d18" />

4.	Why is it called “one-shot”?
<img width="930" height="92" alt="image" src="https://github.com/user-attachments/assets/d536517b-3bcb-4d74-813a-47dbbb2afcf2" />

5.	What happens if capacitor value increases?
<img width="743" height="137" alt="image" src="https://github.com/user-attachments/assets/5904109a-cd99-4f53-a165-e2e41e870031" />
