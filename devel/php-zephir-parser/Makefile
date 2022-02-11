PORTNAME=	php-zephir-parser
DISTVERSIONPREFIX=	v
DISTVERSION=	1.4.2
CATEGORIES=	devel
PKGNAMEPREFIX=	${PHP_PKGNAMEPREFIX}

MAINTAINER=	cmcdonald@netgate.com
COMMENT=	Zephir Parser delivered as a C extension for the PHP language

LICENSE=	MIT

BUILD_DEPENDS=  re2c>0:devel/re2c

USES=	gmake libtool
USES+=	php:ext php:phpize php:flavors

USE_GITHUB=	yes
GH_ACCOUNT=	zephir-lang

PHP_MODNAME=	zephir_parser

GNU_CONFIGURE=	yes

TEST_TARGET=	test

.include <bsd.port.mk>
