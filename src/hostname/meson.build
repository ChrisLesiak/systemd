# SPDX-License-Identifier: LGPL-2.1+
#
# Copyright 2017 Zbigniew Jędrzejewski-Szmek

if conf.get('ENABLE_HOSTNAMED') == 1
        install_data('org.freedesktop.hostname1.conf',
                     install_dir : dbuspolicydir)
        install_data('org.freedesktop.hostname1.service',
                     install_dir : dbussystemservicedir)
        install_data('org.freedesktop.hostname1.policy',
                     install_dir : polkitpolicydir)
endif
