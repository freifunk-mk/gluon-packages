include $(TOPDIR)/rules.mk

PKG_NAME:=gluon-mesh-vpn-wireguard-vxlan
PKG_VERSION:=1
PKG_RELEASE:=1

PKG_MAINTAINER:=Rafael Grothmann <freifunk@lordsandwurm.de>
PKG_LICENSE:=GPL-2.0-or-later

include $(TOPDIR)/../package/gluon.mk

define Package/gluon-mesh-vpn-wireguard-vxlan
  TITLE:=Support for connecting meshes via wireguard
  DEPENDS:=+gluon-mesh-vpn-core +micrond +kmod-wireguard +wireguard-tools +ip-full
endef

$(eval $(call BuildPackageGluon,gluon-mesh-vpn-wireguard-vxlan))
