CC=gcc
CFLAGS= -std=c99 -pedantic -Wall -Werror

all: sort-ints_debug sort-ints


sort-ints: sort-ints.c
	$(CC) $(CFLAGS) -DNDEBUG -O2 sort-ints.c -o sort-ints -lm


sort-ints_debug: sort-ints.c
	$(CC) $(CFLAGS) -g sort-ints.c -o sort-ints_debug -lm


clean:
	rm -f sort-ints sort-ints_debug
	rm -f *.o

