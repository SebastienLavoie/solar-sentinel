
GCC ?= arm-linux-gnueabi-gcc

all:
	$(GCC) -DHAVE_CONFIG_H -I. -I.. -g -O2 -MT bcm2835.o -MD -MP -MF deps/bcm2835.Tpo -c -o bcm2835.o bcm2835.c

clean:
	rm bcm2835.o