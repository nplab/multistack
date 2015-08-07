.PATH: .
KMOD=	multistack
SRCS=	multistack.c
TARGET!=	uname -m
IDENT!=		uname -i
CFLAGS+= -I../../
CFLAGS+= -I$(SYSDIR)/$(TARGET)/compile/$(IDENT)
CFLAGS+= -I$(SYSDIR)/$(IDENT)
.include <bsd.kmod.mk>
