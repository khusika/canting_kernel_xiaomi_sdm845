obj-$(CONFIG_BCM_GPS_SPI_DRIVER) += bcm_gps_spi.o bbd.o bbd_rpc_lh.o

# Ignore this warn
ifeq ($(cc-name),clang)
EXTRA_CFLAGS += $(call cc-disable-warning,typedef-redefinition,)
endif
