# $FreeBSD$

PORTNAME=	libsandbox
PORTVERSION=	1.0b
CATEGORIES=	devel

MAINTAINER=	penzin.dev@gmail.com
COMMENT=	Collections of APIs for separating running applications

LICENSE=	APACHE20

USE_GITHUB=	yes
GH_ACCOUNT=	FreeWebOS
GH_PROJECT=	libsandbox
GH_TAGNAME=	1.0b
GH_COMMIT=	96f9a77

USES=		cmake:outsource
INSTALL_TARGET=	install

BUILD_DEPENDS+=	share/cmake/Modules/webOS/webOS.cmake:${PORTSDIR}/devel/cmake-modules-webos

.include <bsd.port.mk>
