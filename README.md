# Prime Factor Analysis & Sorting Tool (C++)

## Description
A technical C++ application designed to decompose integers into their prime constituents and organize the results using classic sorting algorithms. The project features an optimized primality test and a descending-order Bubble Sort implementation.


## Key Technical Features
* **Optimized Primality Testing**: Features an `isPrime` function utilizing trial division with a mathematical optimization (checking $i$ and $i+2$ while incrementing by 6) to reduce computational overhead.
* **Bubble Sort Implementation**: Includes a custom `bubbleSort` function specifically configured to organize integer arrays in descending order.
* **Prime Factorization Logic**: Implements a search loop to identify all unique prime divisors of a user-provided integer.
* **Memory Management**: Utilizes fixed-size arrays with safety checks for storing calculated divisors.

## Execution Logic
1. **Data Acquisition**: The program prompts the user for a target integer $n$.
2. **Decomposition**: It iterates through potential divisors, validating each one against the `isPrime` logic.
3. **Array Population**: Found prime factors are stored sequentially in the `primeDivisors` array.
4. **Data Organization**: The `bubbleSort` function is called to rearrange the factors from largest to smallest.
5. **Output**: The sorted list of prime divisors is presented in the console.

## How to Build
1. Requirements: C++ compiler (GCC, Clang, or MSVC).
2. Compilation: `g++ main.cpp -o factor_sorter`
3. Run: `./factor_sorter`

## Learning Objectives
* Mastering number theory fundamentals (Prime factorization).
* Implementing and understanding the mechanics of Bubble Sort.
* Optimizing conditional loops for performance-critical tasks.
