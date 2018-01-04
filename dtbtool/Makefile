CFLAGS=-Os -g -Wall
CC=gcc
PROGNAME=dtbtool

all: dtbtool

%.o: %.c
	$(CC) $(CFLAGS) -c $<

dtbtool: dtbtool.o
	$(CC) -g -o dtbTool dtbtool.o


obj-$(CONFIG_BUILD_DTBIMAGE) += dtbtool.o
