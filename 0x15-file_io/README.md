0x15. C - File I/O

File descriptor is integer that uniquely identifies an open file of the process.

File Descriptor table: File descriptor table is the collection of integer array indices that are file descriptors in which elements are pointers to file table entries. One unique file descriptors table is provided in operating system for each process.

File Table Entry: File table entries is a structure In-memory surrogate for an open file, which is created when process request to opens file and these entries maintains file position.

Standard File Descriptors: When any process starts, then that process file descriptors table’s fd(file descriptor) 0, 1, 2 open automatically, (By default) each of these 3 fd references file table entry for a file named /dev/tty

