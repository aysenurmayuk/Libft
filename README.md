# Libft Project

The Libft project is an essential part of the curriculum at 42 schools, designed to help students build a strong foundation in C programming. In this project, students are tasked with creating their own library of standard C functions, which can then be used in future projects throughout the curriculum.

## Purpose

The main goal of the Libft project is to familiarize students with the basics of programming in C and to deepen their understanding of fundamental programming concepts such as memory management, string manipulation, and data structures. By creating their own library of standard functions, students gain hands-on experience in implementing common programming tasks from scratch, which helps reinforce their understanding of the C language and its standard library.

## Features

- Contains a wide range of functions commonly used in C programming, including string manipulation functions (`ft_strlen`, `ft_strcpy`, `ft_strcat`, etc.), memory management functions (`ft_memset`, `ft_memcpy`, `ft_memmove`, etc.), and character manipulation functions (`ft_isalpha`, `ft_toupper`, `ft_tolower`, etc.).
- Provides a comprehensive set of functions for validating and converting data types, parsing input, and performing mathematical calculations.

## Usage

To use the Libft library in your projects, simply include the `libft.h` header file and link your source code with the compiled library. You can compile the library by running `make` in the root directory of the project, which will generate a `libft.a` static library file.

```bash
gcc -o my_program my_program.c -L. -lft
