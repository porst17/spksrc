PKG_NAME = tmfs
PKG_VERS = 5f12bcdb048bf5c652b91bb9866a9f59406b2fb1
PKG_EXT = tar.gz
PKG_DIST_NAME = $(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = https://github.com/abique/tmfs/archive/
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

DEPENDS = cross/fuse cross/boost

HOMEPAGE = https://github.com/abique/tmfs
COMMENT  = FUSE filesystem for reading macOS TimeMachine backups
LICENSE  = MIT

#CONFIGURE_TARGET=dummy_target

include ../../mk/spksrc.cross-cmake.mk

.dummy_target:
