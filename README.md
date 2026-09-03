
master: [![Build Status](https://travis-ci.org/svenpeter42/fastfilters.svg?branch=master)](https://travis-ci.org/svenpeter42/fastfilters) [![Build status](https://ci.appveyor.com/api/projects/status/obc03rs0cwisnsdv/branch/master?svg=true)](https://ci.appveyor.com/project/svenpeter42/fastfilters/branch/master)

devel: [![Build Status](https://travis-ci.org/svenpeter42/fastfilters.svg?branch=devel)](https://travis-ci.org/svenpeter42/fastfilters) [![Build status](https://ci.appveyor.com/api/projects/status/obc03rs0cwisnsdv/branch/master?svg=true)](https://ci.appveyor.com/project/svenpeter42/fastfilters/branch/devel)

Ideguchi-Lab Python 3.12 compatibility fork
------------

This fork pins pybind11 v2.12.1 (`2e0815278cb899b20870a67ca8205996ef47e70f`)
to support building the Python extension with Python 3.12. The original project
revision pinned a pre-Python-3.12 pybind11 revision.

Installation (stable)
------------

	% git clone https://github.com/svenpeter42/fastfilters.git
	% cd fastfilters
	% mkdir build
	% cmake ..
	% make
	% make install


Conda Installation (stable)
------------

	% conda install -c ilastik fastfilters


Gentoo Installation (development)
------------

	% git clone https://github.com/svenpeter42/fastfilters.git
	% cd fastfilters/pkg/gentoo/sci-libs/fastfilters
	% sudo ebuild fastfilters-9999.ebuild manifest clean merge
