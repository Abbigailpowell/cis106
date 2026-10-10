# Notes 3 — Linux GUI, CLI, and Commands

## 1. What is a graphical user interface (GUI)?

A **graphical user interface (GUI)** is a way of using a computer by interacting with things you can see on the screen. Instead of typing commands, you can use windows, icons, menus, and a mouse or keyboard.

**Example**
* Clicking on a folder to open it
* Using a web browser
* Moving files by dragging them into another folder

## 2. What is a desktop environment?

A **desktop environment** is the part of a Linux system that provides the graphical desktop that the user interacts with. It includes things like windows, menus, icons, and applications.

**Example**
* GNOME
* KDE Plasma
* Xfce

## 3. What is the command line interface (CLI)?

A **command line interface (CLI)** is a way to communicate with the computer by typing commands. Instead of clicking on icons and menus, you type a command and the computer gives you a result.

**Example**

bash
date

This command displays the current date and time.

## 4. How do I access the command line interface (CLI)?

There are several ways to access the command line in Linux. You can open a **terminal emulator** from the graphical desktop. You can also use a **virtual console** by switching to another console using a keyboard shortcut.
From a Linux desktop, you can open the Terminal application  and start typing commands.
**Example**
ls -l /home/user

## 5. What is a virtual console?

A **virtual console** is a text-based way to access Linux without using the graphical desktop. Linux can have multiple virtual consoles running at the same time. A virtual console can be useful if the graphical interface is not working or if you need to work directly from the command line.

## 6. What is a terminal emulator?

A **terminal emulator** is a program that gives you access to the command line while you are using a graphical desktop.

**Examples**
* GNOME Terminal
* Konsole
* xterm

The terminal emulator lets you type commands and see the results without leaving the graphical desktop.

## 7. What is bash?

**Bash** stands for **Bourne Again Shell**. It is a shell that allows users to interact with the Linux operating system by typing commands. Bash can also be used to run scripts and automate tasks.

**Example**
bash
echo Hello

This tells Bash to display the word `Hello`.

## 8. What is the shell prompt?

The **shell prompt** is the text shown in the terminal that tells you the shell is ready for you to enter a command.

**Example**
bash
$
When you see the prompt, you can type a command and press Enter.

# Linux Commands

## `clear`

### Definition:
The `clear` command clears the text from the terminal screen.

### Usage
It is useful when the terminal has become cluttered and you want a clean screen.

### Example
bash
clear

## `echo`

### Definition

The `echo` command displays text or other information on the screen.

### Usage

It can be used to print messages or display the value of something.

### Example
bash
echo Hello World

* Output
Hello World

## `date`

### Definition

The `date` command displays the current date and time.

### Usage

It can be used when you need to quickly check the system's date and time.

### Example

bash
date

## `free`

### Definition

The `free` command displays information about the computer's memory.

### Usage

It can be used to check how much memory is being used and how much is available.

### Example
bash
free

## `uname`

### Definition

The `uname` command displays information about the system.

### Usage

It can be used to find information about the Linux system and kernel.

### Example

bash
uname -a
The `-a` option displays more information about the system.

## `history`

### Definition

The `history` command shows commands that were previously entered into the terminal.

### Usage

It is useful when you want to find a command you used earlier without typing it again.

### Example

bash
history

## `man`

### Definition

The `man` command displays the manual page for a command.

### Usage

It is useful for learning how a command works, including its options and how to use it.

### Example
bash
man echo
This opens the manual page for the `echo` command.

## `tldr`

### Definition

`tldr` provides shorter and easier-to-read examples for Linux commands.

### Usage

It is useful when the regular `man` page has too much information and you just want to see common examples.

### Example
bash
tldr echo
This gives examples of how to use the `echo` command.

## `cheat`

### Definition

The `cheat` command is used to display cheat sheets for commands.

### Usage

It can be useful when you want to quickly look up how to use a command.

### Example
bash
cheat echo
This displays information and examples for using `echo`.

## `hostname`

### Definition

The `hostname` command displays the name of the computer.

### Usage

It can be used to find the name assigned to the Linux computer.

### Example

bash
hostname

## `df`

### Definition

The `df` command shows information about the amount of disk space available on file systems.

### Usage

It can be used to check how much storage space is being used and how much is still available.

### Example

bash
df -h 

## `du`

### Definition

The `du` command shows how much disk space files and directories are using.

### Usage

It can help you find out which files or folders are taking up storage space.

### Example

bash
du -h

## `figlet`

### Definition

The `figlet` command displays text in large letters made from characters.

### Usage

It can be used to make text stand out in the terminal.

### Example
bash
figlet Linux

This displays the word **Linux** using large ASCII-style letters.
