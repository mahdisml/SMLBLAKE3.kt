# SMLBLAKE3.kt
Kotlin BLAKE3 implementation (cryptographic hash function )

Mahdi Safarmohammadloo

Based on https://github.com/BLAKE3-team/BLAKE3

Special Thanks to rctcwyvrn !

He Translated Blake3 reference implementation from Rust to Java https://github.com/rctcwyvrn/blake3

AND

I Optimized and Translated it to Kotlin

It's not fast as native implementation of Rust(and java jni native)

BENCHMARK :

* blake3KotlinFromJava(auto translated from java) = 1029 ms

* blake3Java = 293 ms

* smlblake3.kt = 269 ms

* sha1   = 222 ms

* sha256 = 149 ms

* sha512 = 101 ms

* blake3Native(java jni) = 22 ms                 
