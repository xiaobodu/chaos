CXXFLAGS += -Wall -static -g -O2 -fPIC

noinst_PROGRAMS = chaos_timer

chaos_timer_SOURCES = chaos.cpp \
					   ../misc_impl.cpp

chaos_timer_LDADD = \
			  $(top_srcdir)/chaos/libchaos_je.a \
			  -lpthread

