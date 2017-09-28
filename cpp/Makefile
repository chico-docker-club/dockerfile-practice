CC=g++
CFLAG=-std=c++11 -pedantic -Wall
TARGET=hello-world

all: $(TARGET)

run: clean all
	./$(TARGET)

clean:
	rm -rf main.o $(TARGET)

$(TARGET): main.o
	$(CC) main.o -Wall -o $(TARGET)

main.o: main.cpp
	$(CC) $(CFLAGS) -c main.cpp -o main.o
