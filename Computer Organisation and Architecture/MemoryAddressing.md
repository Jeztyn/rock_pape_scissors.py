<h1>Memory Addressing Modes</h1>

There are many ways to locate data and instructions in primary memory and these methods are known as <b>Memory Address Modes</b>.

There are essentially 4 types of Memory Addressing modes:
  1. Immediate
  2. Direct
  3. Indirect
  4. Indexed

<h3>Immediate Addressing mode</h3>
-> It basically means that the data is hard-coded into the instruction itself.   
-> It neither requires memory accesses nor fetching of memory so it is, by far, the fastest method of addressing.
-> the major disadvantage of this mode is the size constraint.
<h3> Direct Addressing mode </h3>
->It is a very straightforward method of addressing data, we basically provide the memory location of the data.
-> It requires a memory access so while it is fairly fast, it is slower than Immediate addressing.
<h3> Indirect Addressing mode </h3>
-> It essentially means that the address of the data is stored at an intermediate location so we basically have to find the intermediate location first which then gives us the address of the data.
-> there are two memory accesses required so it is slower than both direct and immediate but it contain data of larger sizes.
<h3>Indexed Addressing mode </h3>
-> It means that the final address of the data has to be found using an offest from the base address.
-> It is ideal for storing and accessing values of arrays because they require contiguous memory locations so we need only the address of the first element to find the location of the other elements in the array. 