# algoC Programming Language

Welcome to **algoC**, a new programming language built using Python. This language aims to simplify algorithmic expressions and make programming more intuitive.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Syntax and Examples](#syntax-and-examples)
    - [Variables and Expressions](#variables-and-expressions)
    - [Control Flow](#control-flow)
    - [Loops](#loops)
    - [Functions](#functions)
    - [Lists](#lists)
5. [Contributing](#contributing)
6. [License](#license)

## Introduction

algoC is designed to be a straightforward, readable language with an emphasis on clarity and simplicity. It's perfect for learning algorithms, prototyping, and educational purposes.

## Features

- Simple and clear syntax
- Supports variables, arithmetic operations, and comparisons
- Control flow with `si` (if), `sinon_si` (elif), and `sinon` (else)
- Loop constructs with `pour` (for) and `tant_que` (while)
- Function definitions
- List operations

## Installation

To install algoC, follow these steps:

1. **Clone the Repository**

    ```sh
    git clone git@github.com:Chaabane2k03/AlgoC.git
    ```

2. **Navigate to the Directory**

    ```sh
    cd algoc
    ```

3. **Install Dependencies**

    Ensure you have Python installed (version 3.6 or later). Then install required dependencies:

    ```sh
    pip install -r requirements.txt
    ```

4. **Run the Interpreter**

    ```sh
    python shell.py
    algoC > RUN("example.algoc")
    ```

## Syntax and Examples

### Variables and Expressions

Define variables using the `variable` keyword and assign values using the `=` operator.

```algoC
variable x = 10
variable y = 5
variable z = x + y * 2
ecrire(z)  # Output: 20
```

### Control Flow

Use `si`, `sinon_si`, and `sinon` for conditional statements.

```algoC
si x > y faire
    ecrire("x is greater than y") 
sinon_si x == y faire
    ecrire("x is equal to y") 
sinon
    retourner("x is less than y") 
fin
```

### Loops

`pour` loops are used for iterating a specific number of times.

```algoC
pour i = 1 a 10 faire
    ecrire(i)
fin
```

`tant_que` loops are used for repeating a block of code while a condition is true.

```algoC
variable n = 5
tant_que n > 0 faire
    ecrire(n)
    n = n - 1
fin
```

### Functions

Define functions using the `fonction` keyword.

```algoC
fonction add(a, b)
    retourner a + b
fin

variable sum = add(3, 4)
ecrire(sum ) # Output: 7
```

### Lists

Create lists using square brackets.

```algoC
variable myList = [1, 2, 3, 4, 5]
ecrire(myList[2])  # Output: 3
```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Make sure to follow the project's coding standards and include tests for new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Enjoy programming with algoC! If you encounter any issues or have suggestions, please open an issue on the GitHub repository.
