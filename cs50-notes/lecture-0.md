# CS50x: Lecture 0 - Scratch

---

## Tools

- **cs50.dev** is the CS50 VS Code version.
- In the terminal, typing `code chat.py` creates a `chat.py` file where I can write code.
- In the terminal, typing `python chat.py` runs the chat.py program.
- The virtual rubber duck by CS50 is **cs50.ai**.

---

## Number Systems

- **Unary notation / base 1:** single digit
- **Binary / base 2:** two digits, that are 0 and 1
- **Decimal / base 10:** 10 digits

A **binary digit** in short is a **bit**.

Binary is good because it only says two things: **on and off**, according to the analogy of switching a bulb on and off.

### Place Values

Let's generalise this placing system:

| 4 | 2 | 1 |
|:-:|:-:|:-:|
| # | # | # |

So in binary we represent numbers like this:

- `001` is 1
- `010` is 2
- and so on

So it's 3 bits, that is, it can count only up to **7**.

### Bytes

**8 bits = 1 byte**

| 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |

8 bits can count up to **255** and total possibilities are **256** (including zero).

---

## Representing Data

### Letters and Symbols: ASCII

To represent alphabets or colors or symbols we have to assign particular notations in binary. For example, for capital letter **A**, `01000001` i.e. **65** is assigned.

- After 65 it is consistent up to **Z**.
- **ASCII** stands for American Standard Code for Information Interchange.
- There is a consistent gap between capital letters and small letters, i.e. a difference of **32**.
- ASCII represents 8 bits, so it can only represent 256 characters.

### Unicode

ASCII is not the only system we use, though it was the earliest. Now we also use **Unicode**, which has more room than ASCII and stores more symbols and characters like emojis, colors, and letters of different languages.

- Unicode has 16/24/32 bits per character.
- With a 32-bit character you can have approx. 4 billion representations.

### Color: RGB

We use **3 bytes** to represent a color. Each byte is 8 bits, and each byte assigned to **R**, **G** and **B** can represent shades from 0 to 255.

- `0, 0, 0` represents **black**
- `255, 255, 255` is **white**

### Music

But how do we represent music?

- Frequency
- Amplitude
- Duration

---

## Computational Thinking

**Algorithms:** step-by-step instructions for solving problems

**Code**

**Pseudocode:** step-by-step instructions in English in a proper way

### Building Blocks

- Functions
- Conditions
- Boolean
- Loop, etc.

### Compiler

A compiler is just a program that translates one language to another.

---

## Scratch

**scratch.mit.edu**

> Practice Scratch!!!!

*This is it for Lecture 0.*
