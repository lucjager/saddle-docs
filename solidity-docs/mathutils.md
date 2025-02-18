A library to be used in conjunction with SafeMath. Contains functions for calculating
differences between two uint256.

# Functions:

- [`within1(uint256 a, uint256 b)`](#MathUtils-within1-uint256-uint256-)
- [`difference(uint256 a, uint256 b)`](#MathUtils-difference-uint256-uint256-)

# Function `within1(uint256 a, uint256 b) → bool` {#MathUtils-within1-uint256-uint256-}

Compares a and b and returns true if the difference between a and b
is less than 1 or equal to each other.

## Parameters:

- `a`: uint256 to compare with

- `b`: uint256 to compare with

## Return Values:

- True if the difference between a and b is less than 1 or equal,
  otherwise return false

# Function `difference(uint256 a, uint256 b) → uint256` {#MathUtils-difference-uint256-uint256-}

Calculates absolute difference between a and b

## Parameters:

- `a`: uint256 to compare with

- `b`: uint256 to compare with

## Return Values:

- Difference between a and b
