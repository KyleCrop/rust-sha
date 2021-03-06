# rust-sha
Rust Secure Hash Algorithm (SHA) Intrinsics Library

## Introduction

Intel claims that SHA-1 and SHA-256 instruction set extensions (collectively known as the [SHA Extensions](https://en.wikipedia.org/wiki/Intel_SHA_extensions)) are due to be included in [Skylake](https://en.wikipedia.org/wiki/Skylake_(microarchitecture)) sometime in 2015, and ARM has almost no documentation on the subject, so until more information is available, the hardware accelerated versions are disabled by default. 

## Conclusion

If by chance you are running this code on a newer ARM or x86 with these instructions available, and their specifications have not changed, then you will have to manually uncomment the "//pub mod x86;" in [mod.rs](https://github.com/andydude/rust-cryptoil/blob/master/src/sha1/mod.rs) yourself.

Good luck.
