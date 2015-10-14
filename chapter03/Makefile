ROOT=..
CC=gcc
CFLAGS=-ansi -I$(ROOT)/include -Wall -DMACOS -D_DARWIN_C_SOURCE $(EXTRA)

PROGS =	seek

all:	$(PROGS)

%:	%.c
	$(CC) $(CFLAGS) $@.c -o $@

clean:
	rm -f $(PROGS)
