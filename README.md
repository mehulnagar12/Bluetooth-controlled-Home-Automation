Bluetooth Module: HC-05

-----------------------
PIN DESCRIPTION:
-----------------------
1.     STATE  --- Open
2.     Rx  --- Serial receiving pin
3.     Tx  --- Serial transmitting pin
4.     GND --- ground
5.     Vcc ---	+5volt dc
6.     EN ---  to enter in AT mode

-----------------------------
MICRO-CONTROLLER USED: 8051
-----------------------------
The pin diagram of 8051 microcontroller looks as follows -
1.        Pins 1 to 8 - These pins are known as Port 1. This port doesn’t serve any other functions. It is internally 
	 pulled up, bi-directional I/O port.

2.        Pin 9 - It is a RESET pin, which is used to reset the microcontroller to its initial values.

3.        Pins 10 to 17 - These pins are known as Port 3. This port serves some functions like interrupts, timer input, 
	 control signals, serial communication signals RxD and TxD, etc.

4.        Pins 18 & 19 - These pins are used for interfacing an external crystal to get the system clock.

5.        Pin 20 - This pin provides the power supply to the circuit.

6.        Pins 21 to 28 - These pins are known as Port 2. It serves as I/O port. Higher order address bus signals are 
	 also multiplexed using this port.

7.        Pin 29 - This is PSEN pin which stands for Program Store Enable. It is used to read a signal from the external 
	 program memory.

8.        Pin 30 - This is EA pin which stands for External Access input. It is used to enable/disable the external memory 
	 interfacing.

9.        Pin 31 - This is ALE pin which stands for Address Latch Enable. It is used to demultiplex the address-data signal
	 of port.

10.        Pins 32 to 39 - These pins are known as Port 0. It serves as I/O port. Lower order address and data bus signals 
	 are multiplexed using this port.

11.        Pin 40 - This pin is used to provide power supply to the circuit.

