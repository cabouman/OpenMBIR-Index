# OpenMBIR-Index

This repository provides links to the OpenMBIR family of software packages. OpenMBIR is a family of open source reconstruction algorithms based on model-based iterative reconstruction that can be used to reconstruct tomographic data with various geometries.

* Python wrapper for fast Super-Voxel parallel-beam MBIR https://github.com/cabouman/svmbir  
For most people, this is the package to use.
It is fast, parallel beam CT code with a python interface, and it has extensive instructions.
Please email use if you have any problems installing or using it.

* This is the underlying C version of Super-Voxel (i.e., fast parallelized) Parallel Beam MBIR: https://github.com/HPImaging/sv-mbirct  
Super-voxel code that adds PnP functionality: https://github.com/vsridha/sv-mbirct
This code is not recommended for most users. It is only for experts.

* For Parallel Beam MBIR (reference but slow): https://github.com/cabouman/OpenMBIR-ParBeam
* This code is very slow. It is only provided as a reference for testing and comparison.

* For Cone Beam MBIR: https://github.com/cabouman/OpenMBIR-ConeBeam  
For 4D Cone Beam MBIR: https://github.com/cabouman/OpenMBIR-ConeBeam-4D

* MBIR for electron microscopy (EM) applications: https://github.com/OpenMBIR/OpenMBIR-TEM  
More information for bright field: https://engineering.purdue.edu/~bouman/OpenMBIR/bf-em/index.html  
More information for dark field: https://engineering.purdue.edu/~bouman/OpenMBIR/haadf-em/index.html

* MBIR for TIMBIR 4D space-time reconstruction: https://github.com/adityamnk/timbir  
More information for TIMBIR: https://engineering.purdue.edu/~bouman/OpenMBIR/timbir/index.html

* Projects under development:  
Super-voxel code with MACE support: https://github.com/vsridha/sv-mbirct/tree/dev-CE
