GitHub Link:
https://github.com/danmar0801/Quantum-Program


Youtube Video Link:
https://www.youtube.com/watch?v=RktC2XLLqQI&ab_channel=DanyMarcha

# Shor's Algorithm for Integer Factorization

This is a Python implementation of Shor's algorithm for integer factorization using Qiskit. The algorithm is capable of factoring large integers into their prime factors, which is an important problem in number theory with applications in cryptography.

## Requirements
To run this project, you will need to have the following software installed:

1. Python 3
2. Qiskit

## Usage
To factorize an integer using Shor's algorithm, you can modify the N variable in the code to specify the integer you want to factorize. The algorithm will find a random integer a such that gcd(a, N) = 1, and then use quantum operations to find the period r of the function f(x) = a^x mod N.

Once the period r is found, the algorithm can use classical algorithms to factorize N into its prime factors. The factors of N will be printed to the console.

## Limitations
It's worth noting that Shor's algorithm is not practical for large numbers due to the current limitations of quantum computers. This implementation is intended for educational purposes only and is not optimized for performance.
