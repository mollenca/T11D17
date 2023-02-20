CC=gcc

CFLAGS=-Wall -Werror -Wextra -std=c11

door_struct :  dmanager_module.o
	$(CC) dmanager_module.o -o ./../build/Quest_1 -lm
	rm -f *.o

dmanager_module.o : dmanager_module.c
	$(CC) $(CFLAGS) -c dmanager_module.c -o dmanager_module.o

clean :
	rm -f ./../build/Quest_*