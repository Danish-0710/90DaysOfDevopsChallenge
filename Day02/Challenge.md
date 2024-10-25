# Basic Linux Commands

## Learning Objectives

By the end of this document, you will:
- Understand the purpose of basic Linux commands.
- Be able to navigate the file system using directory commands.
- Learn how to list files and directories with various options.
- Gain familiarity with creating directories.

## Key Concepts

1. **File System**: The way files and directories are organized on your computer.
2. **Command Line Interface (CLI)**: A text-based interface to interact with the computer, as opposed to a graphical user interface (GUI).
3. **Flags/Options**: Special arguments you can add to commands to modify their behavior (e.g., `-l`, `-a`).
4. **Directories**: Folders that contain files and other directories.

## Overview

Linux is an operating system that uses a command line interface for users to interact with it. This document outlines some basic commands that are essential for navigating and managing files in Linux. 

### Listing Commands

The `ls` command is used to list files and directories in your current location.

### Syntax
```bash
ls [option_flag] [arguments]
```

## Common Flags

- l: Long format listing. Displays detailed information (permissions, owner, size, and modification date) for each file.
- a: Shows all files, including hidden ones (files starting with a dot).
- i: Displays the inode number (a unique identifier for each file) alongside the file names.
- d: Lists directories themselves, not their contents.

## Examples:

- ls -l:
Shows files in a detailed list format. Useful for seeing file permissions and sizes.

- ls -a:
Lists all files, including hidden files (like .bashrc).

- ls *.sh:
Lists all files that end with the .sh extension (often shell scripts).

- ls -i:
Displays the inode numbers of files, which can be helpful for file management tasks.

- ls -d */:
Lists only directories in the current path.


## Directory Commands

1. **Print Working Directory**
- Command: pwd
What it does: Displays your current location in the file system. Think of it as asking, "Where am I right now?"

2. **Change Directory**
- Command: cd path_to_directory
What it does: Changes your current location to the specified directory. You can think of it as moving into a folder.

3. **Shortcut: cd ~ or just cd**
What it does: Takes you back to your home directory (the main folder for your user account).

4. **Command: cd -**
What it does: Switches back to the last directory you were in.

5. **Command: cd ..**
What it does: Moves one level up in the directory structure (to the parent folder).

6. **Command: cd ../..**
What it does: Moves two levels up in the directory structure.

7. **Make Directory**
- Command: mkdir directoryName
What it does: Creates a new directory with the specified name.



## Examples:

mkdir newFolder                # Creates a new folder named 'newFolder'.

mkdir .NewFolder               # Creates a hidden directory (prefixing with '.' hides it).

mkdir A B C D                  # Creates multiple directories ('A', 'B', and 'C') at once.

mkdir /home/user/Mydirectory   # Creates a directory in a specific location.

mkdir -p A/B/C/D               # Creates nested directories (if 'A' and 'B' don’t exist, they'll be created).


## Conclusion
Understanding these basic commands will help you navigate and manage files in Linux effectively. Practice using them to become more comfortable with the command line interface!


