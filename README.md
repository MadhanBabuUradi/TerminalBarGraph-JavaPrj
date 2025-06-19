## 📊 Terminal Bar Graph in Java

This Java program takes 10 integer inputs from the user and visually represents them as horizontal bar graphs directly in the terminal using Unicode characters.

### 🚀 Features

- Accepts 10 numbers from the user.
- Displays each number as a horizontal bar made of block characters.
- Uses Unicode characters:
  - `█` (U+2588) for full blocks
  - `▜` (U+259C) for half blocks (used for odd numbers to show the extra unit)
- Efficiently separates original values from visual components for clarity.

---

### 🧪 Sample Output

If the user enters:
```
10 15 8 7 9 12 13 6 4 5
```

The terminal will display something like:
```
████10
██████▜15
███4
███▜7
████▜9
██████6
██████▜13
███3
██2
██▜5
```

---

### 🛠️ How It Works

1. Takes 10 integer inputs and stores them in an array.
2. Determines if a number is odd or even to know whether to add a partial block.
3. Divides each number by 2 to scale the bar length.
4. Displays a horizontal bar using `█` and optionally `▜` for odd numbers.

---

### 📌 Usage

To run the program:

```bash
javac terminal_bar_graph.java
java terminal_bar_graph
```

Input your 10 numbers when prompted.

---

### 🧠 Concepts Used

- Arrays
- Loops
- ASCII and Unicode character handling
- Integer division and modulo
- Terminal output formatting

---


### 👨‍💼 Author

Developed by Madhan Babu Uradi -   
📧 Reach me on: https://www.linkedin.com/in/madhanbabuuradi/
