build: utils.o hello.o help.o
	gcc utils.o help.o hello.o -o hello

all:
	gcc simple_hello.c -o simple

utils.o: utils.c
	gcc -c utils.c

hello.o: hello.c
	gcc -c hello.c

help.o: help.c
	gcc -c help.c

clean:
	rm -f *.o *~ hello
