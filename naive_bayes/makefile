CC=g++
CFLAGS=-I.

naivebayes: ./src/main.cpp ./src/classifier.cpp ./src/classifier.h
	[ -d build ] || mkdir ./build
	$(CC) -o ./build/naivebayes ./src/main.cpp ./src/classifier.cpp

clean:
	rm -rf ./build

