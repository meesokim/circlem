#
# Makefile
#

CIRCLEHOME = ../../..

OBJS	= vchiqdevice.o \
	  vchiq_arm.o vchiq_2835_arm.o vchiq_core.o vchiq_kern_lib.o vchiq_connected.o \
	  vchiq_shim.o vchiq_util.o

libvchiq$(RASPPI).a: $(OBJS)
	rm -f $@
	$(AR) cr $@ $(OBJS)

include $(CIRCLEHOME)/Rules.mk
