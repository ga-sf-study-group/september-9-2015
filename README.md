# september-9-2015

Calculate Change

Given a price and amount of money given, write a function calculate_change to calculate the amount of change to return. Return value should be an object/hash with keys of pennies, nickels, dimes, quarters, dollar_bills, five_dollar_bills, ten_dollar_bills, and twenty_dollar_bills.

For example, calculate_change(76.89, 100) would return: {pennies: 1, nickels: 0, dimes: 1, quarters: 0, dollar_bills: 3, five_dollar_bills: 0, ten_dollar_bills: 0, twenty_dollar_bills: 1}

----

Rotate Array

Given an array and number of steps, rotate the array to the right by k steps. 

For example, with array = [1,2,3,4,5,6,7] and k = 3, array is rotated to [5,6,7,1,2,3,4].

----

Spiral Matrix

Given a matrix of m x n elements (m rows, n columns), return all elements of the matrix in spiral order.
For example, given the following matrix:
[
 [ 1, 2, 3 ],
 [ 4, 5, 6 ],
 [ 7, 8, 9 ]
]

Returns [1,2,3,6,9,8,7,4,5].

----

Count Primes

Count the number of prime numbers less than a non-negative number, n.

----

FizzBuzz

Write a function that prints the numbers from 1 to 50. But for multiples of three print "Fizz" instead of the number and for the multiples of five print "Buzz". For numbers which are multiples of both three and five print "FizzBuzz".

----

Letter Combinations of a Phone Number

Given a digit string, return all possible letter combinations that the number could represent. (Check out your cellphone to see the mappings) 

For example, Input: "23", Output: ["ad", "ae", "af", "bd", "be", "bf", "cd", "ce", "cf"].

----

Fibonacci

Write a function to print the first n numbers in a fibonacci series. Fibonacci series is series of natural numbers where next number is equivalent to sum of previous two number e.g. fn = fn-1 + fn-2. 
The first 2 numbers in the fibonacci series are always  1, 1.

----

Add Binary

Given two binary strings, return their sum (also a binary string).

For example, a = "11", b = "1", the return is "100".

----

Decode Numbers

You are given an encoded message containing only numbers. You are also provided with the following mapping:

A : 1
B : 2
C : 3
...
Z : 26

Given an encoded message, count the number of ways it can be decoded.

INPUT:

Your program should accept as its first argument a path to a filename. Each line in this file is a test-case and contains an encoded message of numbers. E.g.

1
2
12
123
You may assume that the test cases contain only numbers.

OUTPUT:

Print out the different number of ways it can be decoded. E.g.

1
2
2
3
NOTE: 12 could be decoded as AB(1 2) or L(12). Hence the number of ways to decode 12 is 2.
