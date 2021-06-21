functions
conditions
boolean expressions
loops

#include <stdio.h>

int main(void)
{
    printf("hello, world"); 
}

How to write good code
correctness: does it work as intended
design: qualitative/subjective. how well written your code it.
style: how the code is formatted, readability

IDE: integrated development environment

instructions
-new file
-save "hello.c", .c extension for writing in C

stdio.h
    standard io 

#include <stdio.h>

int main(void)
{
    printf("hello, world");
}

CLI
    command line interface

GUI
    Graphical User Interface

What is the language that computers speak?
    binary
    1 and 0 to represent everything

Every command is compiled to binary


Source Code
    input
    the stuff we type that gets converted to binary

Machine Code
    output
    binary

Compiler
    converts input to output, source code to machine code
    make command

make hello
    compiles
./hello
    run the code 

function
    action or verb that does something
    mini application
    can take inputs
    implementation of algorithm in code

arguments
    or parameters
    inputs to functions

printf
    print format code
    print to screen
    printf()
    put string in parenthesis with ""
    end line with semicolon

when a function takes arguments
    can have side effects

side effect
    of a function
    visual
    other than return 

return values/variables
    what is given back at end of function 

library
    code someone else has written
    in this course, we will use cs50 library

string
    text in some form 

get_string()
    from cs50 library
    prints the argument and takes response from user
    string answer = get_string("What's your name?");

= 
    assignment operator in c 

must declare data type when assigning variable
    string answer = get_string("What's your name?");

printf("hello, %s", answer)

------
#include <cs50.h>
#include <stdio.h>

int main(void)
{
    string answer = get_string("What's your name?");
    printf("hello, %s\n", answer); 
}

-----
make hello
./hello

\n
    escape character

stdio.h
    standard input output
    popular file used in c programs to get input/output from user

io means input/output

.h is a header file

help50
    put help50 in front of compile command
    help50 make hello
    will give better error messages

style50
    can give style tips
    style50 hello.c

comments should refer to the purpose of the code
    not just saying what it is doing

check50
    checks correctness of code
    check50 hello

stopped lecture at 52:22