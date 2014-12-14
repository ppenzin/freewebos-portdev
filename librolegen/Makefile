# $FreeBSD$

PORTNAME=	librolegen
PORTVERSION=	1.0b
CATEGORIES=	devel

MAINTAINER=	penzin.dev@gmail.com
COMMENT=	librolegen dynamically generates webOS system bus role files

LICENSE=	APACHE20

USE_GITHUB=	yes
GH_ACCOUNT=	FreeWebOS
GH_PROJECT=	librolegen
GH_TAGNAME=	1.0b
GH_COMMIT=	2833a6e

USES=		cmake:outsource
INSTALL_TARGET=	install

BUILD_DEPENDS+=	${LOCALBASE}/share/cmake/Modules/webOS/webOS.cmake:${PORTSDIR}/devel/cmake-modules-webos

.include <bsd.port.mk>
