TARGETS=$(patsubst %.c,%,$(wildcard *.c))

LDLIBS += -lpthread

all: $(TARGETS)

conn: conn.c
	$(CC) $(CFLAGS) -o $@ $^

clean:
	rm -f $(TARGETS)
