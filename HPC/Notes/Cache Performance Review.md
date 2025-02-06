Assume we have a computer where the cycles per instructions is 1 when all mem access hit in the cache. The only data accesses are loads & stores & these total 50% of the instructions. It the miss penalty is 25 clock cycles & the miss rate is 2% how much faster would the computer be if all instructions were cache hits.


Assume the miss rate of instruction cache is 2% & the miss rate of the data cache is 4%. If a processor has CPI of 2 without any mem stalls & the miss penalty is 100 cycles for all misses. Determine how much faster a processor would run with a perfect which would never miss. Assume the freq of all loads and stores is 36%.



# Split Cache
Instruction and data cache is split into 2 different blocks & they operate in parallel



# Basics of Cache Optimization
## Techniques to Reduce Miss Rate 
### 3rd Optimization: Higher Associativity
Assume that higher associativity would increase the clock cycle time as listed below:
	Clock cycle time 

>[!Question]
>Calculate the local and global miss rates at lvl 1 & lvl 2 cache 
>
>For the following basic cache optimisation techniques write which performance parameter(miss rate, miss penalty, hit time) is getting reduced & what is the hardware complexity. If parameter getting reduced is miss rate mention the class of miss getting reduced.
> 	1. Large block size 
> 	2. Large cache
> 	3. higher associativity
> 	4. multilevel cache


## Techniques to Reduce Miss Penalty
Fifth Optimisation: Giving priority to Read Misses over Write miss Penalty

Write buffers, however do complicate mem acc because they might hold the updated value of a location needed on a read miss 

Assume direct mapped write through cache that maps 512 & 1024 to the same block, & a four word write buffer that is not checked on a read miss. Will the value in R2 always be equal to the value in R3?

