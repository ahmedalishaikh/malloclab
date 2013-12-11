malloclab
=========

Malloc Lab - CS 220

<dl>
  <dt> Authors </dl>
  <dd> Ahmed Shaikh - ashaikh3@binghamton.edu </dd>
  <dd> Htin Linn  - hkyaw1@binghamton.edu </dd>
</dl>



<dl><dt> Description </dt></dl>
Malloc implementation done for Computer Architecture class. To run, use the command <br>
./mdriver -f ./traces/ <br>
to run with the traces given. 

Implementation:
---------------
Runs a user-defined malloc using a explicit free list with coalescing and splitting. As of right now, it gives a performance of 86. 

Future Plans:
-------------
I am hoping to  get a RB-Tree implementation working, and use segregated lists, this will improve performance exponentially since lookup time will go from O(n) -> O(log(n)). Using segregated free lists will bring fragmentation down significantly as it will give semi-optimal blocks to reduce fragmentation.
