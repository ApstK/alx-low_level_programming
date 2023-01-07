0x0A. C - argc, argv


    argc is the number of arguments on the command line (including the program name itself)

    argv is an array of C-style strings (character arrays, with a null character at the end of each string)

	argv[0] is the name of the program being executed
        argv[1] is the first parameter supplied on the command line
        argv[2] is the second parameter supplied on the command line, and so forth.

 The name of the variable argc stands for "argument count"; argc contains the number of arguments passed to the program. The name of the variable argv stands for "argument vector". A vector is a one-dimensional array, and argv is a one-dimensional array of strings. Each string is one of the arguments that was passed to the program.

For example, the command line

gcc -o myprog myprog.c

would result in the following values internal to GCC:


argc
    4
argv[0]
    gcc
argv[1]
    -o
argv[2]
    myprog
argv[3]
    myprog.c 

As you can see, the first argument (argv[0]) is the name by which the program was called, in this case gcc.
