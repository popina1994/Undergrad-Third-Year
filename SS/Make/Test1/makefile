f : file1.o file3.o file2.o 
	gcc -o prog1 file1.o file2.o file3.o
	echo $^

file1.o file2.o file3.o:  mydef.h
	#gcc -c file1.c

#file2.o : mydef.h
	#gcc -c file2.c

#file3.o :mydef.h
#	gcc -c file3.c

clean:
	rm file1.o file2.o file3.o