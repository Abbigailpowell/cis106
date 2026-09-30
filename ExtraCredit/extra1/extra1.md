# Extra Credit 1: Markdown

# Document 1: What is Linux

## Introduction

**Linux** is an operating system, similar to Windows, iOS, and Mac OS. It is used in many different types of technology, including smartphones, cars, supercomputers, home appliances, desktops, and servers. The article also explains that Linux is used on the Internet, at stock exchanges, and on many of the world's most powerful supercomputers.

An operating system manages the resources of a computer and allows software to communicate with the computer's hardware. Linux is made up of several important parts that work together to provide a complete operating system.

**Main Parts of Linux**
- Bootloader – The software that manages the boot process of the computer.
- Kernel – The main part of the Linux operating system.
- Init system – The system that manages processes after the computer starts.
- Daemons – Background services that perform different tasks.
- Graphical server – Provides the graphical system that allows applications and desktop environments to work.
- Desktop environment – Provides the graphical interface that users interact with.
Applications – Programs that allow users to perform different tasks.

## Why use Linux? 
One reason to use **Linux** is its reliability. The article also discusses the cost of Linux and explains that there can be no cost to download and install many Linux distributions. This can make Linux different from operating systems and server software that require a license. Another reason is security, Linux is less vulnerable to malware, ransomware, and viruses compared with some other operating systems. The article also connects Linux's security to its open-source development model.

![Linux Mascot](linxmascot.webp)

Linux is commonly represented by a penguin mascot called tux.

## Linux Distributions

![Linux Distrubution Logos](linuxlogos.jpg)

A **Linux distribution**, also called a distro, is a version of Linux that combines the operating system with different software and a particular desktop environment. Many Linux distributions can be downloaded for free. They can also be placed on a disk or USB drive and installed on a computer.

Some examples of Linux distribution are:

- Manjaro
- Ubuntu
- Antergos
- Solus
- Fedora
- Debian
- Linux Mint

## Linux Distribution Comparison

Choosing a **Linux distribution** depends on a few important questions.

Skill level, a person's experience with Linux can help determine which distribution they should use.

Some distributions recommended for beginners include:

- Linux Mint
- Ubuntu
- Elementary OS
- Deepin

For users with more experience, distributions such as Debian and Fedora. For highly skilled users, Gentoo is mentioned. The article also describes Linux From Scratch as an option for people looking for a challenge.

| Distribution | Description |
|---           |---          |
| Ubuntu | Beginner-friendly |
| Fedora | Modern Linux distribution |
| Debian | Stable Linux distribution |

## Linux Desktop Environment 
Desktop environments provide the graphical interface.

![Linux Desktop Screenshot](linxdesktopscreenshot.webp)

1. Cinnamon
2. KDE Plasma
3. Xfce

# Document 2: Python

## Getting started with PYthon 

**Python** is a simple programming language with straightforward syntax. LearnPython.org provides an interactive Python tutorial for people who are experienced programmers as well as people who are new to programming. 

## Learn the Basics

### Hello, World!

The simplest directive in Python is the print() function. It displays a line of text and automatically includes a new line. In Python 3, print is a function, so parentheses are required.

print("Hello, World!")
Hello, World!
Python uses indentation to define blocks of code instead of curly braces. The standard indentation in Python is four spaces.

### Variables and Types

Python does not require variables to be declared before they are used or require their type to be declared. Every variable in Python is an object. Python supports different types of numbers, including:

Integers – whole numbers
Floating point numbers – decimal numbers
Strings can be defined using either single quotes or double quotes.

String = "hello"
int = 20
float = 10.1

Operators can be used with numbers and strings, but mixing operators between numbers and strings is not supported.

### Lists

Lists are similar to arrays. They can contain any type of variable and can contain as many variables as needed. Lists can also be done over. Python uses a zero-based index when accessing items in a list. This means the first item has an index of 0, while the second item has an index of 1.

The append method can be used to add items to a list.
numbers = []
numbers.append(1)
numbers.append(2)

Trying to access an index that does not exist generates an error.

### Basic Operators

