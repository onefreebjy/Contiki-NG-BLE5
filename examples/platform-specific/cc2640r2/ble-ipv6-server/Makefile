CONTIKI_PROJECT = server

all: $(CONTIKI_PROJECT)

#PLATFORMS_ONLY = srf06-cc26xx
#BOARDS_ONLY = launchpad/cc2650 sensortag/cc2650 srf06/cc26xx launchpad/cc2640r2

MODULES += os/services/shell
MAKE_MAC = MAKE_MAC_BLE
MAKE_NET = MAKE_NET_IPV6
CONTIKI = ../../../..
include $(CONTIKI)/Makefile.include
