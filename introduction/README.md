# C Introduction

The C programming language is a compiled general prupose programming language.
To be able to program in C, we have to understand how computer memory works.

### Compiled language
C is a compiled language. It means that, in order to run a C program, the compiler must take our code, process it, and it will create an executable file that will run our program.

### Basics of the language
Like all programming languages, we can extend functionality of our code with libraries. All C programs take advantage of many different libraries.

If we want to print something on the screen, we would want to use *printf*. In order to use it, we have to include the source where it has been defined - in this case *stdio.h* header file.

At the top of our hello.c file, we will include *stdio.h* like this:

```c
  #include <stdio.h>
```

OK, this is great. But, where should we put our *printf("Hello, World");*?
Lets see how our entire program looks like, so we can break it down line by line:

```c
  #include <stdio.h>

  int main() {
    printf("Hello, world!");

    return 0;
  }
```

