# $FreeBSD$

PORTNAME=	libpbnjson
PORTVERSION=	1.0b
CATEGORIES=	devel

MAINTAINER=	penzin.dev@gmail.com
COMMENT=	Palm's Better Native JSON library

LICENSE=	APACHE20

USE_GITHUB=	yes
GH_ACCOUNT=	FreeWebOS
GH_PROJECT=	libpbnjson
GH_TAGNAME=	XXX.x.x
GH_COMMIT=	XXX

USES=		cmake:outsource
INSTALL_TARGET=	install

BUILD_DEPENDS+=	${LOCALBASE}/share/cmake/Modules/webOS/webOS.cmake:${PORTSDIR}/devel/cmake-modules-webos
BUILD_DEPENDS+=	XXX:${PORTSDIR}/devel/yajl
BUILD_DEPENDS+=	XXX:${PORTSDIR}/devel/lemon
BUILD_DEPENDS+=	XXX:${PORTSDIR}/devel/boost-libs
BUILD_DEPENDS+=	XXX:${PORTSDIR}/net/uriparser
BUILD_DEPENDS+=	bash:${PORTSDIR}/shells/bash

.include <bsd.port.mk>
