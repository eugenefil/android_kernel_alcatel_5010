subdir-ccflags-y +=  -I$(srctree)/drivers/input/keyboard/mediatek/
ifeq ($(CONFIG_MT_SND_SOC_6580),y)
	EXTRA_CFLAGS += -I$(srctree)/sound/soc/mediatek/mt_soc_audio_6580
endif

obj-$(CONFIG_KEYBOARD_MTK) := hal_kpd.o
