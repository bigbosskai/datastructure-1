#obj-m += hello.o
#obj-m += filtericmp.o
#obj-m += rootkit.o
#obj-m += rickroll.o
#obj-m += excited_virus.o
#obj-m += mmap/mymmap.o
#obj-m += thread/kthread.o
obj-m += ioctl/ioctl_basic.o
all:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules

clean:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean
