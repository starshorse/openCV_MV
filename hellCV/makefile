CC = g++
CFLAGS = -g -Wall -std=c++11
SRCS = main.cpp
PROG = HelloCV

OPENCV=`pkg-config opencv4 --cflags --libs`
LIBS = $(OPENCV)

.PHONY:all clean

all:$(PROG)

$(PROG): $(SRCS)
	$(CC) $(CFLAGS) -o $(PROG) $(SRCS) $(LIBS) 

clean:
	rm -f $(OBJS) $(PROGS)
