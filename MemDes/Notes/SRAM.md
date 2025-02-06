# 6T SRAM - Write Operations
- 2 cross couple CMOS inverters are formed by using transistor pairs M1-M2 & M3-M4
- 2 Bit lines are used to transfer data and are complement to each other.
# LAYOUT- CMOS inverter pair


# Assignment 1: 6T SRAM
## Make the Layout for the sram using 2 pdk libraries
### GPDK 180nm
### SCL 180nm


# Stability analysis: Static Noise Margin
- Static noise analysis is used to study noise distribances on SRAM cell
- It is classified as HSNM, RSNM, WSNM.
- HSNM- Hold static noise margin
	- In HSNM, - PG transistors are off, No connections to bit line & complementary bit line.
	- It is equivalent to a sense amplifier
	- Why do we do this?
		- This is being done to make sure that the 2 nodes which are connected can effectively hold all the data without losing it over time?
	- Butterfly Curve: Max noise margin something!!??

- RSNM- Read static noise margin
	- PG transistors turned on, connected bit line & complementary bit line.
		- smaller noise margin
		- the curve is slightly changed, there is some residue voltage seen in the graph
		- There is a finite amount of voltage.

- WSMN- Write static noise margin
	- One bit line is connected to VDD & the other is connected to GND
	- Right branch has the same condition as the read operation
	- Left branch, it decays from certain low value to ground


# Dynamic Noise Margin
- Dynamic analysis is more practical
- A current is injected onto one of the nodes 
- Based on 

- the concept of separatrix which defines boundary between stable & unstable state
- current through pass transistors acts as current source 



# Transistor's sub-threshold current
- Due to carrier diffusion between src & channel
- If gnd is not 0 but some finite value then there is leakage current 
- s

# Variability & Reliability


# Content Addressable Mem
Normally, RAMs are accessed by supplying an address. The mem returns the data word stored in it. A CAM is designed such that the user supplies a data word and the CAM returns one or more addresses where the word was found. 

