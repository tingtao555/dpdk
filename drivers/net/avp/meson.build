# SPDX-License-Identifier: BSD-3-Clause
# Copyright(c) 2018 Intel Corporation

if not is_linux
	build = false
	reason = 'only supported on linux'
endif
sources = files('avp_ethdev.c')
install_headers('rte_avp_common.h', 'rte_avp_fifo.h')
