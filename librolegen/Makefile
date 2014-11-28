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
GH_TAGNAME=	submissions/21
GH_COMMIT=	2833a6e

USES=		cmake:outsource
INSTALL_TARGET=	install

BUILD_DEPENDS+=	share/cmake/Modules/webOS/webOS.cmake:${PORTSDIR}/devel/cmake-modules-webos

.include <bsd.port.mk>
