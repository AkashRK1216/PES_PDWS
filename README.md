# PES_PDWS
<h2>Day-1: Development of opensource EDA, openLane and Sky130 Physical Design Kit</h2>
<details open>
<summary>Talking to Computers </summary>
<br>
<ul>
  <li> Computers are defined by levels of abstraction and this makes t easier for developers</li>
  <li> Developers use a high level programming language to instruct the computer</li>
  <li> This ligh level language is then broken down into RISC-v(or x86) code by the compiler</li>
  <li> The Assembler takes the output of the compiler and breaks down the RISC-V code into machine code(Binary)</li>
</ul>
Here we can see the image which depicts the above steps:
<p>![image](https://github.com/AkashRK1216/PES_PDWS/assets/98165735/ff51504f-48f3-4c9b-abcb-8ff6319236d5)</p>
<p>![image](https://github.com/AkashRK1216/PES_PDWS/assets/98165735/798a42f6-cb8d-4ba5-b318-44153251705b)</p>
</details>

<details open>
<summary> Brief overview of a SoC Design</summary>
<h5>Here is an image of a System on Chip with its components:</h5>
![image](https://github.com/AkashRK1216/PES_PDWS/assets/98165735/76aba3c9-64a7-497b-96c6-c2b5e51c47cf)
<ul>
  These are the explanations for all the labelled parts
<li>SDRAM - Synchronous Dynamic Random-Access Memory (SDRAM) is a type of volatile semiconductor memory. Its primary function is to provide high-speed data storage and retrieval capabilities for temporary data storage and quick access by the processor</li>
<li>JTAG - Joint Test Action Group, is a standard interface and protocol used for testing and debugging integrated circuits, including chips and microcontrollers. The primary function of JTAG is to perform boundary scan testing. Boundary scan is a technique used to test the interconnections between the pins of an integrated circuit and detect faults or defects.</li>
<li>UART- Universal Asynchronous Receiver/Transmitter is a common serial communication interface.UART serves as a means for transmitting and receiving serial data between a chip and other external devices.</li> 
<li>GPIO- General-Purpose Input/Output, is a versatile hardware that allows the chips to interact with the external world by providing the ability to read digital signals from external devices and send digital signals to external devices.</li>
<li>I2C- Inter-Integrated Circuit, is a serial communication protocol that is used to connect multiple digital devices together on the same bus.</li>
<li>QSPI- Quad Serial Peripheral Interface, is a high-speed serial communication protocol commonly used for data storage, memory access, and communication between microcontrollers, microprocessors, and external memory devices. It offers higher data transfer rates than traditional SPI's</li> 
</ul>
</details>

<details open>
<summary> SoC Design with OpenLANE</summary>
![image](https://github.com/AkashRK1216/PES_PDWS/assets/98165735/a7344a84-b564-4461-8b40-2f7221f2d677)
<p>OpenLANE is an EDA tool containing several PDKs completely simulate the fabrication of hardware on a computer</p>
<h5> What is a Process Design Kit?</h5>
<p>"PDK" a (Process Design Kit) is a set of files provided by semiconductor manufacturers to help designers use their fabrication process to create integrated circuits (ICs). It contains a comprehensive set of information, models, and files that enable designers to develop and verify their designs using the specific process technology offered by the manufacturer.</p>
<h5>What is an Electronic Design Automation tool?</h5>
<p>EDA stands for (Electronic Design Automation), and EDA tools refer to a category of software applications and tools used in the design and development of electronic systems, including integrated circuits (ICs), printed circuit boards (PCBs), and other electronic components.EDA tools are essential for designing and testing electronic hardware and ensuring that it functions correctly before it is manufactured.hese tools automate various aspects of the design process, making it more efficient and error-free.</p>




