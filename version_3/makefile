object = main.o ./print_hi/print_hi.o ./print_hello/print_hello.o 

edit : $(object) 
	gcc -o edit $(object) 

main.o : ./print_hi/print_hi.h ./print_hello/print_hello.h

clean:
	rm $(object) edit 2>/dev/null
