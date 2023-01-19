0x10. C - Variadic functions

stdarg.h is a header in the C standard library of the C programming language that allows functions to accept an indefinite number of arguments.

Variadic functions are functions which may take a variable number of arguments and are declared with an ellipsis in place of the last parameter. An example of such a function is printf. A typical declaration is

int check(int a, double b, ...);

Variadic functions must have at least one named parameter, so, for instance,

char *wrong(...);

is not allowed in C. (In C++ and the upcoming C23,[2] such a declaration is permitted.) In C, a comma must precede the ellipsis if a named parameter is specified; in C++, it is optional. 


This directory contains my answers on the 0x10-variadic_functions project questions.
