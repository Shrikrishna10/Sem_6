# In Memory Computing
- Boolean & Arithmetic operations can be entirely performed in the SRAM array.
- data intensive applications with computations on weights of different layers & so on
- Low density of SRAM cells
	- 6T SRAM activates multiple rows degrading the read noise margins
	- shared read-write paths 
	- 8T SRAM decouples read & write paths 
		- enhances noise margins & allows reducing VDD & hence lowers power consumption
		- Incurs 30% area penalty when compared to 6T SRAM.
		- supports limited boolean operations


- Von Neuman Bottleneck
	- Power to compute
	- power to move
	- data communication 