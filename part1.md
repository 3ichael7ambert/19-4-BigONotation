## **Step One: Simplifying Expressions**

Simplify the following big O expressions as much as possible:

1. O(n + 10)
    Answer: O(n)

If n is 100, the difference between O(n + 10) and O(n) is negligible.

---
2. O(100 * n)
    Answer: O(n)

100 is a steady constant, the time compplexity scales to n

---
3. O(25)
    Answer:  O(1)

No matter what the input will always be 25, making the time always the same



---
4. O(n^2 + n^3)
    Answer:  O(n^3)

    The hihest order, n^3, is the time complexity

O(n^2 + n^3) = O(n*n + n*n*n)

---
5. O(n + n + n + n)
    Answer: O(n)

    Although n inputs 4 times its similar to saying O(n*4) or O(n) the time of operations is always based on n.



---
6. O(1000 * log(n) + n)
    Answer: O(n)

        This scales with n.

    From Intro: "The logarithm of a number roughly measures the number of times you can divide that number by 2 before you get a value that’s less than or equal to one."



---
7. O(1000 * n * log(n) + n)
    Answer:  O(n * log(n)) 

    The scaling of n * log n is the largest time complexity.

---
8. O(2^n + n^2)
    Answer:<!--  O(n^2) --> O(2^n)

I chose O(n^2) at first but the solution is O(2^n), for this I will say it has to do with the exponetial growth.

---
9. O(5 + 3 + 1)
    Answer:  O(1)

 O(5+3+1) = O(9) however the input will constantly be 9, making the time be 1 operation, O(1)

---
10. O(n + n^(1/2) + n^2 + n * log(n)^10)
    Answer: <!-- O(n * log(n)^10) --> O(n^2)

I chose O(n * log(n)^10) at first but the solution is O(n^2)
I dont know why