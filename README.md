# 2:1 MUX
This repository presents the Design of 2:1 MUX  implemented using synopsis custom compiler on 28nm technology
# Table of Content
- [Abstract](https://github.com/Bekalsupritha/2-1-MUX/edit/main/README.md#abstract)
- [Tools Used](https://github.com/Bekalsupritha/2-1-MUX/edit/main/README.md#tools-uesd)
- [Circuit Details](https://github.com/Bekalsupritha/2-1-MUX/edit/main/README.md#circuit-details)
- [Reference Circuit](https://github.com/Bekalsupritha/2-1-MUX/edit/main/README.md#reference-circuit)
- [Reference Waveform](https://github.com/Bekalsupritha/2-1-MUX/edit/main/README.md#reference-waveform)
- [Truth Table](https://github.com/Bekalsupritha/2-1-MUX/edit/main/README.md#truth-table)
- [Simulation Using Synopsis](https://github.com/Bekalsupritha/2-1-MUX/edit/main/README.md#simulation-using-synopsis)
- - [Circuit](https://github.com/Bekalsupritha/2-1-MUX/edit/main/README.md#circuit)
- - [Idle Mode](https://github.com/Bekalsupritha/2-1-MUX/edit/main/README.md#idle-mode)
- - [Waveform](https://github.com/Bekalsupritha/2-1-MUX/edit/main/README.md#waveform)
- [Author](https://github.com/Bekalsupritha/2-1-MUX/edit/main/README.md#author)
- [Acknowledgement](https://github.com/Bekalsupritha/2-1-MUX/edit/main/README.md#acknowledgement)
- [References](https://github.com/Bekalsupritha/2-1-MUX/edit/main/README.md#references)
# Abstract
This paper presents a analysis of 2:1 MUX using CMOS logic. One of the important elements in digital circuit is a multiplexer or data selector for processing multiple inputs with a single output.Currently multiplexer have become a universal logic element used to design any digital combinational logic circuits/system in the IC’s. A multiplexer is a building block in communication networking. It is a combinational circuit that converts serial data into parallel data. 2:1 MUX has 2n input lines, ‘n’ select lines and single output line. According to the binary value of the select line the particular input is selected and passed to the output. In this paper, multiplexer using CMOS logic are analyzed in performance point of view.
# Tools Uesd
- Synopsys Custom Compiler:  The Synopsys Custom Compiler™ design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. This tool was used to design the circuit on a transistor level.
- Synopsys Primewave:  PrimeWave™ Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. This tool helped in various types of simulations of the above designed circuit.
- Synopsys 28nm PDK:  The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit.
# Circuit Details
Multiplexer is a universal combinational circuit which can be used to implement any logic gate. It has 2 input data lines, single select line and single output line. Complementary Metal Oxide Semiconductor logic deploys symmetric number of both types of MOSFET’s, i.e., pMOS and nMOS. This leads to better performance of any logic circuit since nMOS is strong ‘0’ device and pMOS is strong ‘1’ device. Thus, CMOS provides complete ‘1’ and complete ‘0’ logics at the output without any distortion.2:1 MUX using CMOS modeled using 10 transistors. The 2:1 MUX using static CMOS has been designed using a Pull-Up Network (PUN) consisting of 4 pMOS and a Pull-Down Network (PDN) consisting of 4 nMOS. The PUN is constructed using two parallel pMOS circuits connected in series. The PDN is constructed using two series nMOS circuits connected in parallel .The function of the PDN is to provide a connection between the output and VDD when the output is 1. Similarly, the PDN connects the output to ground when the output is expected to be 0. They have simple design; hence they are insensitive to variations, good noise margins, fast operating speed and low power. Nevertheless, performance or area constraints occasionally dictate the need for other circuit families. One of the major advantages of Static CMOS logic is that they have zero quiescent power dissipation, where for any applied input state either the PUN or PDN remains off.
# Reference Circuit
![cmos ckt](https://user-images.githubusercontent.com/100553715/156155177-1a7b5055-28e0-4833-aa45-3872a5e2f4d4.jpg)
# Reference Waveform
![cmos](https://user-images.githubusercontent.com/100553715/156155229-0b1d02e7-ce84-4186-bedc-d49f2be2cf39.jpg)
# Truth Table
![truth table](https://user-images.githubusercontent.com/100553715/156176766-ff97507b-155d-47ce-bf14-53dd027bdf69.png)
# Simulation using Synopsis
>## Circuit
![circuit](https://user-images.githubusercontent.com/100553715/156155400-05b3b9c2-2afa-4dca-bd9c-73b25175a6fd.png)
>## Idle Mode
![Idle mode](https://user-images.githubusercontent.com/100553715/156155442-c0880c07-a8d1-4f83-80e2-4b23339e1b7b.png)
>## Waveform
![waveform](https://user-images.githubusercontent.com/100553715/156157091-88f31845-3dac-42a8-ba49-661b917511c3.png)
# Author
Supritha bekal,Mangalore Institute Of Technology and Engineering
# Acknowledgement
1. [CLoud Based Analog IC Design Hackathon](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/)
2. [Synopsys India](https://www.synopsys.com/)
3. [VLSI System Design (VSD)] Corp.Pvt.Ltd India
4. Kunal Ghosh, Co-founder, VSD Corp.Pvt.Ltd.- [kunalghosh@gmail.com](kunalghosh@gmail.com)
5. Chinmay Panda, IIT Hyderabad
6. Sameer Durgoji, NIT Karnataka
# References
1. International Journal of Trendy Research in Engineering and Technology.https://www.academia.edu/55583852/Investigation_of_MUX_Using_Various_CMOS_Circuit_Style_under_Nanometer_Technology
2. https://youtu.be/1l7KEYFRFzs
3. Journal of Advancements in Robotics.https://www.researchgate.net/publication/349211497_21_Multiplexer_Using_Different_Design_Styles_Comparative_Analysis

