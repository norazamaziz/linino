# $Id$
#
# Makefile for diag driver
#
# Copyright (C) 2005 Felix Fietkau <nbd@openwrt.org>
#
# This program is free software; you can redistribute it and/or
# modify it under the terms of the GNU General Public License
# as published by the Free Software Foundation; either version
# 2 of the License, or (at your option) any later version.
#

obj-m := wlcompat.o

ifeq ($(MAKING_MODULES),1)
export-objs := wlcompat.o

-include $(TOPDIR)/Rules.make
endif
