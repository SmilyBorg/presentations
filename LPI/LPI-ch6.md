# Chapter 6 Text Processing/Advanced Command line
https://www.safaribooksonline.com/library/view/comptia-linux/9780134085777/ch06.html

---
# We will cover
* Pipes, Streams, and redirects
* Process text streams using filters
* Search text files using regular expressions

---
# Unix basics
* Commands should do one thing well
* It should accept standard Input
* It should produce standard Output
* Everything is a file

---
# Input/Output Streams
| Name           | Device      | File Descriptor | Associated File |
| -------------- | ----------- | --------------- | --------------- |
| Standard In    | /dev/stdin  | 0               | /proc/self/fd/0 |
| Standard Out   | /dev/stdout | 1               | /proc/self/fd/1 |
| Standard Error | /dev/stderr | 2               | /proc/self/fd/2 |

---
# Redirection
* < redirect a file to stdin
* > redirect stdout to a file
* >> redirect std out to a file, appending to the file
* 2> Redirects stderr to a file
* 2>&1 redirect stderr to stdout
* | pass stdout of one command the stdin of the next 
---
# commands
* cat and tac
* more
* less
* nl
* pr
* sort
* uniq
* wc

---
# multiple command operators
* ;
* &&
* ||

---
# Command Substitution
* `somecmd`
* $(somecmd)

---
# Spliting and processing Streams
* tee 
* xargs

---
* find 
* grep, egrep, fgrep 
* expand 
* convert
* cut
* paste
* join
* head and tail
* split
* od
* strings
* reset
* fmt 
* tr 
* sed 

---
* awk
* jq
