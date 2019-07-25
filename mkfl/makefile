hello:print.o main.o
	gcc main.o print.o -o hello

main.o:main.c print.h
	gcc -c main.c

print.o:print.h print.c
	gcc -c print.c

clean:
	rm -f *.o hello
