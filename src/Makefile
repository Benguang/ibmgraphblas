# simple Makefile for IBMGraphBLAS, relies on cmake

default:
	( cd build ; cmake .. ; make )
#	( cd build ; cmake .. ; make ; cd ../Demo ; ./demo )

library:
	( cd build ; cmake .. ; make )

#install:
#	( cd build ; cmake .. ; make ; make install )

clean: distclean

purge: distclean

distclean:
#	rm -rf build/* Demo/*_demo.out Demo/complex_demo_out.m
	rm -rf build/*
#	( cd Test ; make distclean )
#	( cd Tcov ; make distclean )
#	( cd Doc  ; make distclean )