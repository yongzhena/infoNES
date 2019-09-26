KERN_DIR = /mnt/hgfs/b503/imax283/linux-2.6.35.3

all:
	make -C $(KERN_DIR) M=`pwd` modules 

clean:
	make -C $(KERN_DIR) M=`pwd` modules clean
	rm -rf modules.order

obj-m	+= joypad.o
