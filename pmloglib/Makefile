# $FreeBSD$

PORTNAME=	pmloglib
PORTVERSION=	1.0b
CATEGORIES=	devel

MAINTAINER=	penzin.dev@gmail.com
COMMENT=	Thre Free WebOS logging library

LICENSE=	APACHE20

USE_GITHUB=	yes
GH_ACCOUNT=	FreeWebOS
GH_PROJECT=	pmloglib
GH_TAGNAME=	XXX.x.x
GH_COMMIT=	XXX

USES=		cmake:outsource
INSTALL_TARGET=	install

BUILD_DEPENDS+=	${LOCALBASE}/share/cmake/Modules/webOS/webOS.cmake:${PORTSDIR}/devel/cmake-modules-webos
BUILD_DEPENDS+=	XXX:${PORTSDIR}/devel/glib20
BUILD_DEPENDS+=	XXX:${PORTSDIR}/devel/libpbnjson

.include <bsd.port.mk>
