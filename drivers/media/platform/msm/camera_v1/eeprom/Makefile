GCC_VERSION      := $(shell $(CONFIG_SHELL) $(PWD)/scripts/gcc-version.sh $(CROSS_COMPILE)gcc)
EXTRA_CFLAGS += -Idrivers/platform/msm/camera_v1/io
EXTRA_CFLAGS += -Idrivers/platform/msm/camera_v1
obj-$(CONFIG_MSM_EEPROM) += msm_camera_eeprom.o
obj-$(CONFIG_IMX074_EEPROM) += imx074_eeprom.o
obj-$(CONFIG_IMX091_EEPROM) += imx091_eeprom.o
obj-$(CONFIG_IMX175_EEPROM) += imx175_eeprom.o
