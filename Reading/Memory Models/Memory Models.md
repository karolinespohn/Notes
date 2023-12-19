# Basics  
- Memory models describe how threads can interact through data and shared memory
- From memory models, compilers can derive rules for which kind of optimizations can be performed on multi threaded code
- If no memory model exists, compilers apply no optimizations to multi-threaded code or assume single-threaded execution, leading to bugs
- Weak memory models allow more reordering than strong memory models, making certain proofs harder or impossible
# Java Memory Model 
- The Java Memory Model examines each read in an execution trace
- For each read of data $d$, it checks whether the write which wrote $d$ was valid 
# Sources
- [Wikipedia](https://en.wikipedia.org/wiki/Memory_model_(programming)
- [Oracle Docs](https://docs.oracle.com/javase/specs/jls/se21/jls21.pdf)