# $NetBSD: Makefile,v 1.3 2021/01/30 10:15:15 wiz Exp $

DISTNAME=	stone-3.2.1
PKGNAME=	${PYPKGPREFIX}-${DISTNAME}
CATEGORIES=	net python
MASTER_SITES=	${MASTER_SITE_PYPI:=s/stone/}

MAINTAINER=	pkgsrc-users@NetBSD.org
HOMEPAGE=	https://github.com/dropbox/stone
COMMENT=	Interface description language (IDL) for APIs
LICENSE=	mit

DEPENDS+=	${PYPKGPREFIX}-ply>=3.4:../../devel/py-ply
DEPENDS+=	${PYPKGPREFIX}-six>=1.3.0:../../lang/py-six
BUILD_DEPENDS+=	${PYPKGPREFIX}-test-runner-[0-9]*:../../devel/py-test-runner

USE_LANGUAGES=	# none

.include "../../lang/python/egg.mk"
.include "../../mk/bsd.pkg.mk"
