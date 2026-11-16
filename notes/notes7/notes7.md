# Notes 7 - Wildcards 

## The Asterisk (*) Wildcard

The asterisk (`*`) matches zero or more characters. It can represent any number of characters in a filename.

**Examples:**
- `ls *.txt` - Lists all files that end with `.txt`.
- `ls report*` - Lists files that start with `report`.
- `ls *20*` - Lists files that contain `20` anywhere in the filename.

## The Question Mark (?) Wildcard

The question mark (`?`) matches exactly one character. It is useful  when working with hidden files and when you know most of a filename but want to match one unknown character.

**Examples:**
- `ls file?.txt` - Lists files such as `file1.txt` or `fileA.txt`.
- `ls ?.txt` - Lists files with one character before `.txt`.
- `ls report?.pdf` - Lists files such as `report1.pdf` or `reportA.pdf`.

## The Square Brackets ([]) Wildcard

Square brackets match exactly one character from a group or range of characters. 
Wildcard uses `[! ]` to reverse the match.

**Examples:**
- `ls file[a-z].txt` - Matches filenames with one lowercase letter in that position.
- `ls report[0-9].pdf` - Matches report filenames with one number in that position.
- `ls file[!1].txt` - Matches files with one character in that position except `1`.


## Brace Expansion
Brace expansion is a feature in Bash that generates argument strings, allowing you to create multiple filenames or directories using one command. Instead of typing each directory name separately, you can place the names inside curly braces `{}` and separate them with commas.

Brace expansion is useful when creating multiple directories with the same parent directory.

### Example 1: Creating Multiple Directories

`mkdir {documents,images,videos}`

This command creates three directories:

- documents
- images
- videos

### Example 2: Creating a Directory Structure

`mkdir -p wallpapers/cars/{1080p,2k,4k}`

This command creates the following directory structure:

wallpapers/
- cars/
    - 1080p/
    - 2k/
    - 4k/

The -p option creates the parent directories if they do not exist.

### Example 3: Using Number Ranges

`mkdir week{1..5}`

This command creates five directories named:

- week1
- week2
- week3
- week4
- week5
