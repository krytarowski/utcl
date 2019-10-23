#	$NetBSD$

NOMAN=	# defined

.include <bsd.own.mk>

PROG=	utcl

here :=	${.PARSEDIR}

.PATH: ${here}/..

.PATH: ${here}/../libutcl

SRCS+=	tinytcl.c

LDADD+=	-lutcl -L${here}/../libutcl
DPADD+=	libutcl.a

.include <bsd.prog.mk>
