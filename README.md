# FizzBuzz

## What is this project?

This project is the simple "FizzBuzz" program written in Java.

The idea of this project is to print numbers from 1 to 100, but coming with some guidelines:

1. If a number is divisible by 3, print "Fizz" instead of a number
2. If a number is divisible by 5, print "Buzz" instead of a number
3. If a number is divisible by 3 and 5, print "FizzBuzz" instead of a number
4. Otherwise, print the original number.

A for loop is used to repeat numbers from 1-100. In the loop it checks if the number is divisible by 3, 5, or both, using the following condition:

```java
 if (i % 3 == 0 && i % 5 == 0)