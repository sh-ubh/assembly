# assembly
Learning low-level programming 

## How to compile 
```shell
$ nasm -f elf32 -o hello_world.o hello_world.asm
$ ld -m elf_i386 -o hello_world hello_world.o
```

