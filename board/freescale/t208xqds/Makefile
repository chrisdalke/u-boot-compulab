#
# Copyright 2013 Freescale Semiconductor, Inc.
#
# SPDX-License-Identifier:      GPL-2.0+
#

ifeq ($(CONFIG_SPL_BUILD),y)
obj-y += spl.o
else
obj-$(CONFIG_TARGET_T2080QDS) += t208xqds.o eth_t208xqds.o
endif

obj-y   += ddr.o
obj-y   += law.o
obj-y   += tlb.o
