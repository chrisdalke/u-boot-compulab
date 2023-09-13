#
# board/silinux/ek874/Makefile
#
# Copyright (C) 2021 Renesas Electronics Corporation
#
# SPDX-License-Identifier: GPL-2.0+
#

ifeq ($(CONFIG_SPL_BUILD),y)
obj-y	:= ../../renesas/rcar-common/gen3-spl.o
else
obj-y	:= ek874.o ../../renesas/rcar-common/common.o
endif
