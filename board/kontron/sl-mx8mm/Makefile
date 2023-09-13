# SPDX-License-Identifier: GPL-2.0+
# (C) Copyright 2019 Kontron Electronics GmbH

obj-y := sl-mx8mm.o

ifeq ($(CONFIG_SPL_BUILD),y)
obj-y += spl.o
obj-$(CONFIG_IMX8M_LPDDR4) += lpddr4_timing.o
endif
