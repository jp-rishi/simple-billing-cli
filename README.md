# Simple Billing System (C++)

A minimal command-line billing and invoicing program written in C++.
Originally built as a high school project, later cleaned up and documented.

## Overview

This project is a simple terminal-based billing system that allows users to:

* Create and manage invoices
* Add items with prices and quantities
* Calculate totals
* Display structured billing information in the console

It focuses on core C++ concepts and logic rather than UI or external dependencies.

## Features

* Command-line interface (no GUI)
* Itemized billing
* Automatic total calculation
* Lightweight and fast
* No external libraries required

## Tech Stack

* Language: C++
* Interface: Terminal / CLI
* Paradigm: basic OOP

## Getting Started

### Compile

```bash
g++ product.cpp -o billing
```

### Run

```bash
./billing
```

## Example Usage

```
Enter item name: Apple
Enter price: 2
Enter quantity: 3

Total: 6
```

## Project Structure

```
/product.cpp   -> entry point
```


## Why This Project Exists

This was originally created as a learning exercise to practice:

* Input/output handling
* Basic data structures
* Program flow and logic

It represents an early step in learning C++ and software development.

## Possible Improvements

* File saving/loading for invoices
* Better input validation
* Modular class-based design
* Unit tests
* Enhanced CLI UX

## License

MIT License (or whatever you prefer)
