FORCEINC=#-include asm-generic/cache.h -include asm-generic/param.h
DEFS=-D__KERNEL__ -DCONFIG_M386 -DCONFIG_X86_32

# -DHZ=50
CFLAGS += -nostdinc -I../include -I../include/x86 $(DEFS) $(FORCEINC) -DKBUILD_MODNAME=\"cirrus\"

all: cirrusfb.o

