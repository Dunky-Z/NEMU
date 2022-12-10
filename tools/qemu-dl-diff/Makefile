NAME  = qemu
SRCS  = $(shell find src/ -name "*.c" | grep -v "isa")
SRCS += $(shell find src/isa/$(ISA) -name "*.c")

SHARE = 1
CFLAGS += -DNEMU_HOME_DEV=$(NEMU_HOME_DEV)

include $(NEMU_HOME_DEV)/scripts/isa.mk
include $(NEMU_HOME_DEV)/scripts/build.mk
