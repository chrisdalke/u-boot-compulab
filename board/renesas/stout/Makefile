#
# board/renesas/stout/Makefile
#
# Copyright (C) 2015 Renesas Electronics Europe GmbH
# Copyright (C) 2015 Renesas Electronics Corporation
# Copyright (C) 2015 Cogent Embedded, Inc.
#
# SPDX-License-Identifier: GPL-2.0
#

ifeq ($(CONFIG_SPL_BUILD),y)
obj-y	:= stout_spl.o
else
obj-y	:= stout.o cpld.o qos.o
endif
