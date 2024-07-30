# OpenMBIR Software Index

This repository provides links to the OpenMBIR family of software packages. OpenMBIR is a family of open source reconstruction algorithms based on model-based iterative reconstruction that can be used to reconstruct tomographic data and other forms of sensor data.

**[MBIRJAX CT:](https://github.com/cabouman/mbirjax)**
This is a new package based on jax. It offers a) ease of use, b) high-performance on GPU plattforms, c) rapid and robust convergence, d) full support for both parallel and conebeam geometry, and e) the ability to easily add new geometries. Right now it can do 2k x 2k x 1k reconstructions on an 80 GB A100 GPU with about 200 GB CPU main memory in about 2.5 hours, which we believe is state-of-the-art both in speed and quality for iterative reconstruction. Currently, it provides basic-support for preprocessing of NSI data sets, and it is ideal for reconstructing data from synchrotrons, X-radia scanners, and TEM instruments. This package is probably the best choice for scientists and engineers who would like to use MBIR reconstruction. The documentation is available from [here](https://mbirjax.readthedocs.io).

**[SVMBIR Parallel CT:](https://github.com/cabouman/svmbir)**
This is a python package for parallel and fan beam CT reconstruction. The code is very fast and easy to use with good [documentation](https://svmbir.readthedocs.io/en/latest/index.html). This code is useful for reconstructing any parallel beam data including X-ray synchrotron and electron microscopy tilt sequences.

**[MBIR Cone Beam CT:](https://github.com/cabouman/mbircone)**
This is a python package for cone beam CT reconstruction. The code is fairly fast and easy to use. It also supports 4D and PnP reconstruction using CNN prior models. 

**[MBIR Multislice Helical CT:](https://github.com/cabouman/mbirhelical)**
This is a python package for multislice helical scan CT reconstruction. This is the geometry used by typical medical scanners. This is raw C code. It is reasonably well written, but since it is C code, it requires a lot of TLC to use. We are hoping to put a python front end on this code and accellerate it in the future.

**[Gaussian Mixture EM Clustering Algorithm:](https://github.com/cabouman/pygmcluster)**
This is a python package for estimating the order and parameters of a Gaussian mixture model from training data. It is a port of some earlier widely used [C code](https://engineering.purdue.edu/~bouman/software/cluster).

**[Cython Sandbox:](https://github.com/cabouman/sandbox)**
This is a simple example of how you can use Cython to build a python interface to a C-code package.

**[C-code:](https://github.com/cabouman/C-code)**
This is a simple C-code package for reading and writing TIFF images.

**[Legacy C-code:](http://engineering.purdue.edu/~bouman/OpenMBIR)**
This is a pointer to a web page containing some of the old C-code implementations that served as the basis for these newer open-source packages.
