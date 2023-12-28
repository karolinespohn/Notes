# Basics  
- Memory models describe how threads can interact through data and shared memory
- From memory models, compilers can derive rules for which kind of optimizations can be performed on multi threaded code
- If no memory model exists, compilers apply no optimizations to multi-threaded code or assume single-threaded execution, leading to bugs
- Weak memory models allow more reordering than strong memory models, making certain proofs harder or impossible
# Sources
- [Wikipedia](https://en.wikipedia.org/wiki/Memory_model_(programming)