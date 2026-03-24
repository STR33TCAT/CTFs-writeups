# Challenge: LOG HUNT

## Description
Analyze the server log to find parts of the flag.

## Approach
The log file likely contains pieces of the flag labeled as FLAGPART.

## Solution
$ cd Downloads
$ ls
$ cat Server.log
$ wc -l Server.log
$ grep FLAGPART Server.log | cut -d ":" -f4 | sort | uniq

## Explanation
- grep FLAGPART: filters lines containing FLAGPART
- cut -d ":" -f4: extracts the 4th field separated by ":"
- sort | uniq: removes duplicates and orders the parts

## Flag
$ picoCTF{us3_y0urlinux_sk1lls_cedfasfb}
