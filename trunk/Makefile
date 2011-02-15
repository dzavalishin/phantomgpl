PHANTOM_ULAND=../../userland/trunk

default::
	@echo make {clear,all,install}

install:: all
	cd build; make install; cd ..

all:: import
	cd phantom; make all; cd ..

clean::
	cd phantom; make clean; cd ..

import::
	echo It is supposed that phantomuserland dir is in $(PHANTOM_ULAND)
	-ln -s $(PHANTOM_ULAND)/include include
	-ln -s ../$(PHANTOM_ULAND)/phantom/lib phantom/lib

