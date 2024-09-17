# Advanced Mathematical Functions in Lean3

This Lean project contains implementations of various mathematical functions and operations, including:

- Basic arithmetic operations (doubling, factorial, exponentiation)
- Special sequences (Fibonacci, Padovan)
- Combinatorial functions (binomial coefficients, Stirling numbers)
- List operations (length, sum, square, reverse, zip addition)

## Author

Rodolfo Lopez

## Date

Fall 2022

## Installation

To run this project, you need to install Lean. The recommended way is to use elan, the Lean version manager:

1. Install elan:

   - On Unix-like systems (Linux, macOS):
     ```
     curl https://raw.githubusercontent.com/leanprover/elan/master/elan-init.sh -sSf | sh
     ```
   - On Windows:
     ```
     curl https://raw.githubusercontent.com/leanprover/elan/master/elan-init.ps1 -sSf | powershell -c -
     ```

2. Restart your terminal or run `source ~/.profile` (or equivalent for your shell).

3. Install Lean:

   ```
   elan install leanprover/lean4:stable
   ```

4. Verify the installation:
   ```
   lean --version
   ```

For more detailed instructions, visit the [Lean website](https://leanprover.github.io/lean4/doc/setup.html).

## Usage

Open the `hw3.lean` file in a Lean-compatible editor to view and evaluate the code.

## File Structure

- `hw3.lean`: Contains all the implementations of mathematical functions and operations

To test functions, use the `#eval` command in Lean, as demonstrated in the `hw3.lean` file.

## Key Concepts

The project covers the following Lean concepts:

- Recursive function definitions
- Pattern matching
- List operations
- Natural number operations

## Key Functions

- `double`: Doubles a natural number
- `factorial`: Computes the factorial of a natural number
- `myexp`: Computes exponentiation
- `fib`: Generates Fibonacci sequence terms
- `padovan`: Generates Padovan sequence terms
- `binom`: Computes binomial coefficients
- `stirling_one` and `stirling_two`: Compute Stirling numbers of the first and second kind
- `length`: Computes the length of a list
- `sumlist`: Sums all elements in a list of natural numbers
- `squarelist`: Squares every element in a list of natural numbers
- `reverse`: Reverses the order of elements in a list
- `zipadd`: Adds two lists of natural numbers element-wise
