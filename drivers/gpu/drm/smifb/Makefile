obj-m := smifb.o
smifb-objs :=smi_drv.o smi_fbdev.o smi_main.o smi_mode.o smi_plane.o smi_ttm.o smi_prime.o hw750.o hw768.o
smifb-objs += ddk750/ddk750_help.o  ddk750/ddk750_chip.o  ddk750/ddk750_clock.o  ddk750/ddk750_mode.o ddk750/ddk750_power.o ddk750/ddk750_helper.o ddk750/ddk750_display.o ddk750/ddk750_2d.o ddk750/ddk750_edid.o ddk750/ddk750_swi2c.o ddk750/ddk750_hwi2c.o ddk750/ddk750_cursor.o


smifb-objs += ddk768/ddk768_help.o  ddk768/ddk768_chip.o  ddk768/ddk768_clock.o  ddk768/ddk768_mode.o ddk768/ddk768_power.o ddk768/ddk768_helper.o ddk768/ddk768_display.o ddk768/ddk768_2d.o \
ddk768/ddk768_edid.o ddk768/ddk768_swi2c.o ddk768/ddk768_hwi2c.o ddk768/ddk768_cursor.o ddk768/ddk768_video.o ddk768/ddk768_hdmi.o  ddk768/ddk768_timer.o ddk768/ddk768_intr.o 


ccflags-y :=-O2 -Iinclude/drm -fno-tree-scev-cprop -D_D_SMI -D_D_SMI_D -D__cdecl
