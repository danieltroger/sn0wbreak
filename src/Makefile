CC=gcc
CFLAGS= -g -Wall -L/os/lib
LIBS = -limobiledevice -lplist -lusbmuxd
TARGET=info
SOURCES=info.c \
        device.c \
        lockdown.c \
        file_get_contents.c

all: $(TARGET)

$(TARGET): $(TARGET).c
	$(CC) $(CFLAGS) -o $(TARGET) $(SOURCES) $(LIBS)

clean:
	rm $(TARGET)
