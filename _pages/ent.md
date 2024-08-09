---
permalink: /ent/
title: "Number Theory and cryptography"
excerpt: "page for number theory"
author_profile: true
redirect_from: 
  - /nut/
  - /nt/
  - /nut.html
---
2024-2025
          
  * Instructor: [Young Kim](https://yxyzyxy.github.io/)
  * Main Text: Number Theory by Pommersheim, Marks, Flapan
    * [Textbook](https://drive.google.com/file/d/12hlPJ-97kd89FtDE16ze1AyskNnSMSQ3/view?usp=sharing) (Log in required)
  * Further readings: 
      * Elementary Methods in Number Theory by Nathanson
      * A Classical Introduction to Number Theory by Ireland and Rosen 

---

> Mathematics is the queen of the sciences—and number theory is the queen of mathematics.
-Carl Friedrich Gauss

Number theory, which is the study of the integers, is one of the oldest branches of math and is still an active field of research today.
The goal for this exploration is to learn how math is about rigorous creativity in exploring different ideas and structures.
We will also focus on applying these techniques to cryptography.

If you're interested in joining, please fill out [this form](https://forms.gle/9rDSk2H9pSFd1qrk7). 
Familiarity with Algebra 2/Precalculus is assumed.

### Topics

  1. [Pythagorean Triples](/files/ent/ptriples.pdf)
  2. [Mathematical Induction](/files/ent/induction.pdf)
  3. Primes, Composites, and Sieves
  4. Division Algorithm
      1. Base n number systems
      2. p-adic numbers (geometry)
  5. Euclidean Algorithm
  6. Fibonacci Numbers
  7. The Golden Ratio
  8. Diophantine Equations
  9. Fundamental Theorem of Arithmetic
  10. Modulo tables
  11. Modular Arithmetic (Number tricks, ISBNs, Calendars)
  12. Euclidean Rings and Fields
  13. Basic Encryption Schemes
  14. Sun-Zi Theorem (Chinese Remainder Theorem)
  15. Modular Exponentiation
  16. Fermat's Little Theorem
  17. RSA Encryption
  18. Gaussian Integers
  19. Sum of Squares
      1. Fermat's sum of two squares
      2. Lagrange's sum of four squares

We will learn enough programming in Python to be able to perform encryption algorithms.

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
