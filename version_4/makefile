object = main.o ./print_hi/print_hi.o ./print_hello/print_hello.o 

H_FILES = ./print_hi/print_hi.h ./print_hello/print_hello.h

edit : $(object) 
	gcc -o edit $(object) 

$(object) : $(H_FILES)

clean:
	rm $(object) edit 2>/dev/null
