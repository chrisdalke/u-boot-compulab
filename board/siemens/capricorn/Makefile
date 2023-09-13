# SPDX-License-Identifier: GPL-2.0+
#
# Copyright 2019 Siemens AG
#

obj-y += board.o

ifeq ($(CONFIG_SPL_BUILD),y)
obj-y += spl.o
else
obj-y += ../common/factoryset.o
endif
