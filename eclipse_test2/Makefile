# ============================================================================
# Name        : Makefile
# Author      : mee
# Version     :
# Copyright   : Your copyright notice
# Description : Makefile for Hello World in Fortran
# ============================================================================

.PHONY: all clean

# Change this line if you are using a different Fortran compiler
FORTRAN_COMPILER = gfortran

all: src/test2.f90
	$(FORTRAN_COMPILER) -O2 -g \
		-o bin/test2 \
		src/test2.f90

clean:
	rm -f bin/test2 *.mod
