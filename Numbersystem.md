# Number Systems 

---

## 1. What Are Number Systems?

"A number system in digital electronics is a method of representing numbers using a specific set of symbols or digits". It defines how numbers are expressed and processed in digital circuits. The commonly used number systems are:

- **Binary (Base 2)** - Uses `0` and `1`  
- **Decimal (Base 10)** - Our everyday system; uses `0` to `9`  
- **Octal (Base 8)** - Uses `0` to `7`  
- **Hexadecimal (Base 16)** - Uses `0` to `9` and `A` to `F` (A=10, B=11, ..., F=15)

---

## 2. Number Systems Explained

### Binary (Base 2)
- **Digits**: `0`, `1`  
- **Each position** = power of 2  

Example:  
`1011` = (1×2^3) + (0×2^2) + (1×2^1) + (1×2^0) = 8 + 0 + 2 + 1 = **11 (Decimal)**

---

### Decimal (Base 10)
- **Digits**: `0–9`  
- **Each position** = power of 10  

Example:  
`253` = (2×10^2) + (5×10^1) + (3×10^0) = 200 + 50 + 3 = **253 (Decimal)**

---

### Octal (Base 8)
- **Digits**: `0–7`  
- **Each position** = power of 8  

Example:  
`145` = (1×8^2) + (4×8^1) + (5×8^0) = 64 + 32 + 5 = **101 (Decimal)**

---

### Hexadecimal (Base 16)
- **Digits**: `0–9` and `A–F`  
- **Each position** = power of 16  

Example:  
`2F` = (2×16^1) + (15×16^0) = 32 + 15 = **47 (Decimal)**

---

## 3. Conversions Between Number Systems

### A. Binary to Decimal
1. Write the binary number.
2. Multiply each digit by 2^position (from right to left).
3. Add the results.

Example:  
`1101` = (1×2^3) + (1×2^2) + (0×2^1) + (1×2^0) = 8 + 4 + 0 + 1 = **13**

---

### B. Decimal to Binary
1. Divide the number by 2.
2. Write down the remainder.
3. Repeat until the result is 0.
4. Read remainders from bottom to top.

Example: 13  
13 ÷ 2 = 6 remainder 1  
6 ÷ 2 = 3 remainder 0  
3 ÷ 2 = 1 remainder 1  
1 ÷ 2 = 0 remainder 1  
**Binary: 1101**

---

### C. Decimal to Hexadecimal
1. Divide the number by 16.
2. Write down the remainder.
3. Repeat until the result is 0.
4. Read remainders from bottom to top.

Example: 254  
254 ÷ 16 = 15 remainder 14 → `E`  
15 ÷ 16 = 0 remainder 15 → `F`  
**Hex: FE**

---

### D. Hexadecimal to Decimal
1. Convert letters to numbers (A=10, ..., F=15).
2. Multiply each digit by 16^position.
3. Add the results.

Example: `1A` = (1×16^1) + (10×16^0) = 16 + 10 = **26**

---

### E. Binary to Hexadecimal
1. Split binary into groups of 4 (from right).
2. Convert each group to hexadecimal.

Example: `11010110` → `1101` = D, `0110` = 6  
**Hex: D6**

---

### F. Hexadecimal to Binary
1. Convert each hex digit to 4-bit binary.

Example: `2F`  
2 = `0010`, F = `1111`  
**Binary: 00101111**

---

### G. Decimal to Octal
1. Divide the decimal number by 8.
2. Write down the remainder.
3. Repeat until the result is 0.
4. Read remainders from bottom to top.

Example: 100  
100 ÷ 8 = 12 remainder 4  
12 ÷ 8 = 1 remainder 4  
1 ÷ 8 = 0 remainder 1  
**Octal: 144**

---

### H. Octal to Decimal
1. Multiply each digit by 8^position.
2. Add the results.

Example: `145` = (1×8^2) + (4×8^1) + (5×8^0) = 64 + 32 + 5 = **101**

---

### I. Binary to Octal
1. Group binary digits into 3s from the right.
2. Convert each group to octal.

Example: `101101` → `000 101 101` → `0 5 5` → **Octal: 55**

---

### J. Octal to Binary
1. Convert each octal digit to 3-bit binary.

Example: `7` = `111`, `4` = `100`  
**Octal 74 → Binary: 111100**

---
## Importance of Number Systems in Digital Systems

- Digital devices (like computers) only understand two states: ON and OFF. These are represented using `1` and `0`, which is **binary**.
- Number systems allow us to **store, process, and communicate** data efficiently in digital circuits.
- **Octal and Hexadecimal** make it easier for humans to read and write large binary numbers.
- Using number systems helps in **designing hardware** and **writing software** for digital systems.
