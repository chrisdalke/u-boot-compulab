#
# board/renesas/silk/Makefile
#
# Copyright (C) 2015 Renesas Electronics Corporation
# Copyright (C) 2015 Cogent Embedded, Inc.
#
# SPDX-License-Identifier: GPL-2.0
#

ifeq ($(CONFIG_SPL_BUILD),y)
obj-y	:= silk_spl.o
else
obj-y	:= silk.o qos.o
endif
