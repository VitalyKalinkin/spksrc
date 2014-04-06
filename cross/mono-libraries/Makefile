PKG_NAME = mono-libraries
PKG_VERS = 3.4.0
PKG_EXT = tar.bz2
PKG_DIST_NAME = mono-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = http://download.mono-project.com/sources/mono
PKG_DIR = mono-$(PKG_VERS)

DEPENDS = 

HOMEPAGE = http://mono-project.com/
COMMENT  = The Mono .NET libraries set
LICENSE  =

GNU_CONFIGURE = 1
CONFIGURE_ARGS = --with-static_mono=yes --with-xen-opt=no --with-profile4=yes --with-moonlight=yes  

include ../../mk/spksrc.cross-cc.mk
