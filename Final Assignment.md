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
  
* cat: reads each file parameter in sequence and writes it to standard output.
  
* cp: Use the cp command to create a copy of the contents of a file or directory.
  
* cut: Cut out sections of a specified file or piped data and print the result to standard output.
  
* grep: search for a string in groups of files.
  
* head: writes to standard output a specified number of lines or bytes of each of the files or of the standard input.
  
* ls: list the names and features of files and directories.
  
* man: display the user manual of any command that we can run on the terminal.
  
* mkdir: create or make new directories.
  
* mv: move files and directories from one directory to another, or to rename a file or directory.
  
* tac: display the file content in reverse order.
  
* tail: prints the last few numbers of lines of a certain file, then terminates.
  
* touch: modifies timestamps, creates new files, or changes the the modification and access time for any file.
  
* tr: deletes or substitutes characters from standard input and writes the result to standard output. 
  
* tree: Displays directory path and files in each subdirectory,

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
  
