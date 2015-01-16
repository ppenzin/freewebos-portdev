# $FreeBSD$

PORTNAME=	pmloglib-headers
PORTVERSION=	1.0b
CATEGORIES=	devel

MAINTAINER=	penzin.dev@gmail.com
COMMENT=	Headers exposed by Free WebOS logging library

LICENSE=	APACHE20

USE_GITHUB=	yes
GH_ACCOUNT=	FreeWebOS
GH_PROJECT=	pmloglib
GH_TAGNAME=	1.0b
GH_COMMIT=	01eb692

USES=		cmake:outsource
CMAKE_ARGS=	-D SHIP_HEADERS_ONLY=ON
INSTALL_TARGET=	install

BUILD_DEPENDS+=	${LOCALBASE}/share/cmake/Modules/webOS/webOS.cmake:${PORTSDIR}/devel/cmake-modules-webos

.include <bsd.port.mk>
