#
# Makefile for the Synaptics TCM touchscreen driver.
#

# Each configuration option enables a list of files.
ifeq ($(CONFIG_SAMSUNG_PRODUCT_SHIP), y)
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_TCM_SPI) += synaptics_tcm_spi.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_TCM_I2C) += synaptics_tcm_i2c.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_TCM_CORE) += synaptics_tcm_core_module.o synaptics_tcm_sec_fn.o synaptics_tcm_sec_fn_test.o
synaptics_tcm_core_module-objs := synaptics_tcm_core.o synaptics_tcm_touch.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_TCM_ZEROFLASH) += synaptics_tcm_zeroflash.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_TCM_REFLASH) += synaptics_tcm_reflash.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_TCM_RECOVERY) += synaptics_tcm_recovery.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_TCM_DIAGNOSTICS) += synaptics_tcm_diagnostics.o
else
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_TCM_SPI) += synaptics_tcm_spi.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_TCM_I2C) += synaptics_tcm_i2c.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_TCM_CORE) += synaptics_tcm_core_module.o synaptics_tcm_sec_fn.o synaptics_tcm_sec_fn_test.o
synaptics_tcm_core_module-objs := synaptics_tcm_core.o synaptics_tcm_touch.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_TCM_ZEROFLASH) += synaptics_tcm_zeroflash.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_TCM_REFLASH) += synaptics_tcm_reflash.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_TCM_DEVICE) += synaptics_tcm_device.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_TCM_TESTING) += synaptics_tcm_testing.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_TCM_RECOVERY) += synaptics_tcm_recovery.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_TCM_DIAGNOSTICS) += synaptics_tcm_diagnostics.o
endif