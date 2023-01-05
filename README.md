# GDAL wheels for Python on Windows 

This repository provides unofficial binary wheels for [GDAL](https://github.com/OSGeo/gdal) for Python on Windows.

GDAL, the Geospatial Data Abstraction Library, is an open source MIT licensed translator library for raster and vector geospatial data formats.

The files are unofficial (meaning: informal, unrecognized, personal, unsupported, no warranty, no liability, provided "as is") and made available for testing and evaluation purposes.

Source code changes, if any, have been submitted to the project maintainers or are included in the wheels.

The [Microsoft Visual C++ Redistributable packages for Visual Studio 2022](https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170) is required.

The wheels can be downloaded from the [Releases](https://github.com/cgohlke/gdal.whl/releases) page.

## Release 2023.1.4

This release has been built from the following source code:

- [gdal](https://github.com/OSGeo/gdal) 3.6.1
- [boost](https://boostorg.jfrog.io/artifactory/main/release/1.81.0/source/boost_1_81_0.zip) 1.81.0
- [brotli](https://github.com/google/brotli) 1.0.9
- [bzip2](https://sourceware.org/pub/bzip2/bzip2-1.0.8.tar.gz) 1.0.8
- [c-ares](https://c-ares.org/download/c-ares-1.18.1.tar.gz) 1.18.1
- [c-blosc](https://github.com/Blosc/c-blosc) 1.21.3
- [cfitsio](https://heasarc.gsfc.nasa.gov/FTP/software/fitsio/c/cfitsio-3.49.tar.gz) 3.49
- [charls](https://github.com/team-charls/charls) 2.4.1
- [curl](https://curl.se/download/curl-7.86.0.tar.gz) 7.86.0
- [expat](https://github.com/libexpat/libexpat/releases/download/R_2_4_9/expat-2.4.9.tar.gz) 2.4.9
- [freexl](https://www.gaia-gis.it/gaia-sins/freexl-1.0.6.tar.gz) 1.0.6
- [geos](https://download.osgeo.org/geos/geos-3.11.1.tar.bz2) 3.11.1+lgpl
- [giflib](https://sourceforge.net/projects/giflib/files/giflib-5.2.1.tar.gz) 5.2.1
- [hdf4](https://github.com/HDFGroup/hdf4) 4.2.15
- [hdf5](https://support.hdfgroup.org/ftp/HDF5/releases/hdf5-1.10/hdf5-1.10.9/src/hdf5-1.10.9.tar.gz) 1.10.9
- [imath](https://github.com/AcademySoftwareFoundation/Imath) 3.1.5
- [json-c](https://github.com/json-c/json-c) 0.16
- [lerc](https://github.com/Esri/lerc) 4.0.0
- [libaec](https://gitlab.dkrz.de/k202009/libaec) 1.0.6
- [libdeflate](https://github.com/ebiggers/libdeflate) 1.15
- [libgeotiff](https://github.com/OSGeo/libgeotiff/releases/download/1.7.1/libgeotiff-1.7.1.tar.gz) 1.7.1
- [libjpeg-turbo](https://github.com/libjpeg-turbo/libjpeg-turbo) 2.1.4
- [libjxl](https://github.com/libjxl/libjxl) 0.7.0
- [libkml](https://github.com/libkml/libkml) 1.3.0
- [libpng](https://github.com/glennrp/libpng) 1.6.39
- [libspatialite](https://www.gaia-gis.it/gaia-sins/libspatialite-5.0.1.tar.gz) 5.0.1
- [libssh2](https://www.libssh2.org/download/libssh2-1.10.0.tar.gz) 1.10.0
- [libtiff](https://gitlab.com/libtiff/libtiff) 4.5.0
- [libwebp](https://github.com/webmproject/libwebp) 1.2.4
- [libxml2](https://gitlab.gnome.org/GNOME/libxml2) 2.10.3
- [libxslt](https://gitlab.gnome.org/GNOME/libxslt) 1.1.37
- [lz4](https://github.com/lz4/lz4) 1.9.4
- [minizip-ng](https://github.com/zlib-ng/minizip-ng) 3.0.7
- [netcdf-c](https://downloads.unidata.ucar.edu/netcdf-c/4.8.1/netcdf-c-4.8.1.tar.gz) 4.8.1
- [openexr](https://github.com/AcademySoftwareFoundation/openexr) 3.1.5
- [openjpeg](https://github.com/uclouvain/openjpeg) 2.5.0
- [openssl](https://github.com/openssl/openssl) 1.1.1s
- [pcre2](https://github.com/PCRE2Project/pcre2.git) 10.42
- [proj](https://download.osgeo.org/proj/proj-9.1.1.tar.gz) 9.1.1
- [snappy](https://github.com/google/snappy) 1.1.9
- [sqlite](https://github.com/sqlite/sqlite) 3.40.0
- [uriparser](https://github.com/uriparser/uriparser) 0.9.7
- [win-iconv](https://github.com/OgreTransporter/win-iconv) master
- [xz](https://git.tukaani.org/xz.git) 5.4.0
- [zlib](https://github.com/madler/zlib) 1.2.13
- [zstd](https://github.com/facebook/zstd) v1.5.2

## Build system

- [Windows Dev Kit](https://learn.microsoft.com/en-us/windows/arm/dev-kit/) 2023
- [Visual Studio](https://visualstudio.microsoft.com/vs/community/) 2022 Community 17.4
- [CPython](https://www.python.org/downloads/windows/) 3.8, 3.9, 3.10, 3.11
- [PyPy](https://www.pypy.org/download.html) 3.9
