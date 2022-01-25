WRITING SECURE CODE

INTRODUCTION: 
The objective of this project provides some insight into the mechanics of a real buffer overflow attack. No original code is modified and the attack is performed by inputting values which causes the buffer overflow. 

OVERVIEW: 

SECTION 1:
The goal is to provide input to the echo-app command-line application that will result in the execution of the function 'start_sh' in a C code target.c. A successful exploit implies we got the shell while echo-app is running. When entered into the shell '$', we can execute shell commands to know the information and exit.

SECTION 2:
As a part of this section, the use of a fuzzer called American Fuzzy Lop to find security vulnerabilities. Fuzzing is a technique for finding vulnerabilities in a program by running the program on 'random data' until it crashes. The 'afl-fuzz' is used in this section, one of the most successful and widely-used fuzzers currently available. The fuzzing of a version of libarchive (https://www.libarchive.org/), a widely used archive and compression library. It provides a program called bsdtar that offers similar functionality to the more common GNU tar program. 
