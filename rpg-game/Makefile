all: compile link

compile: 
	g++ -c main.cpp -Isrc/include

link:
	g++ main.o -o main -Lsrc/lib -lsfml-graphics -lsfml-window -lsfml-system