malloclab
=========

Malloc Lab - CS 220

Malloc implementation done for Computer Architecture class. To run, use the command:

./mdriver -f ./traces

to run with the traces given. 

Implementation:
===============

Runs a user-defined malloc using a explicit free list with coalescing and splitting. As of right now, it gives a performance of 86. 

Future Plans:
=============

I am hoping to  get a RB-Tree implementation working, and use segregated lists, this will improve performance exponentially since lookup time will go from O(n) -> O(log(n)). Using segregated free lists will bring fragmentation down significantly as it will give semi-optimal blocks to reduce fragmentation.
