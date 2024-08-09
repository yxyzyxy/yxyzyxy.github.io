---
permalink: /ent/
title: "Number Theory and Crytography"
excerpt: "page for number theory"
author_profile: false
redirect_from: 
  - /nut/
  - /nt/
  - /nut.html
---
2024-2025

  * Instructor: [Young Kim](https://yxyzyxy.github.io/)
  * Main Text: Number Theory by Pommersheim, Marks, Flapan
    * [Textbook](https://drive.google.com/file/d/1ukws6VYOhGW4ATlJA-4aA0jrcP24paRJ/view?usp=sharing) (Log in required)
  * Further Readings:
    * Elementary Methods in Number Theory by Nathanson
    * A Classical Introduction to Modern Number Theory by Ireland and Rosen
---

"Mathematics is the queen of the sciences—and number theory is the queen of mathematics.''- Carl Friedrich Gauss

Number theory, which is the study of the integers, is one of the oldest branches of math and is still an active field of research today.
The goal for this exploration is to learn how math is about rigorous creativity in exploring different ideas and structures.
We will also focus on applying these techniques to crytography.

Below, you will find writeups and worksheets under [topics](#Topics) and [sample problems](#Sample-problems).

## Topics
  * [Pythagorean Triples](/files/ent/ptriples.pdf)
  * [Mathematical Induction](/files/ent/induction.pdf)
  * Primes, Composites, and Sieves
  * Division Algorithm
  * Euclidean Algorithm
  * Diophantine Equations
  * Fundamental Theorem of Arithmetic
  * Modulo tables
  * Modular Arithmetic (Number tricks, ISBNs, Calendars)
  * Rings and Fields
  * Basic Ciphers
  * Sun-Zi Theorem (Chinese Remainder Theorem)
  * Modular Exponentiation
  * Fermat's Little Theorem
  * RSA Encryption
  * Sum of Squares


## Sample problems:
  1. Prove that $3^{512}$ has a remainder of 0 when divided by 1024.
  2. Find the last 3 digits of $2025^{2024^{2023}}$.
  3. Does the function $f(x) = x^2 + x + 41$ always spit out primes for positive integers $x$? 
  4. A composite number n is called a psuedoprime to base b if gcd(b,n) = 1 and $b^{n-1} -1$ is divisible by $n$. Prove that 1729 is a pseudoprime to bases 2,3, and 5.
  5. How do the rational points on the unit circle parametrize all Pythagorean triples?
  6. For any given year, the Doomsday is defined as the day of the week of the last day of February in that year (e.g. Doomsday of 2007 is Wednesday since the last day of February 2007 was Wednesday, February 28.) Find the Doomsday of 2025 and the Doomsday of 6512. 

Some particular types of encryption:
  1. Caesar ciphers
  2. Exponentiation
  3. RSA Encryption algorithm (public and private key)
  5. Elliptic Curves (if time permits)
We will learn enough programming in Python to be able to perform encryption algorithms.
