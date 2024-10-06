# -String-processing


## Description

This project implements a `StringProcessor` class in Java, which provides several string and arithmetic processing methods. These methods include:

- **isStrongPassword(String password)**: Checks if a password is strong (must contain an uppercase letter, a lowercase letter, a digit, and a special symbol).
- **calculateDigits(String sentence)**: Counts the number of digits in a given sentence.
- **calculateWords(String sentence)**: Counts the number of words in a sentence.
- **calculateExpression(String expression)**: Evaluates an arithmetic expression containing numbers, basic operations (+, -, *, /), and parentheses.

## Features

- **Strong password checking**: Ensures password complexity for better security.
- **Digit and word counting**: Useful for text analysis.
- **Arithmetic expression evaluation**: Parses and computes arithmetic expressions including parentheses.

## Requirements

- **Java**: Make sure you have Java installed. You can download it from [here](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/YourUsername/StringProcessor.git
    ```
2. Navigate to the project directory:
    ```bash
    cd StringProcessor
    ```

## How to Run

1. Compile the `StringProcessor.java` file:
    ```bash
    javac StringProcessor.java
    ```
2. Run the `StringProcessor` class:
    ```bash
    java StringProcessor
    ```

You will be prompted to input a password, sentence, and arithmetic expression for testing each method.

## Example Usage

```bash
Enter a password: P@ssw0rd
Is strong password: true

Enter a sentence: The year is 2024!
Number of digits: 4

Enter another sentence: Hello World
Number of words: 2

Enter an arithmetic expression: (10 + 5) * 2
Result of the expression: 30.0
