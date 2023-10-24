 - More functions, more nested loops
C
 By: Julien Barbier
 Weight: 1
 Project over - took place from Oct 12, 2023 4:00 AM to Oct 13, 2023 4:00 AM
 An auto review will be launched at the deadline
In a nutshell…
Auto QA review: 0.0/70 mandatory & 0.0/19 optional
Altogether:  0.0%
Mandatory: 0.0%
Optional: 0.0%
Calculation:  0.0% + (0.0% * 0.0%)  == 0.0%
Concepts
For this project, we expect you to look at this concept:

Struggling with the sandbox? Try this: Using Docker & WSL on your local host
Resources
Read or watch:

Nested while loops
C - Functions
Learning to Program in C (Part 06) (stop at 14:00)
What is the purpose of a function prototype?
C - Header Files (stop before the “Once-Only Headers” paragraph)
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
What are nested loops and how to use them
What is a function and how do you use functions
What is the difference between a declaration and a definition of a function
What is a prototype
Scope of variables
What are the gcc flags -Wall -Werror -pedantic -Wextra -std=gnu89
What are header files and how to to use them with #include
Copyright - Plagiarism
You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
You are not allowed to publish any content of this project.
Any form of plagiarism is strictly forbidden and will result in removal from the program.
Requirements
General
Allowed editors: vi, vim, emacs
All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
All your files should end with a new line
A README.md file, at the root of the folder of the project is mandatory
Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
You are not allowed to use global variables
No more than 5 functions per file
You are not allowed to use the standard library. Any use of functions like printf, puts, etc… is forbidden
You are allowed to use _putchar
You don’t have to push _putchar.c, we will use our file. If you do it won’t be taken into account
In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
The prototypes of all your functions and the prototype of the function _putchar should be included in your header file called main.h
Don’t forget to push your header file
More Info
You do not have to understand the call by reference (address), stack, static variables, recursions or arrays, yet.

Quiz questions
Great! You've completed the quiz successfully! Keep going! (Hide quiz)
Question #0
What is the output of the following piece of code?

int i;

for (i = 48; i < 58; i++)
{
    printf("%c", i);
}

0123456789


School


48495051525354555657

Question #1
What is the return value of the following function?

int some_function(void)
{
    printf("%d", 12);
    return (98);
}

98


402


12

Question #2
What is the output of the following piece of code?

int i;

i = 0;
while (i < 10)
{
    i++;
    printf("%d", i / 2);
}

0123456789


0112233445


0011223344

Question #3
What is the output of the following piece of code?

int i;

i = -9;
while (i < 0)
{
    printf("%d", -i);
    i++;
}

987654321


-9-8-7-6-5-4-3-2-10


-9-8-7-6-5-4-3-2-1


9876543210

Question #4
What is the output of the following piece of code?

int i;

i = 9;
while (--i)
{
    printf("%d", i);
}

9876543210


876543210


987654321


87654321

Question #5
What is the output of the following piece of code?

int i;

i = 9;
while (i--)
{
    printf("%d", i);
}

876543210


9876543210


987654321


87654321

Question #6
What is the output of the following piece of code?

int i;

for (i = 0; i < 10; i++)
{
    printf("%d", i * 2);
}

2468101214161820


024681012141618


0123456789

Question #7
What is the return value of the following function?

int some_function(void)
{
    int i;

    for (i = 0; i < 10; i++)
    {
        printf("%d", i);
    }
    return(i);
}

9


10


0123456789


0

Question #8
What is the output of the following piece of code?

int i;

i = 0;
while (i < 10)
{
    printf("%d", i % 2);
    i++;
}

0123456789


1010101010


0101010101
