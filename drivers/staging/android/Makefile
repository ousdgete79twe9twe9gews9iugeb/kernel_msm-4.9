ccflags-y += -I$(src)			# needed for trace events

obj-y					+= ion/

obj-$(CONFIG_ASHMEM)			+= ashmem.o
ifneq ($(CONFIG_ANDROID_SIMPLE_LMK),y)
obj-$(CONFIG_ANDROID_LOW_MEMORY_KILLER)	+= lowmemorykiller.o
endif
obj-$(CONFIG_ANDROID_VSOC)		+= vsoc.o
