CC=g++
CFLAGS=-I.

naivebayes: ./src/main.cpp ./src/vehicle.cpp ./src/cost.cpp ./src/road.cpp
	[ -d build ] || mkdir ./build
	$(CC) -o ./build/behavior ./src/main.cpp ./src/vehicle.cpp ./src/cost.cpp ./src/road.cpp

clean:
	rm -rf ./build

