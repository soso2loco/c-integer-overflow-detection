# c-integer-overflow-detection
# Integer Overflow Detection in C

## Description

This program asks the user to enter two integers and calculates their sum.
After performing the addition, the program checks whether integer overflow occurred.

Overflow can happen when the result of adding two integers exceeds the maximum or minimum value that can be stored in an integer. The program determines if:

* **Positive overflow** occurred (two positive numbers produce a negative result)
* **Negative overflow** occurred (two negative numbers produce a positive result)
* **No overflow** occurred

The program then prints the result of the addition and reports the overflow status.



## Concepts Demonstrated

* User input using `scanf`
* Integer arithmetic in C
* Conditional statements (`if`, `else if`, `else`)
* Detecting integer overflow using logical conditions

---

## How to Compile

Use the GNU C compiler:

```
gcc overflow.c -o overflow
```

---

## How to Run

```
./overflow
```

The program will prompt you to enter two integers.

Example:

```
Please enter two numbers: 2000000000 2000000000
2000000000 + 2000000000 = -294967296
Positive overflow occurred
```

---

## Files in this Project

* `overflow.c` – C source code for the program
* `README.md` – Project documentation

---

## Author
Soleil Brewer
