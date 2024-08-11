# CS 131 Fall 2023: Brewin# Interpreter

This repository contains my interpreter for [CS 131](https://ucla-cs-131.github.io/fall-23-website/)'s quarter-long project. The interpreter written in Python is for a made up object oriented programming language called Brewin#. The final part of the project spec are as follows:

1. [Project #4 Spec](https://docs.google.com/document/d/17tXuOYUlmCjMELna94cM-pp47AMLXr_6_2htWdlsB7o/edit)

Starting bootstrapping code:

- `intbase.py`, the base class and enum definitions for the interpreter
- `brewparse.py`, which contains the `parse_program` function to parse Brewin programs
- `brewlex.py`, which contains helper functions for brewparse.py

## Features supported by Brewin#

Objects - instantiation, fields, methods, comparison, prototypal inheritance

Functions - first-class functions, lambda functions, closures, pass by reference/value

Operations - assignment, binary operations, unary operations, basic arithmetic

Control flow - functions, if statements, while loops, return statements

Variables - string, int, bool, nil types supported; limited type coercion is supported

## Licensing and Attribution

This is an unlicensed repository; even though the source code is public, it is **not** governed by an open-source license.

Boilerplate code was primarily written by [Carey Nachenberg](http://careynachenberg.weebly.com/), with support from his TAs for the [Fall 2023 iteration of CS 131](https://ucla-cs-131.github.io/fall-23-website/).
