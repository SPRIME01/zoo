extract:
	${tooldir}/rng2bgf OpenDocument-manifest-schema-v1.1.rng ext.bgf
	${tooldir}/normbgf ext.bgf grammar.bgf

get:
	rm -f *.rng
	wget http://docs.oasis-open.org/office/v1.1/OS/OpenDocument-manifest-schema-v1.1.rng

include ../../Makefile.grammar
