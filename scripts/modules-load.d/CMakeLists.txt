#
# SPDX-License-Identifier: GPL-2.0-only
#
# Copyright (C) 2015-2020 Micron Technology, Inc.  All rights reserved.
#

if( NOT "${MPOOL_DISTRO}" STREQUAL "el6" )
    install( FILES ${CMAKE_CURRENT_SOURCE_DIR}/mpool.conf DESTINATION /etc/modules-load.d COMPONENT runtime )
endif()
