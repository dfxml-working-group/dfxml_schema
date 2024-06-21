#!/usr/bin/make -f

# Portions of this file contributed by NIST are governed by the
# following statement:
#
# This software was developed at the National Institute of Standards
# and Technology by employees of the Federal Government in the course
# of their official duties. Pursuant to Title 17 Section 105 of the
# United States Code, this software is not subject to copyright
# protection within the United States. NIST assumes no responsibility
# whatsoever for its use by other parties, and makes no guarantees,
# expressed or implied, about its quality, reliability, or any other
# characteristic.
#
# We would appreciate acknowledgement if the software is used.

top_srcdir := ..

all:

.%.dfxml.done.log: \
  %.dfxml \
  $(dfxml_xsd)
	xmllint \
	  --noout \
	  --schema $(top_srcdir)/dfxml.xsd \
	  $<
	touch $@

check: \
  .minimal.dfxml.done.log

clean:
	@rm \
	  -f \
	  .*.dfxml.done.log
