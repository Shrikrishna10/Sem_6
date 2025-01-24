# To design a effective computer architecture, the architect need to explore on the following
## Take advantage of parallelism:
- Bit level parallelism: 4-bit, 8-bit, 16-bit & so on.
- Instruction lvl parallelism: At the lvl of an individual processor, taking advantage of parallelism among instructions is critical to achieving high performance
- Data lvl parallelism: Spreading data across many disks for parallel reads & writes enables data-lvl parallelism.
- Thread lvl parallelism: Multi-core systems 
- Logic lvl parallelism: Use carry look ahead, which uses parallelism to spread the process of computing sums

## Principle of locality:
- Programs tend to reuse data & instructions they have used recently.
- A program spends 90% of its execution time is spent on accessing the memory { either a instruction/data}
- An implication of locality is that we can predict with reasonable accuracy what instructions and data a program will use in the near future based on its accesses in the recent past.

>[!Note]
>**Temporal Locality**: If a item is referenced then it will tend to be again referenced soon within relatively small time duration. Access latency can be avoided by reusing the data fetched previously.
>**Spatial Locality**: If a particular storage location is referenced at a particular time, then it is likely that nearby mem locations will be referenced in the near future.
>

### Data
- Reference  Array elements in succession - Spatial locality
- Reference  Sum in each iteration - Temporal locality
### Instruction
- Reference Instruction in sequence  - Spatial locality (basically moving between mem hierarchy)
- Reference Instruction in Loop  - Temporal locality

## Focus on the Common Case
Making the common case fast will tend to enhance performance better than optimizing the rare case. Simple things to have better optimizing and they will be repeated a lot anyways so it will get better.
	IF & ID unit of a processor may not be used that often


# Memory Hierarchy

## Basics of Cache
Focus on any 2 adjacent lvls- called upper(closer to cpu) & lower(farther from cpu)- in the memory hierarchy, because each block copy is always between 2 adjacent lvls.

#### Terminologies
- Block: min. unit of data to move between lvls
- Hit: Data requested is in some block of upper lvl
- Hit rate: fraction of mem accesses that are hits(i.e. found at upper lvl) or the Fraction of mem accesses found in a lvl of the mem hierarchy
- Hit time: Time to determine if the access is indeed a hit + Time to access & deliver the data from the upper level to the CPU(hit time = 1+2).

- Miss: Data requested is not in the upper lvl & need to be retrieved from the block in the lower lvl.
- Miss rate: Fraction of the mem access are not hits
	- Miss rate=(1-hit rate)
- Miss Penalty: The miss penalty is the time to replace a block in the upper lvl with the corresponding block from the lower lvl, plus the time to deliver this block to the processor
	- (Analogy the time to get another book from the shelves & place it on the desk)
