Implementation of SHA256 in python:

SHA256 is part of the SHA2 family of hash functions, which are used to ensure data integrity and the authenticity of messages. It's widely utilized in digital signatures, especially in structures like ECDSA and XMSS/LMS. The most critical components of SHA2 are the message schedule and compression functions, which need careful implementation to prevent side-channel attacks.

Specifications:
Input size: Arbitrary size (less than 2^64 bits)
Block size: 512 bits
Output size: 256 bits
Number of rounds: 64


