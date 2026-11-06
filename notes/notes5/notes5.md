# Notes 5 – Navigating the Linux File System

## 1. Linux Commands

### 1.1 `ls` 

**Definition:**

The `ls` command is used for listing the content of a given directory or the file/directory itself. It allows me to see what is inside a folder without having to open each file individually. 

**Usage/Formula:**

* `ls + options + directory to list`

- `ls` – Lists files and directories.
- `options` – How the information is displayed.
- `directory` – Specifies which directory to list.

**Examples:**

1. List the files and directories in the current directory:

   `ls`

2. Display hidden files and directories:

   `ls -a`

3. List the contents of a specific directory:

   `ls ~/Documents`

### 1.2 `pwd` 

**Definition:**

The `pwd` command stands for Print Working Directory. It displays the full path of the directory I am currently working in. 

**Usage/Formula:**

`pwd`

**Examples:**

1. Display the current working directory:

   `pwd`

Example output:

   `/home/abbigail/cis106`

2. Print physical path

   `pwd -P `

### 1.3 `cd`

**Definition:**

The `cd` command stands for Change Directory. It allows me to move from one directory to another in the Linux file system. I can use it to enter folders, move back to a directory, or return to home directory of the current user.

**Usage/Formula:**

`cd + destination`

- `destination` - it can be an absolute path or relative path.

**Examples:**

1. Move into the Documents directory:

   `cd Documents`

2. Return to my home directory:

   `cd`

## 2. Variables and the Linux File System

### 2.1 What is a variable?

A variable is a named location used to store information with the shell for us with other commands in the script. In Linux, variables allows tou hold different types of information, such as text, numbers, or directory paths.

For example:

`name="Abbigail"`

This creates a variable named `name` and stores the text `Abbigail` inside it.

### 2.2 How do I use a variable?

Use a variable by placing a dollar sign (`$`) before its name. This tells the shell to use the value stored inside that variable.

For example:
```
name="Abbigail" 
echo "$name" 
```
Output:
`Abbigail`

The `echo` command displays the value stored in the variable. The value inside the variable can also change.

```
name="Student"
echo "$name"
```
Output:
`Student`

### 2.3 What is an environment variable?

An environment variable is used by the shell to track specific system information and user information, to determine things like the user's home directory, username, and locations where programs are stored.

Some common environment variables include:
- `HOME` – Stores the path to the current user's home directory.
- `USER` – Stores the current username.

**Examples:**
Display the current user's home directory:

`echo "$HOME"`

Display the current username:

`echo "$USER"`

### 2.4 What is a user defined variable?

A user defined variable are created by the user and exist only in the script and sunshell that runs the script. I can give it a name and assign it a value depending on what I need.

For example:

`course="CIS106"`

To display the value:

`echo "$course"`

Output:

`CIS106`

## 3. Linux Directory Structure

### 3.1 What is the root directory?

The root directory is the main directory at the top of the Linux file system. It is represented by a forward slash (`/`). All other files and directories are organized underneath it, directories such as `/home` is located under the root directory.


### 3.2 What does "Parent Directory" mean?

A parent directory is the directory that is one level above the directory your currently inside. In Linux, two dots (`..`) represent the parent directory.
Get to the parent directory by using:

`cd ..`


### 3.3 What does "Current working directory" mean?

The current working directory is the folder your currently working in while using the Linux terminal. Commands such as `ls` use this directory by default when I do not specify another location.
Check current working directory by using:
`pwd`

### 3.4 What is an absolute path? Include an example.

An absolute path is the complete location of a file or directory starting from the root directory (`/`). It gives the exact location without depending on which directory your currently working in.

**For example**:

`/home/abbigail/Documents/notes5.md`

This path starts at the root directory and shows each directory leading to the file.

### 3.5 What is a relative path? Include an example.

A relative path is a location that is based on my current working directory instead of starting from the root directory. It tells Linux where to go based on where I am already located.

**For example**, if my current working directory is:
`/home/abbigail`

I can use this command:

`cd Documents`

This moves me into:

`/home/abbigail/Documents`

### 3.6 What is the difference between "Your home directory" and "The home directory"?

**The home directory (`/home`)** is the main directory that contains the individual home directories for regular users.

**Your home directory** is the specific personal directory assigned to your own user account. For example, if my username is `abbigail`, my home directory would be: /home/abbigail

To return to my own home directory:
`cd ~`