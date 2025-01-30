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
- RSNM- Read static noise margin
	- 
- WSMN- Write static noise margin
