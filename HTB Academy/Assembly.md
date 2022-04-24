![[Pasted image 20220409165000.png]]

`Stack`

Has a Last-in First-out (LIFO) design and is fixed in size. Data in it can only be accessed in a specific order by push-ing and pop-ing data.

`Heap`

Has a hierarchical design and is therefore much larger and more versatile in storing data, as data can be stored and retrieved in any order. However, this makes the heap slower than the Stack.

`Data`

Has two parts: `Data`, which is used to hold variables, and `.bss`, which is used to hold unassigned variables (i.e., buffer memory for later allocation).

`Text`

Main assembly instructions are loaded into this segment to be fetched and executed by the CPU.


Although this segmentation applies to the entire RAM, `each application is allocated its Virtual Memory when it is run`. This means that each application would have its own `stack`, `heap`, `data`, and `text` segments.

![[Pasted image 20220416200111.png]]

![[Pasted image 20220416200135.png]]

![[Pasted image 20220416201232.png]]

![[Pasted image 20220416202221.png]]
![[Pasted image 20220417214929.png]]

-
 