all: hello

hello: hello.o
	ld -o hello hello.o

hello.o: hello.asm
	nasm -f elf64 -g hello.asm

clean:
	rm -f hello hello.o

