# Notes 6 – Linux Commands

## 1. mkdir

### Definition
The **mkdir** command stands for **make directory**. It is used to create a new directory (folder) in Linux.

### Usage/Formula

`mkdir directory_name`

### Examples
Create a directory named `projects`:

`mkdir projects`

Create multiple directories at once:

`mkdir school work personal`


## 2. touch

### Definition
The **touch** command is used to create an empty file. If the file already exists, it updates the file's timestamp without deleting its contents.

### Usage/Formula
`touch file_name`

### Examples
Create an empty file named `notes.txt`:

`touch notes.txt`

Create multiple files at once:

`touch notes1.txt notes2.txt notes3.txt`


## 3. rm

### Definition
The **rm** command stands for **remove**. It is used to delete files and directories in Linux.

### Usage/Formula
`rm file_name`

### Examples

Delete a file named `notes.txt`:

`rm notes.txt`

Delete a directory and everything inside it:

`rm -r projects`


## 4. cp

### Definition
The **cp** command stands for **copy**. It is used to make a copy of a file or directory and place it in another location. The original file stays where it is.

### Usage/Formula
`cp source destination`

### Examples

Copy a file and give the copy a new name:

`cp notes.txt notes_backup.txt`

Copy a file into another directory:

`cp notes.txt documents/`


## 5. mv

### Definition
The **mv** command stands for **move**. It is used to move files or directories to another location. It can also be used to rename files and directories.

### Usage/Formula
`mv source destination`

### Examples

Rename a file from `notes.txt` to `linux_notes.txt`:

`mv notes.txt linux_notes.txt`

Move a file into another directory:

`mv linux_notes.txt documents/`
