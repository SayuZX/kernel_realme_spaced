ifneq ($(strip $(CONFIG_MTK_TINYSYS_SSPM_SUPPORT)$(CONFIG_MTK_TINYSYS_SSPM_PLT_SUPPORT)),)
ifeq ($(CONFIG_MACH_MT6781),y)
obj-y += mt6781/
else
obj-y += $(subst ",,$(CONFIG_MTK_PLATFORM))/
endif
else
obj-y +=  dummy.o
endif
