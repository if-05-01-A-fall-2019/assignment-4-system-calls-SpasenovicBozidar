*Bozidar Spasenovic*

# SYSTEMCALLS

## fork:
duplicate a process, the duplicated process is called child process

## stat:
Returns informations about a file
Arguments:
const char pathname
      ~path of the file you want the informations

struct stat statbuf
      ~The return buffer

## kill:
Send a signal to a process


## mmap:
creates a new mapping in the virtual address space of the

## chmod:
it changes the file mode of files according to MODE

## waitpid
By default, waitpid() waits only for terminated children

#Fail Conditions

## fork
Can't allocate because low on memory

## exec:

Fails when it doesn't have execute permissions or the file dont't exists

## read:
Fails when you don't have the permission to read a file

## unlink:
A component of the path prefix is not a directory

## mount:
Fails if a component is missing

## Trap
A trap is used to switch from the user mode to the kernel mode
This is used when a program in user-mode needs to execute a system call
