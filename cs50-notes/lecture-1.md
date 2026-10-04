# CS50x: Lecture 1 - C

> **This is cs50!**

---

## Source Code

so here is the code

```c
#include <stdio.h>
int main (void)
{
    printf("hello world\n");
}
```

we will understand this code in some time

## Source Code vs Machine Code

The code above is called as **source code**
and as we know computers only understand 0 and 1
so basically **source code** is what human understands and **0 or 1** is called as **machine code** which machine understands

source code is converted into machine code with the help of tool which is known as **'compiler'**

so to make a 'c' file we save it as `.c`

- graphical user interface - **GUI**
- command line interface - **CLI**

## Writing and Running Our First Program

we will make a file by typing in terminal

```bash
code hello.c
```

write code inside `hello.c` and congratulations we wrote our first program

and now we will compile this program by typing in terminal `make hello`

and now we will access it by `./hello`

which means that i am saying the computer to look into the same folder which i am in for `hello`
and it will run that program and you will get the desired output and in our case it is `hello world`

so these are the commands we wrote in terminal

```bash
code hello.c
make hello
./hello
```

> in programming you have to finish a sentence with a semicolon just like in English we use period/dot.

---

## Understanding the Code

so now lets understand the code we wrote

### Escape Sequences

- `'\n'` we used in our code adds new line
- and there are also more escape sequences like -> `\n`, `\r`, `\"`, `\'`, `\\`
