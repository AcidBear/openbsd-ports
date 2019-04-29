# $OpenBSD: Makefile,v 1.2 2018/09/12 16:22:35 danj Exp $

COMMENT =	Retrieve and parse whois data for IPv4 and IPv6 addresses 	

MODPY_EGG_VERSION =	1.1.0
DISTNAME =					ipwhois-${MODPY_EGG_VERSION}
PKGNAME =						py-${DISTNAME}
CATEGORIES =				net


# MIT
PERMIT_PACKAGE_CDROM=	Yes

MODULES=		lang/python

MODPY_PI =		Yes
MODPY_SETUPTOOLS =	Yes


FLAVORS =		python3
FLAVOR ?=

.include <bsd.port.mk>
