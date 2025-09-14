# Node.js Basics – Command Line Arguments & Loops

This folder contains introductory Node.js scripts that practice js fundamentals like **command-line arguments**, **loops**, and **basic functions**.  

## 📌 Tasks

### 0. First constant, first print
- a constant variable called myVar is created with the value “JavaScript is amazing”
- Prints: `JavaScript is amazing`
  
### 1. 3 languages
- Prints: `“C is fun”`
`“Python is cool”`
`“JavaScript is amazing”`

### 2. Arguments
- Prints: `No argument`, `Argument found`, or `Arguments found` depending on the number of arguments.

### 3. Value of an argument
- Prints the **first argument** passed to the script.
- If no argument is passed → prints `No argument`.

### 4. Concatenation of arguments
- Prints two arguments in the format:
- `<firstArg> is <secondArg>`
- If any argument is missing, it prints `undefined`.

### 5. To integer
- Prints:
`My number: <first argument as integer>`
- If the first argument cannot be converted to an integer → prints `Not a number`.

### 6. Looping languages
- Prints 3 lines using a loop:
`C is fun
Python is cool
JavaScript is amazing`

### 7. Looping x times
- Prints `"C is fun"` **x times**, where `x` is the first argument.
- If `x` cannot be converted to an integer → prints `Missing number of occurrences`.

### 8. Square
- Prints a square using the character `X`.
- The size of the square is given as the first argument.
- If the argument is not a valid integer → prints `Missing size`.

### 9. Add
- Defines a function `add(a, b)` that returns the sum of two integers.
- Prints the result of adding the first and second arguments.
- If arguments are missing or invalid → prints `NaN`.



## 🚀 Usage
Run each script using:

```bash
node <script_name>.js <arguments>
