all:	a.exe

a.exe:	a.o
	gcc -o $@ $^

%.o:	%.c
	gcc -c $^ 

clean:	
	rm a.o a.exe
