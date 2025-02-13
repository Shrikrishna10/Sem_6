
A program is running one a computer with a 4-entry fully associative (micro) translation lookaside buffer (TLB). The following is a trace of virtual page numbers accessed by a program for each access indicate whether it produces a hit/miss &, if it  access the page table, whether it produces a page hit or fault. Put an X under the page table column if it is not accessed.



A page mem sys is divided into 16, 256 MB pages of which any 4 pages can be loaded at a given time. assume processor has loaded pages 2, 3, 4 & 5. Identify how many page faults would occur to load the requested pages 7, 3, 6, & 4 using LRU.


# Ten advanced Optimizations of Cache Performance:
## 1st Optimisation: Small & Simple 1st-lvl caches to reduce Hit time & power
- Critical timing path in a cache hit is the 3-step proccess:
	- Addressing the tag mem using the index portion of the address - Indexing Time required for decoding the index address to select a SET
	- Comparing the read tag value to the address - TAG comparison time & 
	- Setting the multiplexor to choose the correct data item if the cache is set associative - Multiplexing time
- Small size L1 cache: The # sets will be small and the indexing time will be small 
- Simple L1 cache: 
	- Lower the associativity, the lesser is the TAG comparison & Multiplexing time. It means lesser HT
	- Also less # comparison & the energy required for comparison will be less. The higher the associativity higher is the energy required for comparison


Determine whether a 32 KB four-way set associative L1 cache has a faster memory access time than a 32 KB two-way set associative L1 cache. Assume the miss penalty to L2 is 15 times the access time for the faster L1 cache and MR of 2-way is 0.038 and 4 way has .037. Depending on cache size, the hit time for 4 way is 1.4 times longer compared to 2-way. Ignore misses beyond L2. Which has the faster average memory access time?4-way

>[!Solution]
>AMAT(2-way): 1.57 {1+0.036x15}
>AMAT(4-way): 1.37 {1+0.37x10}

