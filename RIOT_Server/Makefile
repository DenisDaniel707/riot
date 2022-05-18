APPLICATION = riot_server
BOARD ?= native
RIOTBASE ?= $(CURDIR)/../RIOT
CFLAGS += -DSCHEDSTATISTICS -DDEVELHELP
QUIET ?= 1

USEMODULE += xtimer
USEMODULE += timex

include $(RIOTBASE)/Makefile.include
