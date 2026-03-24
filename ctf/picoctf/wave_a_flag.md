# Challenge: Wave a Flag

## Description
The challenge provides a downloadable file named `warm`.

## Approach
After downloading the file, its contents appeared unreadable when opened directly.

To identify the file type, the following command was used:

## Solution

$ strings warm
$ strings warm | grep pico
$ ls -l warm
$ chmod +x warm
$ ./warm -h

## Flag
$ picoCTF{b1scu1ts_4nd_gr4vy_ac5832c}____
