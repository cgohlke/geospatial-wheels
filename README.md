# Geospatial library wheels for Python on Windows

This repository provides unofficial binary wheels for some geospatial libraries for Python on Windows.

The files are unofficial (meaning: informal, unrecognized, personal, unsupported, no warranty, no liability, provided "as is") and made available for testing and evaluation purposes.

Source code changes, if any, have been submitted to the project maintainers or are included in the wheels.

The [Microsoft Visual C++ Redistributable packages for Visual Studio 2022](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170) is required.

The wheels can be downloaded from the [Releases](https://github.com/cgohlke/geospatial-wheels/releases) page.

## Release 2025.3.30

Binary wheels for the following packages are included in the
[release](https://github.com/cgohlke/geospatial-wheels/releases/tag/v2025.3.30):

- [basemap](https://pypi.org/project/basemap/) 1.4.1
- [Cartopy](https://pypi.org/project/Cartopy/) 0.24.1
- [cftime](https://pypi.org/project/cftime/) 1.6.4
- [Fiona](https://pypi.org/project/Fiona/) 1.10.1
- [GDAL](https://pypi.org/project/GDAL/) 3.10.2
- [netCDF4](https://pypi.org/project/netCDF4/) 1.7.2
- [pygeos](https://pypi.org/project/pygeos/) 0.14.0
- [pyproj](https://pypi.org/project/pyproj/) 3.7.1
- [rasterio](https://pypi.org/project/rasterio/) 1.4.3
- [Rtree](https://pypi.org/project/Rtree/) 1.4.0
- [shapely](https://pypi.org/project/shapely/) 2.0.7

The wheels include the following statically or dynamically linked libraries:

- [aom](https://aomedia.googlesource.com/aom) 3.12.0
- [boost](https://boostorg.jfrog.io/artifactory/main/release/1.87.0/source/boost_1_87_0.zip) 1.87.0
- [brotli](https://github.com/google/brotli) 1.1.0
- [bzip2](https://sourceware.org/pub/bzip2/bzip2-1.0.8.tar.gz) 1.0.8
- [c-ares](https://github.com/c-ares/c-ares/releases/download/v1.34.4/c-ares-1.34.4.tar.gz) 1.34.4
- [c-blosc](https://github.com/Blosc/c-blosc) 1.21.6
- [cfitsio](https://heasarc.gsfc.nasa.gov/FTP/software/fitsio/c/cfitsio-3.49.tar.gz) 3.49
- [charls](https://github.com/team-charls/charls) 2.4.2
- [curl](https://curl.se/download/curl-8.12.1.tar.gz) 8.12.1
- [dav1d](https://github.com/videolan/dav1d) 1.5.1
- [expat](https://github.com/libexpat/libexpat/releases/download/R_2_7_1/expat-2.7.1.tar.gz) 2.7.1
- [freexl](https://www.gaia-gis.it/gaia-sins/freexl-2.0.0.tar.gz) 2.0.0
- [gdal](https://github.com/OSGeo/gdal) 3.10.2
- [geos](https://download.osgeo.org/geos/geos-3.13.1.tar.bz2) 3.13.1+lgpl
- [giflib](https://sourceforge.net/projects/giflib/files/giflib-5.2.2.tar.gz) 5.2.2
- [hdf4](https://github.com/HDFGroup/hdf4) 4.3.0
- [hdf5](https://github.com/HDFGroup/hdf5/releases/download/hdf5_1.14.6/hdf5-1.14.6.tar.gz) 1.14.6
- [imath](https://github.com/AcademySoftwareFoundation/Imath) 3.1.12
- [json-c](https://github.com/json-c/json-c) 0.17
- [lerc](https://github.com/Esri/lerc) 4.0.4
- [libaec](https://gitlab.dkrz.de/k202009/libaec) 1.1.3
- [libavif](https://github.com/AOMediaCodec/libavif) 1.2.1
- [libdeflate](https://github.com/ebiggers/libdeflate) 1.23
- [libgeotiff](https://github.com/OSGeo/libgeotiff/releases/download/1.7.4/libgeotiff-1.7.4.tar.gz) 1.7.4
- [libjpeg-turbo](https://github.com/libjpeg-turbo/libjpeg-turbo) 3.1.0
- [libjxl](https://github.com/libjxl/libjxl) 0.11.1
- [libkml](https://github.com/libkml/libkml) 1.3.0
- [libpng](https://github.com/glennrp/libpng) 1.6.47
- [libspatialite](http://www.gaia-gis.it/gaia-sins/libspatialite-sources/libspatialite-5.1.0.tar.gz) 5.1.0
- [libssh2](https://www.libssh2.org/download/libssh2-1.11.1.tar.gz) 1.11.1
- [libtiff](https://gitlab.com/libtiff/libtiff) 4.7.0
- [libwebp](https://github.com/webmproject/libwebp) 1.5.0
- [libxml2](https://gitlab.gnome.org/GNOME/libxml2) 2.12.10
- [libxslt](https://gitlab.gnome.org/GNOME/libxslt) 1.1.42
- [libyuv](https://chromium.googlesource.com/libyuv/libyuv) main
- [lz4](https://github.com/lz4/lz4) 1.10.0
- [lzma](https://github.com/tukaani-project/xz) 5.6.4
- [minizip-ng](https://github.com/zlib-ng/minizip-ng) 4.0.7
- [netcdf-c](https://github.com/Unidata/netcdf-c) 4.9.3
- [nghttp2](https://github.com/nghttp2/nghttp2) 1.65.0
- [openexr](https://github.com/AcademySoftwareFoundation/openexr) 3.3.3
- [openjpeg](https://github.com/uclouvain/openjpeg) 2.5.3
- [openssl](https://github.com/openssl/openssl) 3.0.16
- [pcre2](https://github.com/PCRE2Project/pcre2.git) 10.44
- [postgresql](https://ftp.postgresql.org/pub/source/v15.9/postgresql-15.9.tar.gz) 15.9
- [proj](https://download.osgeo.org/proj/proj-9.5.1.tar.gz) 9.5.1
- [qhull](https://github.com/qhull/qhull) 8.0.2
- [rav1e](https://github.com/xiph/rav1e) 0.7.1
- [snappy](https://github.com/google/snappy) 1.2.2
- [sqlite](https://github.com/sqlite/sqlite) 3.49.1
- [uriparser](https://github.com/uriparser/uriparser) 0.9.8
- [win-iconv](https://github.com/OgreTransporter/win-iconv) master
- [zlib](https://github.com/madler/zlib) 1.3.1
- [zstd](https://github.com/facebook/zstd) 1.5.7

## Build system

- [Windows Dev Kit](https://learn.microsoft.com/en-us/windows/arm/dev-kit/) 2023
- [Visual Studio](https://visualstudio.microsoft.com/vs/community/) 2022 Community 17.13
- [CPython](https://www.python.org/downloads/windows/) 3.10, 3.11, 3.12, 3.13 (win32, win-amd64, win-arm64)
