# Topic summary
A reliable and efficient randomness source is a fundamental component in cryptographic applications. Efficient pseudo-random number generators (PRNG) are deterministic, but otherwise cannot be distinguished from real randomness sources.
The input of a PNRG, which is called seed, is a relatively small amount of random bits, which defines the PRNG's initial state. For making the PRNG secure, a reliable entropy source is needed for seeding the PRNG. The purpose of this topic is to study the process and available methods for extracting the seed from an entropy source.

# References
* https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-90B.pdf
* https://en.wikipedia.org/wiki/Randomness_extractor