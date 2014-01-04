
lib_LTLIBRARIES = libtsdecrypt.la
libtsdecrypt_la_SOURCES = csa.c \
			  camd.c \
			  camd-newcamd.c \
			  camd-cs378x.c \
			  data.c \
			  filter.c \
			  globals.c \
			  notify.c \
			  util.c \
			  udp.c \
			  tables.c \
			  process.c \
			  libfuncs/cbuf.c \
			  libfuncs/io.c \
			  libfuncs/queue.c \
			  libfuncs/misc.c \
			  libfuncs/log.c \
			  libfuncs/list.c \
			  libfuncs/server.c \
			  libfuncs/asyncdns.c \
			  libtsfuncs/tsmisc.c \
			  libtsfuncs/crc.c \
			  libtsfuncs/descs.c \
			  libtsfuncs/tsfuncs.c \
			  libtsfuncs/tslog.c \
			  libtsfuncs/pat.c \
			  libtsfuncs/sdt.c \
			  libtsfuncs/pmt.c \
			  libtsfuncs/cat.c \
			  libtsfuncs/secdata.c \
			  libtsfuncs/time.c \
			  libtsfuncs/privsec.c \
			  libtsfuncs/pat_desc.c \
			  libtsfuncs/sections.c


libtsdecrypt_la_LDFLAGS = -lcrypt -lcrypto -ldvbcsa
libtsdecrypt_la_CFLAGS = -DDLIB=\"?\" -DUSE_LIBDVBCSA

bin_PROGRAMS = tsdecrypt
tsdecrypt_SOURCES = tsdecrypt.c
tsdecrypt_CFLAGS = -DVERSION=\"0.1\" -DGIT_VER=\"hmm\" -DBUILD_ID=\"automake\" -DDLIB=\"?\"
tsdecrypt_LDFLAGS = ./libtsdecrypt.la
