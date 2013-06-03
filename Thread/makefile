# for all mini projects using GNU/Linux Thread
# gcc-4.6.1

CC=gcc
CFLAGS=-g -Wall
LFLAGS=-lpthread

SOURCES=thread-pid.c
OBJECTS=$(SOURCES:.c=.o)

# use pattern rules. 
%.o: %.c
	$(CC) $(CFLAGS) $< -o $@


# Project "thread-pid"
EXECUTABLE=thread-pid
$(EXECUTABLE) : $(OBJECTS)
	$(CC) $(LFLAGS) $(OBJECTS) -o $@


# Project "thread-creation1"
EXECUTABLE=thread-creation1

$(EXECUTABLE) : $(OBJECTS)
	$(CC) $(LFLAGS) $(OBJECTS) -o $(target)
