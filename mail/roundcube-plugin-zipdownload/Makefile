# $NetBSD: Makefile,v 1.7 2020/12/28 08:58:10 taca Exp $

PLUGIN=		zipdownload

MAINTAINER=	taca@NetBSD.org
COMMENT=	Roundcube Webmail ZipDownload plugin
LICENSE=	gnu-gpl-v3

DEPENDS+=	${PHP_PKG_PREFIX}-zip>=5.4.0:../../archivers/php-zip

.include "../../mail/roundcube/plugins.mk"
.include "../../mk/bsd.pkg.mk"
