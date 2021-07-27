# const-fnv1a-hash
Rust based const FNV1A hashing implementation for hashing at compile time. 

This is a Rust implementation of FNV1A hashing algorithms which works on the stable channel.

# Features
- no_std.
- All functions are const, and can be used at compile time to hash all the things.
- Additional convenience functions for str hashing.
- dependency free.
- 16 bit hashing implemented using XOR folding.