all: 
	g++ helloWorld.cpp -o hello.o
	g++ test/*.cpp -o runTests.o /usr/lib/libgtest.a /usr/lib/libgtest_main.a -lpthread
	./runTests.o

