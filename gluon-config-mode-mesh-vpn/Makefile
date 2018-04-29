include $(TOPDIR)/rules.mk

PKG_NAME:=gluon-config-mode-mesh-vpn
PKG_VERSION:=2

include $(TOPDIR)/../package/gluon.mk

define Package/gluon-config-mode-mesh-vpn
  TITLE:=Toggle mesh-vpn and bandwidth limit
  DEPENDS:=+gluon-config-mode-core +gluon-mesh-vpn-core
endef

$(eval $(call BuildPackageGluon,gluon-config-mode-mesh-vpn))
