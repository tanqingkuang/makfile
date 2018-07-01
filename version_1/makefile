edit : main.o print_hi.o print_hello.o
	gcc -o edit main.o print_hi.o print_hello.o 

main.o : main.c ./print_hi/print_hi.h ./print_hello/print_hello.h
	gcc -c main.c

print_hi.o : ./print_hi/print_hi.c
	gcc -c ./print_hi/print_hi.c

print_hello.o : ./print_hello/print_hello.c
	gcc -c ./print_hello/print_hello.c

clean:
	rm *.o edit 2>/dev/null
