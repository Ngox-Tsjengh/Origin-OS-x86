CURRENT_DIR	:=	$(shell pwd)
BUILD_ROOT	:=	$(CURRENT_DIR)/../

IMAGE		:=	$(BUILD_ROOT)/hd32Mi.img

CC			:=	x86_64-elf-gcc
CFLAGS		:=	-m32 -z nognustack

.PHONY: kernel clean
kernel:
	$(CC) $(CFLAGS) -c $(OBJ).c -o $(OBJ).o

clean:
	rm -rf *.o *.bin 
