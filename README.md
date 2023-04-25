0x1B. C - Sorting algorithms & Big O
====================================

CAlgorithmData structure

-   By: Alexandre Gautier

![](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/248/willy-wonka.png)

Background Context
------------------

This project is meant to be done by groups of two students. Each group of two should [pair program](https://intranet.alxswe.com/rltoken/gIcHRL9I7i1lw2CTAll37A "pair program") for at least the mandatory part.

Resources
---------

**Read or watch**:

-   [Sorting algorithm](https://intranet.alxswe.com/rltoken/-j5MKLBlzZAC2RfJ5DTBIg "Sorting algorithm")
-   [Big O notation](https://intranet.alxswe.com/rltoken/WRvrE2BaNVQFssHiUATTrw "Big O notation")
-   [Sorting algorithms animations](https://intranet.alxswe.com/rltoken/ol0P7NbYVb5R31iOv4Q40A "Sorting algorithms animations")
-   [15 sorting algorithms in 6 minutes](https://intranet.alxswe.com/rltoken/_I0aEvhfJ66Xyob6dd9Utw "15 sorting algorithms in 6 minutes") (***WARNING**: The following video can trigger seizure/epilepsy. It is not required for the project, as it is only a funny visualization of different sorting algorithms*)
-   [CS50 Algorithms explanation in detail by David Malan](https://intranet.alxswe.com/rltoken/Ea93HeEYuNkOL7sGb6zzGg "CS50 Algorithms explanation in detail by David Malan")
-   [All about sorting algorithms](https://intranet.alxswe.com/rltoken/21X_eaj5RGcLIL9mZv2sqw "All about sorting algorithms")

Learning Objectives
-------------------

At the end of this project, you are expected to be able to [explain to anyone](https://intranet.alxswe.com/rltoken/b-QhraVUoSGmQ1C4QfNoFw "explain to anyone"), **without the help of Google**:

### General

-   At least four different sorting algorithms
-   What is the Big O notation, and how to evaluate the time complexity of an algorithm
-   How to select the best sorting algorithm for a given input
-   What is a stable sorting algorithm

### Copyright - Plagiarism

-   You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
-   You will not be able to meet the objectives of this or any following project by copying and pasting someone else's work.
-   You are not allowed to publish any content of this project.
-   Any form of plagiarism is strictly forbidden and will result in removal from the program.

Requirements
------------

### General

-   Allowed editors: `vi`, `vim`, `emacs`
-   All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
-   All your files should end with a new line
-   A `README.md` file, at the root of the folder of the project, is mandatory
-   Your code should use the `Betty` style. It will be checked using [betty-style.pl](https://github.com/holbertonschool/Betty/blob/master/betty-style.pl "betty-style.pl") and [betty-doc.pl](https://github.com/holbertonschool/Betty/blob/master/betty-doc.pl "betty-doc.pl")
-   You are not allowed to use global variables
-   No more than 5 functions per file
-   Unless specified otherwise, you are not allowed to use the standard library. Any use of functions like *printf, puts, ...* is totally forbidden.
-   In the following examples, the `main.c` files are shown as examples. You can use them to test your functions, but you don't have to push them to your repo (if you do we won't take them into account). We will use our own `main.c` files at compilation. Our `main.c` files might be different from the one shown in the examples
-   The prototypes of all your functions should be included in your header file called `sort.h`
-   Don't forget to push your header file
-   All your header files should be include guarded
-   A list/array does not need to be sorted if its size is less than 2.
