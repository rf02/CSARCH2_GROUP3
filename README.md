## CSARCH2-Cache-Simulation-Project---Group2
The **Cache Simulation Project** is designed to give an overview on the scenarios of the assigned cache mapping and replacement policy. This project contains various test case scenarios to analyze and differentiate each case.

## Specifications
1. Cache line = 16 words
2. Number of cache blocks = 32 blocks
3. Read Policy: non load-through
4. Full Associative + MRU

## Test cases
1. Sequential sequence: up to 2n cache block. Repeat the sequence four times. Example: 0,1,2,3,...,63 {4x}
2. Random sequence: containing 4n main memory blocks.
3. Mid-repeat blocks: Start at block 0, repeat the sequence in the middle two times up to n-1 blocks, after
which continue up to 2n. Then, repeat the sequence four times. Example: if n=8, sequence=0, 1,2,3,4,5,6,7
1,2,3,4,5,6,7 8,9,10,11,12,13,14,15 {4x}
