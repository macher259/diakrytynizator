# diakrytynizator
Simple project using x64 Assembly
### To compile:
```
nasm -f elf64 -w+all -w+error -o diakrytynizator.o diakrytynizator.asm
ld --fatal-warnings -o diakrytynizator diakrytynizator.o
```

