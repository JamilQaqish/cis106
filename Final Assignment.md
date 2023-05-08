---
Name: Jamil Qaqish
Course: CIS 106
Semester: Spring 23
---

## Final Assignment

### Question 1
For every command in this list, include the following:
1. Description
2. Formula/Syntax
3. 3 Examples you understand

* awk: Allows users to process and manipulate data to produce formatted reports.
  * Ex1: Print a list of all the users in your system: `awk -F '{print $1}' /etc/passwd`
  * Ex2: Print a list of all the users in your system with their login shell: `awk -F '{print $1,$NF}' /etc/passwd`
  * Ex3: Repeat the previous command but make the usernames uppercase: `awk -F '{print toupper$1,$NF}' /etc/passwd`
  
* cat: reads each file parameter in sequence and writes it to standard output.
* Ex1: `cat todo.lst`
* Ex2: `cat ~/Documents/todo.lst`
* Ex3: `cat -b ~Documents/todo.md`
  
* cp: Use the cp command to create a copy of the contents of a file or directory.
* Ex1: `cp ~/Picutures/Dogs/ ~/Documents/Pets/`
* Ex2: `cp ~/Documents/Cats/ ~/Documents/Tabby/`
* Ex3: `cp ~/Downloads/file1 ~/Documents/files`
  
* cut: Cut out sections of a specified file or piped data and print the result to standard output.
* Ex1: `cut -d ':' -f1 /etc/passwrd`
* Ex2: `cut -d ':' -f1,7 /etc/passwd`
* Ex3: `cut -b 1-5 usernames.txt`
  
* grep: search for a string in groups of files.
* Ex1: `grep 'Harry Potter' ~/Documents/PrisonerOfAzkaban.txt` 
* Ex2: `grep -v 'Voldemort' ~/Documents/PrisonerOfAzkaban.txt`
* Ex3: `grep -o 'Ron Wesley' ~/Documents/PrisonerOfAzkaban.txt`
  
* head: writes to standard output a specified number of lines or bytes of each of the files or of the standard input.
* Ex1: `head ~/Documents/Book/dracula.txt`
* Ex2: `head -5 ~/Documents/Book/dracula.txt`
* Ex3: `head -10 ~/Documents/Book/dracula.txt` 
  
* ls: list the names and features of files and directories.
* Ex1: `ls ~/Documents/`
* Ex2: `ls ~/Documents/Dogs/`
* Ex3: `ls -l ~/Weekly Reports/`
  
* man: display the user manual of any command that we can run on the terminal.
* Ex1: `man printf`
* Ex2: `man 2 intro`
* Ex3: `man -f ls`
  
* mkdir: create or make new directories.
* Ex1: `mkdir HomeDecor`
* Ex2: `mkdir {dir1,dir2}`
* Ex3: `mkdir -v Pets`
  
* mv: move files and directories from one directory to another, or to rename a file or directory.
* Ex1: `mv sample.txt ~/Documents/`
* Ex2: `mv dir1 dir2`
* Ex3: `test.txt ~/TextFiles/`
  
* tac: display the file content in reverse order.
* Ex1: `tac todo.md`
* Ex2: `tac ~/Documents/todo.md`
* Ex3: `tac ~/Final Project/Deliverable 2.pdf`
  
* tail: prints the last few numbers of lines of a certain file, then terminates.
* Ex1: `tail ~/Documents/Book/dracula.txt`
* Ex2: `tail -5 ~/Documents/Book/dracula.txt`
* Ex3: `tail -10 ~/Documents/Book/dracula.txt`
  
* touch: modifies timestamps, creates new files, or changes the the modification and access time for any file.
* Ex1: `touch cats.txt`
* Ex2: `touch Project.docx`
* Ex3: `touch Grocery.lst`
  
* tr: deletes or substitutes characters from standard input and writes the result to standard output.
* Ex1: `cat file.txt | tr '.' ','`
* Ex2: `cat program.py | tr "[:space:]" '/t'`
* Ex3: `cat file.py | tr -s "[:space:]" ' '`
  
* tree: Displays directory path and files in each subdirectory.
* Ex1: `tree cars`
* Ex2: `tree Lab1`
* Ex3: `tree Homework`

### Question 2
Answer each question:

* How to work with multiple terminals open?
  You can use applications such as Tilix to open multiple terminals, or if you're using the default terminal press CTRL+Shift+T.

* How to work with manual pages?
  Open your Terminal and use the `man` command in order to open the manual.

* How to parse (search) for specific words in the manual page
  You can parse for specific words in the manual using the `grep` command.

* How to redirect output (> and |)
  You can redirect output using the greater than or pipe symbols.
  Ex: $ echo line 1 > users
      $ cat users
      line 1
        
* How to append the output of a command to a file
  1. open terminal
  2. Append text to end of file using `echo` command: `echo 'text' >> filename`
  3. Append command output to end of file: commandname >> filename
   
* How to use wildcards
    * For copying and moving multiple files at the same time:
        Ex: file1 file2 file3 can be moved all at once using the * wildcard by typing `mv file*` in order to move all files that start with that same first word.

* How to use brace expansion
  * For creating entire directory structures in a single command
* Ex: `mkdir -p subjects/{Math,Art,IT}/{Homework,Projects}`
  
