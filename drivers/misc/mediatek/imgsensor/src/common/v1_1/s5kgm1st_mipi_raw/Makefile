#include $(srctree)/drivers/misc/mediatek/Makefile.custom
#ifdef VENDOR_EDIT
#for enable KASAN, use GCC complile tool, add flag -Wno-misleading-indentation
ifeq ($(CONFIG_KASAN),y)
subdir-ccflags-y += -Wno-format
endif
#endif
subdir-ccflags-y += -I$(srctree)/drivers/misc/mediatek/mmdvfs

obj-y += s5kgm1stmipiraw_Sensor.o
