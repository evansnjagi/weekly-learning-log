# C programming
> C is a compiled programming language. It is mainly used for its simplisity in memory management.
## 26-07-2026

### What I covered
How to declare a pointer, store it, read it, modify, and dereference its content. Pointers are variables that store the address of other variables. One major application of pointers is the swap algorithm.

File input/output is an application of pointers. While working with files, first open a file pointer. The pointer holds important information about the file to be opened such as position of the buffer, content, size, etc. After opening the file, verify that it's open. Read/write content in the file. Finally remember to close the file.

### Key insight
Not closing the file may lead to memory leaks or data loss. `fclose` flushed the buffer to disk. This guarantees that data is saved in the file.

### Struggle of the week
Understaning the simple structure to work with files: open -> check -> use -> close.

### What's pending
Milestone project which is about parsing a csv file just like pandas.

### Next weeks intentions
Finish the milestone project on time.