
# Copyright (C) 2016 Openwrt.org
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI Access Control Configuration
LUCI_DEPENDS:=
LUCI_PKGARCH:=all

PKG_NAME:=luci-app-accesscontrol
PKG_VERSION:=1
PKG_RELEASE:=11

# 安装目标
define Build/Install
    chmod a+x $(1)/etc/init.d/mia
endef

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature
