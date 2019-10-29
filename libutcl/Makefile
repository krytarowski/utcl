#      $NetBSD$

.include <bsd.own.mk>

# enable memory debugging
# CPPFLAGS+= -DTCL_MEM_DEBUG

# disable I/O commands -- open, close, gets, puts, etc.
# CPPFLAGS+= -DTCL_GENERIC_ONLY

LIB=           utcl

SRCS+= tclGet.c
SRCS+= tclProc.c
SRCS+= tclVar.c
SRCS+= tclAssem.c
SRCS+= tclCmdAH.c
SRCS+= tclCmdIL.c
SRCS+= tclCmdMZ.c
SRCS+= tclHash.c
SRCS+= tclParse.c
SRCS+= panic.c
SRCS+= regexp.c
SRCS+= tclalloc.c
SRCS+= tclBasic.c
SRCS+= tclExpr.c
SRCS+= tclUtil.c
SRCS+= tclEnv.c
SRCS+= tclXdbg.c
SRCS+= tclunxaz.c
SRCS+= tclGlob.c
SRCS+= tcluxutl.c
SRCS+= tcluxstr.c
SRCS+= tclXgen.c

INCS=          utcl.h
INCSDIR=       /usr/include

.PATH: ${.CURDIR}/..

.include <bsd.lib.mk>
