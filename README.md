# Linux Terminal Commands Cheatsheet

This document provides a concise overview of essential **Linux commands** organized by category, making it easier to learn and practice in the terminal.

---

## I. File and Directory Management

These commands help you navigate, create, manipulate, and remove files and directories:

- **`pwd`** (print working directory): Shows the full path of the current directory.
- **`ls`** (list): Lists files and directories.
  - **`ls -l`**: Shows detailed information (permissions, owner, size, date).
  - **`ls -la`**: Lists all files including hidden ones.
- **`cd`** (change directory): Moves between directories.
  - `cd Documents/` → Go to a specific folder.  
  - `cd ..` → Go up one level.  
  - `cd ~` → Go to your home directory.  
- **`mkdir`** (make directory): Creates a new directory.  
- **`rmdir`** (remove directory): Removes an **empty** directory.  
- **`rm`** (remove): Deletes files.  
  - `rm -r` → Deletes a folder and all its contents (**use with caution!**).  
- **`cp`** (copy): Copies files.  
  - `cp -R` → Copies entire directories recursively.  
- **`mv`** (move): Moves or renames files/directories.  
- **`touch`**: Creates an empty file or updates a file’s timestamp.  

---

## II. Viewing and Editing Files

- **`echo`**: Displays text.  
  - `echo "Hello Linux" > file.txt` → Overwrites file content.  
  - `echo "New line" >> file.txt` → Appends to a file.  
- **`cat`**: Displays file content.  
- **`head`**: Shows the first 10 lines (default).  
  - `head -n 20 file.txt` → First 20 lines.  
- **`tail`**: Shows the last 10 lines (default).  
  - `tail -n 20 file.txt` → Last 20 lines.  
- **`less`**: Interactive viewer for large files (supports search and navigation).  

---

## III. Text Editor `vi`

`vi` is a powerful text editor inside the terminal.  

- **Modes**:  
  - *Normal mode* → Navigate.  
  - *Insert mode* → Edit text.  
  - *Command mode* → Save, quit, etc.  

- **Navigation**:  
  - `G` → End of file.  
  - `1G` → Beginning of file.  
  - `/word` → Search for "word".  
  - `n` → Next match.  

- **Editing**:  
  - `i` → Insert before cursor.  
  - `a` → Insert after cursor.  
  - `x` → Delete character.  
  - `dd` → Delete entire line.  

- **Copy & Paste**:  
  - `yy` → Copy line.  
  - `p` → Paste after cursor.  

- **Save & Exit**:  
  - `:w` → Save.  
  - `:q` → Quit.  
  - `:wq` → Save and quit.  
  - `:q!` → Quit without saving.  

---

## IV. Compression & Decompression

- **`zip`**: Compress files into `.zip`.  
  - `zip -r archive.zip folder/` → Recursive compression.  
- **`unzip`**: Extract `.zip` files.  
  - `unzip archive.zip`  
- **`tar`**: Create and extract `.tar.gz` archives.  
  - `tar -czvf file.tar.gz folder/` → Compress.  
  - `tar -xzvf file.tar.gz` → Extract.  

---

## V. Useful Commands

- **`clear`**: Clears the terminal screen.  
- **`man`** (manual): Displays help for a command.  
  - Example: `man ls`  

---

## VI. Wildcards

Wildcards help match multiple files:  

- **`?`** → Matches exactly one character.  
  - Example: `ls file?.txt` → Matches `file1.txt`, `fileA.txt`.  
- **`*`** → Matches zero or more characters.  
  - Example: `ls file*.txt` → Matches `file.txt`, `file1.txt`, `fileABC.txt`.  

---

## 🚀 Final Tip

Mastering Linux commands requires **practice and experimentation**. Open your terminal, try them out, and combine them to become more efficient in your daily workflow.  

---

## Author
**Bárbara Ángeles Ortiz**

<img src="https://github.com/user-attachments/assets/30ea0d40-a7a9-4b19-a835-c474b5cc50fb" width="115">

[LinkedIn](https://www.linkedin.com/in/barbaraangelesortiz/) | [GitHub](https://github.com/BarbaraAngelesOrtiz)

![Status](https://img.shields.io/badge/status-finished-brightgreen) 📅 Agosto 2025

![Python](https://img.shields.io/badge/python-3.10-blue)

## Agradecimientos 

<img width="180" height="180" alt="Screenshot 2025-08-13 034705" src="https://github.com/user-attachments/assets/bdfa03bc-d44a-4848-b622-6bac4e2dbc95" />
