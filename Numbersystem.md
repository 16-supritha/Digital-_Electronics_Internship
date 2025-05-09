# Number Systems - Beginner Friendly Documentation

This guide will help you understand number systems and how to convert between them. Everything is explained simply so everyone can understand.

---

## 1. What Are Number Systems?
A number system is a way to represent numbers. Different number systems use different bases:
- **Binary (Base 2)** - Uses 0 and 1
- **Decimal (Base 10)** - Our usual system; uses 0 to 9
- **Hexadecimal (Base 16)** - Uses 0 to 9 and A to F (A=10, B=11, ..., F=15)

---

## 2. Binary, Decimal, Hexadecimal Explained

### Binary (Base 2)
- Digits: 0, 1
- Each position is a power of 2

Example: `1011` = (1×2³) + (0×2²) + (1×2¹) + (1×2⁰) = 8 + 0 + 2 + 1 = **11 (Decimal)**

### Decimal (Base 10)
- Digits: 0–9
- Each position is a power of 10

Example: `253` = (2×10²) + (5×10¹) + (3×10⁰) = 200 + 50 + 3 = **253 (Decimal)**

### Hexadecimal (Base 16)
- Digits: 0–9 and A–F
- Each position is a power of 16

Example: `2F` = (2×16¹) + (15×16⁰) = 32 + 15 = **47 (Decimal)**

---

## 3. Conversions Between Number Systems

### A. Binary to Decimal
1. Write the binary number.
2. Multiply each digit by 2^position (right to left).
3. Add the results.

Example: `1101` = (1×2³) + (1×2²) + (0×2¹) + (1×2⁰) = 8 + 4 + 0 + 1 = **13**

### B. Decimal to Binary
1. Divide the number by 2.
2. Write down the remainder.
3. Repeat until the result is 0.
4. Read remainders from bottom to top.

Example: `13`
```
13 ÷ 2 = 6 remainder 1
6 ÷ 2 = 3 remainder 0
3 ÷ 2 = 1 remainder 1
1 ÷ 2 = 0 remainder 1
```
Binary: **1101**

### C. Decimal to Hexadecimal
1. Divide the number by 16.
2. Write down the remainder.
3. Repeat until the result is 0.
4. Read remainders from bottom to top.

Example: `254`
```
254 ÷ 16 = 15 remainder 14 → E
15 ÷ 16 = 0 remainder 15 → F
```
Hex: **FE**

### D. Hexadecimal to Decimal
1. Convert letters to numbers (A=10, ..., F=15).
2. Multiply each digit by 16^position.
3. Add the results.

Example: `1A`
= (1×16¹) + (10×16⁰) = 16 + 10 = **26**

### E. Binary to Hexadecimal
1. Split binary into groups of 4 (from right).
2. Convert each group to hexadecimal.
3. Example: `11010110`
→ `1101` = D, `0110` = 6
Hex: **D6**

### F. Hexadecimal to Binary
1. Convert each hex digit to 4-bit binary.

Example: `2F`
2 = 0010, F = 1111 → Binary: **00101111**

---

