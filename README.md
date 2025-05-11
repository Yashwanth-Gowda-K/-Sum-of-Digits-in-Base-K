# -Sum-of-Digits-in-Base-K


# Sum of Digits in Base K

A Python implementation to convert a number from base 10 to any other base and calculate the sum of its digits in the new base.

## Problem Statement
Given an integer `n` (in base 10) and a base `k`, the program:
1. Converts `n` to base `k`
2. Calculates the sum of its digits in base `k`

## Mathematical Approach
The conversion uses repeated division:
1. Divide `n` by `k` and record the remainder (rightmost digit)
2. Update `n` to be the quotient
3. Repeat until `n` becomes 0
4. Sum all remainders (digits) obtained
