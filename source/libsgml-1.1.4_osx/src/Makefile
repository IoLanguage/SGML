# Generated automatically from Makefile.in by configure.
#
# source make file
#

CC=gcc
DEBUG=-O3
INCLUDE=-I../include -I.
LIBS=
CFLAGS=${DEBUG} ${INCLUDE} -Wall -O3 -fPIC
LFLAGS=${DEBUG} ${INCLUDE} -Wall -O3 -o
OBJS=DomComment.o DomDocument.o DomElement.o DomNode.o DomNodeList.o DomText.o SgmlExtensionHtml.o SgmlExtensionXml.o SgmlParser.o Variant.o
LIBNAME=../libsgml.a
LIBEXEC=ar rc ${LIBNAME} ${OBJS} ${LIBS} && ranlib ${LIBNAME}
LIBBIN=${CXX} ${DEBUG} -Wall -O3 -shared -fPIC -o ../libsgml.so ${OBJS}

all: ${OBJS}
	${LIBEXEC}
	${LIBBIN}

*.c.${O}:
	${CC} ${CFLAGS} $*.c

clean:
	rm -f *.o core ${LIBNAME} ../libsgml.so

distclean:
	rm -f *.o core ${LIBNAME} ../libsgml.so Makefile
