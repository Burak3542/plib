SUBDIRS = src

EXTRA_DIST = README COPYING.DATA plib_examples.dsp plib_examples.dsw install-sh missing autogen.sh

dist-hook:
	tar cf - doc \
             src/ssg/tux/data \
             src/ssg/water/data \
             src/ssg/sky/data \
             src/ssg/majik/data \
             src/ssg/shrubs/data \
             src/psl/data \
             src/fnt/data     \
             data     \
	   | ( cd $(distdir) ; tar xf - )

