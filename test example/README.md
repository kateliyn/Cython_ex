# Cython Example

This is a simple example demonstrating the use of Cython to speed up Python code by incorporating C functions.

## Requirements

- Cython
- Setuptools

## Installation

```bash
$ python setup.py build_ext --inplace
```

## Usage
Run the main program:

```bash
$ python main.py
```
  
How it Works
The example.pyx file contains a simple Cython function add_numbers that adds two numbers.  
The setup.py file is used to build the Cython extension.  
The main program (main.py) imports and uses the Cython function to add numbers.
