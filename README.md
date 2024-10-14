# Happiness
Happiness calculator using integer sets
# Happiness Calculator

## Description

The Happiness Calculator is a Python program that computes your happiness based on an array of integers and two disjoint sets, **A** and **B**. You gain happiness for each integer you like (contained in set **A**) and lose happiness for each integer you dislike (contained in set **B**). The program iterates through the array and provides a final happiness score.

## Features

- Calculate total happiness based on two disjoint sets.
- Efficient membership checking using sets.
- Handles large input sizes, up to 100,000 integers.

## Requirements

- Python 3.x

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/bondpapi/Happiness
   `cd happiness-calculator`

## Usage

1. Run the program:

    `python happiness_calculator.py`

2. Provide input in the following format:

    -First line: Two integers n and m, where n is the number of integers in the array, and m is the number of integers in sets A and B.

    -Second line: A space-separated list of n integers (the array).

    -Third line: A space-separated list of m integers (set A).

    -Fourth line: A space-separated list of m integers (set B).

# Example Input

`5 3`

`1 5 3 4 2`

`1 3 5`

`7 4 6`

# Output

`2`

## How It Works

The program reads the input values and converts sets A and B into sets for quick lookup.
It iterates through the array, adjusting the happiness score based on the presence of each integer in sets A or B.
The final happiness score is printed as output.
Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

# License

This project is licensed under the MIT License. See the LICENSE file for more details.

# Contact

For any inquiries or issues, please contact Michael Bond at bondpapi@yahoo.com