x86 NASM Assembly Code Snips
==============================

Here is a collection of my code snips of x86 Assembly

### Notes
- These snips are for NASM on a 32bit Linux machine, though not all snips use Linux system calls
- I use this repo for reference
- All source code in this repo is under public domain, see LICENSE

### Assembling and Linking
`nasm -f elf -o test.o example.asm # assembles`

`gcc -m32 -o test test.o # links`

