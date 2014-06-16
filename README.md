asm-hello-world
===============

See: http://asm.sourceforge.net/intro/hello.html

Build with (64bit):
    $ nasm -f elf64 hello-world.asm
    $ ld -s -o hello hello-world.o

Build with (32bit):
    $ nasm -f elf64 hello-world.asm
    $ ld -s -o hello hello-world.o

