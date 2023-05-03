Download Link: https://assignmentchef.com/product/solved-cpsc3220-assignment-3-critical-functions-for-a-trivial-file-system
<br>
<strong>Implementing critical functions for a trivial file system.</strong>

Problem Statement

In this assignment you will implement the tfs_delete(), tfs_read(), and tfs_write() functions for a trivial file system. These functions delete a file in the trivial file system, read a buffer of bytes from an existing file in the trivial file system, and write a buffer of bytes to an existing file in the trivial file system, respectively.  Please remember to add read block and write block as the only way to access file blocks.

You will find more details about the file system in the header file tfs.h. The file tfs_1.c is the first part of the implementation of helper functions and public functions. The file tfs_2.c is a skeleton file in which you will provide the implementation of the three functions. The tfs_2.c file has header comments that specify the functions that you will provide. The file tfs_driver1.c is an example of a test driver for the tfs_1.c and tfs_2.c code. The link to the archive with these files is available on Canvas in the assignment description.

The only file you will need to submit to canvas (without compressing it) is “tfs_2.c”. Do not submit any other source files or headers. I will compile my tfs.h header, my tfs_1.c source file, and my test driver file with your tfs_2.c source file to create a program to test. Your code must run on the School of Computing servers (e.g., the ada or babbage machines).

<strong><em>NB:</em></strong> This seems like a simple assignment, but you will need to spend some time understanding the structure and implementation of the existing code. This is a big part of the assignment. After you understand what is going on and how different files interoperate, then you will be able to make additions to the code. Please make a plan and start right away. With the deadline close to the end of the semester, there will not be time for assignment extension.