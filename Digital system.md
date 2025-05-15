# DIGITAL ELECTRONICS


## Table of Contents

- [What is Digital Electronics?](#what-is-digital-electronics)
- [Applications of Digital Electronics](#applications-of-digital-electronics)
- [Digital vs Analog Signals](#digital-vs-analog-signals)
- [Logic Levels](#logic-levels)
- [Number system](#Number-system)

---

## What is Digital Electronics?

**Digital Electronics** is a field of electronics involving digital signals that use binary values (0 and 1) to represent information. It forms the basis of all modern computing devices, utilizing logic gates and circuits to perform operations.

Unlike analog electronics, where signals vary continuously, digital systems work with discrete voltage levels which makes them less susceptible to noise and easier to process.

---

## Applications of Digital Electronics

Digital electronics play a crucial role in various industries and applications:

- **Computing Devices:** Microprocessors, RAM, ROM, and hard drives
- **Communication Systems:** Mobile phones, satellites, and networking equipment
- **Consumer Electronics:** Smart TVs, cameras, and home automation systems
- **Automotive Systems:** Electronic control units, ABS, and infotainment
- **Medical Equipment:** MRI scanners, digital thermometers, ECG monitors
- **Industrial Automation:** PLCs, robotics, and smart control systems

---

## Digital vs Analog Signals

| Feature              | Digital Signal         | Analog Signal          |
|----------------------|------------------------|------------------------|
| Signal Type          | Discrete               | Continuous             |
| Noise Immunity       | High                   | Low                    |
| Data Representation  | Binary (0 and 1)       | Infinite values        |
| Transmission Quality | Less signal degradation| Prone to distortion    |
| Processing           | Simple & Efficient     | Complex                |
| Examples             | Computer data, logic circuits | Audio signals, sensors |

---

## Logic Levels

Logic levels refer to voltage ranges used to represent digital values:

- **Logic 0 (Low):** Typically 0V
- **Logic 1 (High):** Typically 3.3V, 5V, or other depending on the logic family

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
`1011` = (1×2^3) + (0×2^2) + (1×2^1) + (1×2^0) 
= 8 + 0 + 2 + 1
= **11 (Decimal)**

---

### Decimal (Base 10)
- **Digits**: `0–9`  
- **Each position** = power of 10  

Example:  
`253` = (2×10^2) + (5×10^1) + (3×10^0) 
= 200 + 50 + 3 
= **253 (Decimal)**

---

### Octal (Base 8)
- **Digits**: `0–7`  
- **Each position** = power of 8  

Example:  
`145` = (1×8^2) + (4×8^1) + (5×8^0) 
= 64 + 32 + 5 
= **101 (Decimal)**

---

### Hexadecimal (Base 16)
- **Digits**: `0–9` and `A–F`  
- **Each position** = power of 16  

Example:  
`2F` 
2 -> = (2×16^1) + 
E -> = (15×16^0) 
= 32 + 15 
= **47 (Decimal)**

---

## 3. Conversions Between Number Systems

### A. Binary to Decimal
1. Write the binary number.
2. Multiply each digit by 2^position (from right to left).
3. Add the results.

Example:  
`1101` = (1×2^3) + (1×2^2) + (0×2^1) + (1×2^0) 
= 8 + 4 + 0 + 1
= **13**

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

Example: `1A`


= (1×16^1) + (10×16^0) 
= 16 + 10 
= **26**

---

### E. Binary to Hexadecimal
1. Split binary into groups of 4 (from right).
2. Convert each group to hexadecimal.

Example: `11010110`
`11010110`=1101|0110
→ `1101` 
= D,
`0110` 
= 6  
**Hex: D6**

---

### F. Hexadecimal to Binary
1. Convert each hex digit to 4-bit binary.

Example: `2F`  
2 = `0010`,
F = `1111`  
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

Example: `145` = (1×8^2) + (4×8^1) + (5×8^0) 
= 64 + 32 + 5 
= **101**

---

### I. Binary to Octal
1. Group binary digits into 3s from the right.
2. Convert each group to octal.

Example: `101101`
→ `000 101 101` 
→ `0 5 5`
→ **Octal: 55**

---

### J. Octal to Binary
1. Convert each octal digit to 3-bit binary.

Example: `7` 
= `111`, 
`4` = `100`  
**Octal 74
→ Binary: 111100**

---
## Importance of Number Systems in Digital Systems

- Digital devices (like computers) only understand two states: ON and OFF. These are represented using `1` and `0`, which is **binary**.
- Number systems allow us to **store, process, and communicate** data efficiently in digital circuits.
- **Octal and Hexadecimal** make it easier for humans to read and write large binary numbers.
- Using number systems helps in **designing hardware** and **writing software** for digital systems.
- 
- # Logic Gates 


---

## 1. AND Gate

**Function:**
The AND gate outputs HIGH (1) only when all its inputs are HIGH. It performs a logical multiplication operation.

**Symbol:**


![AND Gate](https://github.com/16-supritha/Digital-_Electronics_Internship/blob/b603f1f72208815c54bad21a5cb0b3010dff0d65/and%20gate.png)


**Boolean Function:**
```
Output = A * B
```

**Truth Table:**
|  INP A |  INP B | Output Y |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   0    |
| 1 | 0 |   0    |
| 1 | 1 |   1    |

**Applications:**
- Digital circuits
- Multiplication operations in ALUs
- Input validation

---

## 2. OR Gate

**Function:**
The OR gate outputs HIGH (1) if at least one input is HIGH. It performs a logical addition operation.

**Symbol:**
```
  ![image](https://github.com/user-attachments/assets/f28a85ff-f485-4797-9208-147a4ccc13fd)
 
```

**Boolean Function:**
```
Output = A + B
```

**Truth Table:**
| INPA |INP B | Output Y |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   1    |
| 1 | 0 |   1    |
| 1 | 1 |   1    |

**Applications:**
- Alarm systems
- Logic decision making
- Enable signal generation

---

## 3. NOT Gate

**Function:**
The NOT gate, or inverter, outputs the opposite of the input signal. It changes 0 to 1 and 1 to 0.

**Symbol:**
```
![NOTGate](https://github.com/16-supritha/Digital-_Electronics_Internship/blob/3afe1e87947a8aa19fa0f6dc30adabe74ead265a/not%20gate.png)

**Boolean Function:**
```
Output = A'
```

**Truth Table:**
|   A | Output  |
|---|--------|
| 0 |   1    |
| 1 |   0    |

**Applications:**
- Signal inversion
- Control signal logic

---

## 4. NAND Gate

**Function:**
The NAND gate gives the opposite output of an AND gate. It outputs LOW only when all inputs are HIGH.

**Boolean Function:**
```
Output = (A * B)'
```

**Truth Table:**
| INPA | INPB | Output Y |
|---|---|--------|
| 0 | 0 |   1    |
| 0 | 1 |   1    |
| 1 | 0 |   1    |
| 1 | 1 |   0    |

**Applications:**
- Universal gate
- Memory circuits (latches)

---

## 5. NOR Gate

**Function:**
The NOR gate gives the opposite output of an OR gate. It outputs HIGH only when all inputs are LOW.

**Boolean Function:**
```
Output = (A + B)'
```

**Truth Table:**
| INP A |INP  B | Output Y |
|---|---|--------|
| 0 | 0 |   1    |
| 0 | 1 |   0    |
| 1 | 0 |   0    |
| 1 | 1 |   0    |

**Applications:**
- Oscillators
- Control logic

---

## 6. XOR Gate

**Function:**
The XOR gate outputs HIGH when the number of HIGH inputs is odd. It’s used in circuits where bit comparison is needed.

**Boolean Function:**
```
Output = A ⊕ B
```

**Truth Table:**
| INP A | INP B | Output Y |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   1    |
| 1 | 0 |   1    |
| 1 | 1 |   0    |

**Applications:**
- Parity checks
- Adders (half adder)

---

## 7. XNOR Gate

**Function:**
The XNOR gate outputs HIGH when the inputs are the same. It is the complement of the XOR gate.

**Boolean Function:**
```
Output = (A ⊕ B)'
```

**Truth Table:**
| INP A |INP B | Output Y|
|---|---|--------|
| 0 | 0 |   1    |
| 0 | 1 |   0    |
| 1 | 0 |   0    |
| 1 | 1 |   1    |

**Applications:**
- Equality detection
- Comparator circuits

---



