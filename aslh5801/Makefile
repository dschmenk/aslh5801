TARGET=aslh5801
CFLAGS=-I ../shared
OBJS=../shared/asdata.o ../shared/asdbg.o ../shared/asexpr.o \
../shared/aslex.o ../shared/aslist.o ../shared/asmain.o \
../shared/asmcro.o ../shared/asout.o ../shared/assubr.o \
../shared/assym.o lh5801adr.o lh5801mch.o lh5801pst.o

.PHONY: all clean

all: $(TARGET)

$(TARGET): $(OBJS)
	$(CC) $(CFLAGS) -o $@ $(OBJS)

clean:
	rm -f $(TARGET) $(OBJS)

