#
# board/renesas/porter/Makefile
#
# Copyright (C) 2015 Renesas Electronics Corporation
# Copyright (C) 2015 Cogent Embedded, Inc.
#
# SPDX-License-Identifier: GPL-2.0
#

ifeq ($(CONFIG_SPL_BUILD),y)
obj-y	:= porter_spl.o
else
obj-y	:= porter.o qos.o
endif
