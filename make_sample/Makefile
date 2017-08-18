CC=gcc
CFLAGS=-I.
DEPS=main.h
OBJ=./obj/main.o ./obj/func.o

%.o: %.c $(DEPS)
	$(CC) -c -o $@ $< $(CFLAGS)

testapp: $(OBJ)
	$(CC) -o $@ $^ $(CFLAGS)