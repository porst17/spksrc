PKG_NAME = sparsebundlefs
PKG_VERS = 1e4f85f13e8aa3d6d1aa5007814cb252b09475c6
PKG_EXT = tar.gz
PKG_DIST_NAME = $(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = https://github.com/porst17/sparsebundlefs/archive/
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

DEPENDS = cross/fuse

HOMEPAGE = https://github.com/torarnv/sparsebundlefs
COMMENT  = FUSE filesystem for reading macOS sparse-bundle disk images
LICENSE  = BSD-2

CONFIGURE_TARGET=dummy_target

include ../../mk/spksrc.cross-cc.mk

.dummy_target:
