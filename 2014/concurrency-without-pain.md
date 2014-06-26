# concurrency without Pain in Pure Java

Java concurrency lib is the assembly of concurrency library.

pretending to work in a single core -> yay broken obviously when in multicore
* could use closure's STM by just importing the lang's jar...
	* have to avoid side affects inside the transactions
	* managed mutability
	* for shared state
* "closure is the only language that makes concurrency safe" - Venkat
* multi-verse (akka uses this)
* actor based
	* isolated mutability
	* msg in a queue, no two threads can get to the same data at the same time
	* sequential once inside the actor
	* for divide and conquer
	* problem - punish both readers and writers (this means it needs to follow the promise pattern)