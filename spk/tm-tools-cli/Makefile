SPK_NAME = tm-tools-cli
SPK_VERS = 1.0
SPK_REV = 1
SPK_ICON = src/synocli-disk.png

include ../../mk/spksrc.common.mk

DEPENDS  = cross/tmfs cross/sparsebundlefs

MAINTAINER = porst17
DISPLAY_NAME = FUSE tools for Apple Time Machine backups

OPTIONAL_DESC = 

DESCRIPTION = "Provide sparsebundlefs and tmfs tools for mounting Apple Time Machine backups$(OPTIONAL_DESC)"
STARTABLE = no
CHANGELOG = "Initial release."

HOMEPAGE = 
LICENSE  = Each tool is licensed under it\'s respective license.

SPK_COMMANDS  = bin/sparsebundlefs bin/tmfs

include ../../mk/spksrc.spk.mk
