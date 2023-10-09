# Shell I/O Redirection and Command Basics

This README provides a brief overview of Shell I/O redirection, common commands, and how to combine them for effective command-line operations.

## Commands

### head

The `head` command is used to display the beginning of a file. By default, it shows the first 10 lines of a file.

### tail

The `tail` command displays the end of a file. By default, it shows the last 10 lines of a file.

### find

`find` is a command for searching files and directories in a directory hierarchy.

### wc

The `wc` command is used to count lines, words, and characters in a file.

### sort

`sort` is used to sort lines of text files in alphabetical or numerical order.

### uniq

The `uniq` command removes duplicate lines from a sorted file, retaining only one instance of each line.

### grep

The `grep` command searches for patterns in text using regular expressions and prints matching lines.

### tr

`tr` is used for translating or deleting characters from a text stream.

## Redirection

### Redirect standard output to a file

To redirect the standard output of a command to a file, use the `>` operator:

```bash
command > output.txt
