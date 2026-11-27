# Note 8: Text Commands

## 1. `cat` Command

### Definition
The `cat` command is used to displaying the contents of a file in the terminal. Cat is short for concatenate.

### Usage / Formula

`cat [option] filename `

### Examples
**Example 1: Display the contents of a file.**

`cat notes.txt`

This displays everything inside `notes.txt`.

**Example 2: Display line numbers.**

`cat -n notes.txt`

This displays the file with line numbers.


## 2. `tac` Command

### Definition
The `tac` command displays the contents of a file in reverse order. It prints the last line first and the first line last. It is the opposite of `cat`.

### Usage / Formula

`tac [option] filename`

### Examples
**Example 1: Display a file in reverse order.**

`tac notes.txt`

This displays the last line of the file first.

**Example 2: Reverse the contents of another file.**

`tac report.txt notes.txt`

This prints the lines of `report.txt` from bottom to top.


## 3. `head` Command

### Definition
The `head` command displays the beginning of a file. By default, it shows the first 10 lines. It is useful when you only need to see the beginning of a large file.

### Usage / Formula
`head [option] filename`

### Examples
**Example 1: Display the first 10 lines.**

`head notes.txt`

This displays the first 10 lines of `notes.txt`.

**Example 2: Display the first 5 lines.**

`head -5 notes.txt`

This displays only the first 5 lines.


## 4. `tail` Command

### Definition
The `tail` command displays the end of a file. By default, it shows the last 10 lines. It is useful for checking the last information entered into the files.

### Usage / Formula

`tail [option] filename`

### Examples
**Example 1: Display the last 10 lines.**

`tail notes.txt`

This displays the last 10 lines of `notes.txt`.

**Example 2: Display the last 5 lines.**

`tail -5 notes.txt`

This displays only the last 5 lines.


## 5. `cut` Command

### Definition
The `cut` command is used to extract specific sections of text from a file and display it onto the screen.

### Usage / Formula

`cut [option] filename`

### Examples
**Example 1: Extract a specific field.**

`cut -d ',' -f 1 students.csv`

This displays the first field from each line, using a comma as the separator.

**Example 2: Extract multiple fields.**

`cut -d ',' -f 1,3 students.csv`

This displays the first and third fields from the file.


## 6. `sort` Command

### Definition
The `sort` command is used for sorting files, arranges lines in a text file in a particular order. By default, it sorts alphabetically.

### Usage / Formula

`sort [option] filename`

### Examples
**Example 1: Sort file.**

`sort names.txt`

This displays the lines in alphabetical order.

**Example 2: Sort in reverse order.**

`sort -r names.txt`

This displays the lines in reverse alphabetical order.


## 7. `wc` Command

### Definition
The `wc` command stands for word count. It counts the number of lines, words, and bytes in a file. It is useful for finding out how much information a file contains.

### Usage / Formula

`wc [option] filename`


### Examples

**Example 1: Count lines, words, and bytes.**

`wc notes.txt`

This displays the number of lines, words, and bytes in the file.

**Example 2: Count the lines.**

`wc -l notes.txt`

This displays only the number of lines.
