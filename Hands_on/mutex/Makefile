obj-m += mutex_ex.o
#ARCH=arm
#CROSS_COMPILE_PREFIX=arm-linux-gnueabi-
KSRC = /home/user/workspace/linuxO

all:
	make -C /home/user/workspace/linuxO M=${PWD} modules ARCH=arm CROSS_COMPILE=arm-linux-gnueabi-
clean:
	make -C /home/user/workspace/linuxO M=${PWD} clean ARCH=arm CROSS_COMPILE=arm-linux-gnueabi-


