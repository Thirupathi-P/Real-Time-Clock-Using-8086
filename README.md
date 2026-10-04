# Real-Time-Clock-Using-8086
Real Time Clock on the 8086 Microprocessor in assembly. Time is kept in registers/memory and shown on seven-segment displays/LEDs via an 8255 PPI.

## Mini Project 
The aim of this Mini project is to design and simulate a 24-hour digital clock using the 8086 Microprocessor. 

> [!IMPORTANT]
> To understand the flow of the project, read the **Project Report**.

## Overview of the Project:

The clock shows time in Hours: Minutes: Seconds (HH: MM: SS) format on seven-segment displays. Since the 8086 cannot connect directly to displays and switches, an 8255 Programmable Peripheral Interface (PPI) chip is used in between. The 8255 reads input from three push buttons (SET, UP, DOWN) and a 1 Hz timing pulse, and sends output to six seven-segment displays. 

 &emsp; &emsp;The clock counts seconds, minutes and hours correctly and resets after 23:59:59, and the user can also set the time manually using the push buttons. The project helped in understanding how a microprocessor is interfaced with input and output devices using a PPI chip, which is one of the basic concepts of Microprocessors and Microcontrollers (MPMC).

## Tools Used:

 &emsp; &emsp; **Keil** – used to write and assemble the 8086 Assembly program.<br>
 &emsp;  &emsp;**Proteus** – used to draw the circuit and simulate the complete working of the project.


## Interface Diagram:

<img width="1015" height="508" alt="image" src="https://github.com/user-attachments/assets/0e8e6e97-f110-4c09-8ac1-7a338cc440a9" />

## Code:

> [!NOTE]
> The source code is in the [main.asm](main.asm) file. Please check it out.

## Circuit Design :
<brk>
  <img width="1051" height="624" alt="image" src="https://github.com/user-attachments/assets/458be899-5607-4bf6-ae1f-38321c295c2b" />
</brk>

## Conclusion:


In this Mini project, a 24-hour real-time clock was designed and simulated using the 8086 microprocessor, the 8255 PPI chip and a seven-segment display. The project shows how a microprocessor can be connected to simple input devices (push buttons) and output devices (display) using a PPI chip, which is one of the important topics in Microprocessors and Microcontrollers (MPMC). It also shows how multiplexing is used to control many displays using fewer pins, and how a 1 Hz pulse can be used to keep count of time. 

 &emsp; &emsp;One limitation of this project is that the accuracy of the clock depends completely on the 1 Hz pulse source used in the simulation. In a real hardware circuit, a crystal oscillator or a dedicated real-time clock chip would be used so that the time stays accurate for a long period, even without extra programming. 

 &emsp; &emsp;Overall, this project gives useful hands-on experience in interfacing a microprocessor with real-world input and output devices, which is widely used in many electronic products such as digital clocks, timers, and display boards, making it a useful and practical learning exercise for an MPMC course.


## IEC213 - Microprocessors and Microcontrollers Course Mini project, IIIT Kottayam.
## Team Members:

 |Name | Roll NO|
|-----|-------|
|DHEERAJ MURALI KRISHNAN|2025BEC001|
|ZAYED NAAZIM ABDULLA|2025BEC003|
|ANAGH PELLISSERY|2025BEC0002|
|GUTLAPALLI VAISHNAV SAI|2025BEC0036|
