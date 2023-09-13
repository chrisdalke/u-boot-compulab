#
# Makefile
#
# (C) Copyright 2017 CompuLab, Ltd. http://www.compulab.com
#
# Author: Uri Mashiach <uri.mashiach@compulab.co.il>
#
# SPDX-License-Identifier:     GPL-2.0+
#

obj-y := mux.o common.o

ifeq ($(CONFIG_SPL_BUILD),y)
obj-y  += spl.o
else
obj-y  += cl-som-imx7.o
endif
