# blake3
Hardware implementation of the Blake3 hash function

## Status
Just started. Not completed. **Does Not Work. Do. NOT. Use.**


## Introduction
(Text borrowed from the [BLAKE3
repository](https://github.com/BLAKE3-team/BLAKE3)

BLAKE3 is a cryptographic hash function that is:
* much faster than MD5, SHA-1, SHA-2, SHA-3, and BLAKE2.
* Secure, unlike MD5 and SHA-1. And secure against length extension, unlike SHA-2.
* Highly parallelizable across any number of threads and SIMD lanes, because it's a Merkle tree on the inside.
* Capable of verified streaming and incremental updates, again because it's a Merkle tree.
* A PRF, MAC, KDF, and XOF, as well as a regular hash.
* One algorithm with no variants, which is fast on x86-64 and also on smaller architectures.

BLAKE3 is based on an optimized instance of the established hash
function BLAKE2 and on the original Bao tree mode. For more info, see
the [BLAKE3 paper](https://github.com/BLAKE3-team/BLAKE3-specs/blob/master/blake3.pdf)


The core implements the general BLAKE3 function.
