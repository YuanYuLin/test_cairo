TARGET = test_cairo

CFLAGS += -I$(SDKSTAGE)/usr/include/libcairo
CFLAGS += -I$(SDKSTAGE)/usr/include/libpixman
CFLAGS += -I$(SDKSTAGE)/usr/include/
CFLAGS += -I./include/

LDFLAGS += -L$(CC_SYSROOT)/usr/lib/ 
LDFLAGS += -L$(CC_SYSROOT)/lib/ 
LDFLAGS += -L$(SDKSTAGE)/usr/lib/ 
LDFLAGS += -L$(SDKSTAGE)/lib/ 
LDFLAGS += -lc -lpthread -lrt -lz -lbz2 -lcairo -lpixman-1


SRC = 
SRC += test_main_cairo.c

include Makefile.include.app
