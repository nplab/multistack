.PATH: .
KMOD=	multistack
SRCS=	multistack.c
TARGET!=	uname -m
IDENT!=		uname -i
CFLAGS+= -I../../
CFLAGS+= -I$(SYSDIR)/$(TARGET)/compile/$(IDENT)

.include <bsd.kmod.mk>
