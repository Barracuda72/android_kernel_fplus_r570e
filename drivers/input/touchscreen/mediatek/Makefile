subdir-ccflags-y += -Werror
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/$(MTK_PLATFORM)/include
# In case the platform does NOT support this type of sensors
obj-y   +=  mtk_tpd.o
obj-y   +=  tpd_button.o
obj-y   +=  tpd_calibrate.o
obj-y   +=  tpd_debug.o
obj-y   +=  tpd_default.o
obj-y   +=  tpd_misc.o
obj-y   +=  tpd_setting.o

obj-$(CONFIG_TOUCHSCREEN_MTK_SOLOMON) += SOLOMON/
obj-$(CONFIG_TOUCHSCREEN_MTK_FOCALTECH_TS) += focaltech_touch/
obj-$(CONFIG_TOUCHSCREEN_GT9XX) += goodix917d/
obj-$(CONFIG_TOUCHSCREEN_MTK_GT1X_V14) +=  GT1X_V14/
