CC = gcc 
CFLAGS = -g -std=c99 -Wall 
LDFLAGS = -lm

help: 
	@echo "targets: help log header test clean"
timer: timer.o 
	$(CC) $(LDFLAGS) $^ -o $@
piper: piper.o
	$(CC) $(LFLAGS) $^ -o $@
timer.o: timer.c 
	$(CC) $(CFLAGS) -c  $<
piper.o: piper.c 
	$(CC) $(CFLAGS) -c  $<
test: 
	
clean: 
	rm timer
	rm piper
	rm *.o
all: 
	make compile
	make test