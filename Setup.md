1. Load these modules: 
```diff
@@ Hint: modules in red are mostly the mean and the others are dependencies 
icc/2018.1.163-GCC-6.4.0-2.28,			ifort/2018.1.163-GCC-6.4.0-2.28,
iccifort/2018.1.163-GCC-6.4.0-2.28,			impi/2018.1.163-iccifort-2018.1.163-GCC-6.4.0-2.28,
iimpi/2018a, imkl/2018.1.163-iimpi-2018a,                                       intel/2018a, 
YAXT/0.6.0-intel-2018a,                                                         grib_api/1.27.0-intel-2018a, 
- CDO/1.9.4-intel-2018a,			#freetype/2.10.1-GCCcore-8.3.0, 
util-linux/2.34-GCCcore-8.3.0,			fontconfig/2.13.1-GCCcore-8.3.0,
xorg-macros/1.19.2-GCCcore-8.3.0,			X11/20190717-GCCcore-8.3.0,
nettle/3.5.1-GCCcore-8.3.0,			libdrm/2.4.99-GCCcore-8.3.0,
LLVM/9.0.0-GCCcore-8.3.0,			libunwind/1.3.1-GCCcore-8.3.0, 
Mesa/19.1.7-GCCcore-8.3.0,			libGLU/9.0.1-GCCcore-8.3.0,
pixman/0.38.4-GCCcore-8.3.0,			gettext/0.20.1-GCCcore-8.3.0, 
GLib/2.62.0-GCCcore-8.3.0,			cairo/1.16.0-GCCcore-8.3.0,
-Java/11.0.2,Tk/8.6.9-GCCcore-8.3.0,			#NLopt/2.6.1-GCCcore-8.3.0,
libsndfile/1.0.28-GCCcore-8.3.0,			ICU/64.2-GCCcore-8.3.0,
UDUNITS/2.2.26-GCCcore-8.3.0,			GSL/2.6-GCC-8.3.0,
Ghostscript/9.50-GCCcore-8.3.0,			LittleCMS/2.9-GCCcore-8.3.0, 
ImageMagick/7.0.9-5-GCCcore-8.3.0,			Clang/9.0.1-GCCcore-8.3.0,
M4/1.4.18-GCCcore-8.3.0,			libtool/2.4.6-GCCcore-8.3.0,
pocl/1.4-GCC-8.3.0,R/3.6.2-fosscuda-2019b,		fosscuda/2018b,
cftime/1.0.1-fosscuda-2018b-Python-3.6.6,		
-netcdf4-python/1.4.3-fosscuda-2018b-Python-3.6.6,
binutils/2.31.1-GCCcore-8.2.0,			GCC/8.2.0-2.31.1, 
numactl/2.0.12-GCCcore-8.2.0,			libxml2/2.9.8-GCCcore-8.2.0,
libpciaccess/0.14-GCCcore-8.2.0,			hwloc/1.11.11-GCCcore-8.2.0, 
OpenMPI/3.1.3-GCC-8.2.0-2.31.1,			gompi/2019a, FFTW/3.3.8-gompi-2019a, 
OpenBLAS/0.3.5-GCC-8.2.0-2.31.1,			ScaLAPACK/2.0.2-gompi-2019a-OpenBLAS-0.3.5,
foss/2019a,GCCcore/8.2.0, 
- zlib/1.2.11-GCCcore-8.2.0,			#ncurses/6.1-GCCcore-8.2.0, 
libreadline/8.0-GCCcore-8.2.0,			Tcl/8.6.9-GCCcore-8.2.0,
SQLite/3.27.2-GCCcore-8.2.0,			XZ/5.2.4-GCCcore-8.2.0, 
GMP/6.1.2-GCCcore-8.2.0,			libffi/3.2.1-GCCcore-8.2.0, 
- Python/3.7.2-GCCcore-8.2.0,			#Szip/2.1.1-GCCcore-8.2.0,
- HDF5/1.10.5-gompi-2019a,			#cURL/7.63.0-GCCcore-8.2.0, 
- netCDF/4.6.2-gompi-2019a,			#expat/2.2.6-GCCcore-8.2.0,
libpng/1.6.36-GCCcore-8.2.0,			JasPer/2.0.14-GCCcore-8.2.0,
LibTIFF/4.0.10-GCCcore-8.2.0,			bzip2/1.0.6-GCCcore-8.2.0,
PCRE/8.43-GCCcore-8.2.0,			-PROJ/6.0.0-GCCcore-8.2.0, 
NASM/2.14.02-GCCcore-8.2.0,			libjpeg-turbo/2.0.2-GCCcore-8.2.0,
libgeotiff/1.5.1-GCCcore-8.2.0,			SciPy-bundle/2019.03-foss-2019a,
- GDAL/3.0.0-foss-2019a-Python-3.7.2,			-GEOS/3.7.2-foss-2019a-Python-3.7.2

2.Install the following R packages : 
Open R in terminal then run those commands: 
install.packages("ncdf4",repos ="https://cran.uni-muenster.de/")

install.packages("reshape2",repos ="https://cran.uni-muenster.de/")

install.packages("magrittr",repos ="https://cran.uni-muenster.de/")

install.packages("stringr",repos ="https://cran.uni-muenster.de/")

3.

```