Basic operators can be used with numbers, strings, and lists. Arithmetic Operators that python support are addition, subtraction, multiplication, and division with numbers.

The modulo operator % returns the integer remainder of a division.
10 % 3
1

Using two multiplication symbols creates a power relationship.
2 ** 3
8

Operators with Strings using the addition operator can be used to join strings.

"Hello" + "World"
'HelloWorld'

Strings can also be multiplied to create a repeating sequence.

"Hello" * 3
'HelloHelloHello'

Operators with lists can be joined using the addition operator. The multiplication operator can also be used to create a repeating sequence of a list.

### String Formatting

Python uses C-style string formatting to create new, formatted strings. The % operator is used with a format string and variables. Some basic argument specifiers include:

%s – String or an object with a string representation
%d – Integers
%f – Floating point numbers
%.<number of digits>f – Floating point numbers with a fixed number of digits to the right of the decimal point
%x / %X – Integers in hex representation (lowercase/uppercase)

String formatting can be used to create formatted messages containing information from variables.

### Basic String Operations

Strings are pieces of text that can be defined using quotes "Hello world!", Strings can be assigned using either single or double quotes. Double quotes can be useful when the string itself contains single quotes. Python can perform different operations on strings. For example, the len function can be used to determine the length of a string.

Python uses zero-based indexing, so the first character has an index of 0. Characters can be accessed using brackets, and slices can be used to select part of a string. Negative numbers can also be used to start from the end of a string. Strings can be:

- Reversed using slice syntax
- Converted to uppercase
- Converted to lowercase
- Checked to see whether they start or end with specific text
- Split into multiple strings in a list

### Conditions

Python uses Boolean logic to evaluate conditions. Boolean values are True and False. The comparison operators are:

== – compares two values
!= – checks that two values are not equal
= – assigns a value to a variable

Python also uses Boolean operators such as:
and
or
not
The in operator can be used to check whether an object exists inside an iterable object, such as a list. 

Python uses indentation to define code blocks instead of brackets. The standard indentation is four spaces.An if statement can be used with conditions and code blocks.

The is operator unlike ==, which compares values, is compares the instances themselves.

### Loops

Python has two types of loops, for loops and while loops. A for loop iterates over a given sequence. For x in sequence:
    print(x)

For loops can also iterate over a sequence of numbers using the range function. The range function is zero based.

A while loop repeats as long as a Boolean condition is met.

while condition:
    print("Hello")

Python also provides break and continue statements. Break exits a for or while loop.
continue skips the current block and returns to the for or while statement.

Python can also use an else clause with loops. When the loop condition fails, the code in the else section is executed. If a break statement is used inside the loop, the else section is skipped.

# Document 3: Markdown Tables

## Table 1: Investments

| Id | Name | Email | Investments |
|---|---|---|---|
| 231 | Albert Master | albert.master@gmail.com | Bonds |
| 210 | Alfred Alan | aalan@gmail.com | Stocks |
| 256 | Alison Smart | asmart@biztalk.com | Residential Property |
| 211 | Ally Emery | allye@easyemail.com | Stocks |
| 248 | Andrew Phips | andyp@mycorp.com | Stocks |
| 234 | Andy Mitchel | andym@hotmail.com | Stocks |
| 226 | Angus Robins | arobins@robins.com | Bonds |
| 241 | Ann Melan | ann_melan@iinet.com | Residential Property |
| 225 | Ben Bessel | benb@hotmail.com | Stocks |
| 235 | Benson Romanolf | benr@albert.net | Bonds |

## Table 2: Grade Distribution

| Letter Grade | Percentage |
|---|---|
| A | 90 – 100% |
| B | 80 – 89.99% |
| C | 70 – 79.99% |
| D | 60 – 69.99% |
| F | < 60% |

## Table 3: Computer Parts

| Part | name |
|---|---|
| ![GPU](gpu.webp) | Graphics card |
| ![Hard Drive](harddrive.webp) | Hard Drive |
| ![Motherboard](motherboard.webp) | Motherboard |
| ![RAM](ram.webp) | RAM |
