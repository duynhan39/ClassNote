#Duy Nhan Cao
problem2: problem2.o point.o
	clang++ -Wall -o problem2 problem2.o point.o

problem2.o: problem2.cpp point.h
	clang++ -std=c++11 -g -Wall -c problem2.cpp

point.o: point.cpp point.h
	clang++ -std=c++11 -g -Wall -c point.cpp

clean:
	rm -f *.o problem2 *~
