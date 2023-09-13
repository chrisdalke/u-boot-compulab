# SPDX-License-Identifier: GPL-2.0+

obj-y += pitx_imx8m.o pitx_misc.o

ifeq ($(CONFIG_SPL_BUILD),y)
obj-y += spl.o pitx_misc.o
obj-$(CONFIG_IMX8M_LPDDR4) += lpddr4_timing_2gb.o lpddr4_timing_4gb.o
endif
