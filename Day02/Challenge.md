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

## Common Flags

- l: Long format listing. Displays detailed information (permissions, owner, size, and modification date) for each file.
- a: Shows all files, including hidden ones (files starting with a dot).
- i: Displays the inode number (a unique identifier for each file) alongside the file names.
- d: Lists directories themselves, not their contents.


