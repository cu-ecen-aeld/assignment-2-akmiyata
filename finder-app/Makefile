GCC=$(CROSS_COMPILE)gcc
CFLAGS= -g -Wall
FL=writer

all: ${FL}

${FL}: writer.c
	$(GCC) $(CFLAGS) -o $(FL) $(FL).c

clean:
	rm ${FL}
