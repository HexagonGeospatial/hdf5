HDF5 version 1.15.0 currently under development

![HDF5 Logo](doxygen/img/HDF5.png)

[![develop cmake build status](https://img.shields.io/github/actions/workflow/status/HDFGroup/hdf5/cmake.yml?branch=develop&label=HDF5%20develop%20CMake%20CI)](https://github.com/HDFGroup/hdf5/actions/workflows/cmake.yml?query=branch%3Adevelop)
[![develop autotools build status](https://img.shields.io/github/actions/workflow/status/HDFGroup/hdf5/autotools.yml?branch=develop&label=HDF5%20develop%20Autotools%20CI)](https://github.com/HDFGroup/hdf5/actions/workflows/autotools.yml?query=branch%3Adevelop)
[![netCDF build status](https://img.shields.io/github/actions/workflow/status/HDFGroup/hdf5/netcdf.yml?branch=develop&label=netCDF)](https://github.com/HDFGroup/hdf5/actions/workflows/netcdf.yml?query=branch%3Adevelop)
[![h5py build status](https://img.shields.io/github/actions/workflow/status/HDFGroup/hdf5/h5py.yml?branch=develop&label=h5py)](https://github.com/HDFGroup/hdf5/actions/workflows/h5py.yml?query=branch%3Adevelop)
[![CVE regression](https://img.shields.io/github/actions/workflow/status/HDFGroup/hdf5/cve.yml?branch=develop&label=CVE)](https://github.com/HDFGroup/hdf5/actions/workflows/cve.yml?query=branch%3Adevelop)
[![HDF5 VOL connectors build status](https://img.shields.io/github/actions/workflow/status/HDFGroup/hdf5/vol.yml?branch=develop&label=HDF5-VOL)](https://github.com/HDFGroup/hdf5/actions/workflows/vol.yml?query=branch%3Adevelop)
[![HDF5 VFD build status](https://img.shields.io/github/actions/workflow/status/HDFGroup/hdf5/vfd.yml?branch=develop&label=HDF5-VFD)](https://github.com/HDFGroup/hdf5/actions/workflows/vfd.yml?query=branch%3Adevelop)
[![1.14 cmake build status](https://img.shields.io/github/actions/workflow/status/HDFGroup/hdf5/cmake.yml?branch=hdf5_1_14&label=HDF5%201.14%20CMake%20CI)](https://github.com/HDFGroup/hdf5/actions/workflows/cmake.yml?query=branch%3Ahdf5_1_14)
[![1.14 autotools build status](https://img.shields.io/github/actions/workflow/status/HDFGroup/hdf5/autotools.yml?branch=hdf5_1_14&label=HDF5%201.14%20Autotools%20CI)](https://github.com/HDFGroup/hdf5/actions/workflows/autotools.yml?query=branch%3Ahdf5_1_14)
[![BSD](https://img.shields.io/badge/License-BSD-blue.svg)](https://github.com/HDFGroup/hdf5/blob/develop/COPYING)

[HPC configure/build/test results](https://my.cdash.org/index.php?project=HDF5)

*Please refer to the release_docs/INSTALL file for installation instructions.*

This repository contains a high-performance library's source code and a file format
specification that implements the HDF5® data model. The model has been adopted across
many industries, and this implementation has become a de facto data management standard
in science, engineering, and research communities worldwide.

The HDF Group is the developer, maintainer, and steward of HDF5 software. Find more
information about The HDF Group, the HDF5 Community, and other HDF5 software projects,
tools, and services at [The HDF Group's website](https://www.hdfgroup.org/). 

DOCUMENTATION
-------------
This release is fully functional for the API described in the documentation.

   https://hdfgroup.github.io/hdf5/develop/_l_b_a_p_i.html

Full Documentation and Programming Resources for this release can be found at

   https://hdfgroup.github.io/hdf5/develop/index.html

The latest doxygen documentation generated on changes to develop is available at:

   https://hdfgroup.github.io/hdf5/develop

See the [RELEASE.txt](release_docs/RELEASE.txt) file in the [release_docs/](release_docs/) directory for information specific
to the features and updates included in this release of the library.

Several more files are located within the [release_docs/](release_docs/) directory with specific
details for several common platforms and configurations.

    INSTALL - Start Here. General instructions for compiling and installing the library
    INSTALL_CMAKE  - instructions for building with CMake (Kitware.com)
    INSTALL_parallel - instructions for building and configuring Parallel HDF5
    INSTALL_Windows and INSTALL_Cygwin - MS Windows installations.



HELP AND SUPPORT
----------------
Information regarding Help Desk and Support services is available at

   https://help.hdfgroup.org 



FORUM and NEWS
--------------
The [HDF Forum](https://forum.hdfgroup.org) is provided for public announcements and discussions
of interest to the general HDF5 Community.

   - News and Announcements
   https://forum.hdfgroup.org/c/news-and-announcements-from-the-hdf-group

   - HDF5 Topics
   https://forum.hdfgroup.org/c/hdf5

These forums are provided as an open and public service for searching and reading.
Posting requires completing a simple registration and allows one to join in the
conversation.  Please read the [instructions](https://forum.hdfgroup.org/t/quickstart-guide-welcome-to-the-new-hdf-forum
) pertaining to the Forum's use and configuration.

RELEASE SCHEDULE
----------------

![HDF5 release schedule](doc/img/release-schedule.png) 

HDF5 does not release on a regular schedule. Instead, releases are driven by
new features and bug fixes, though we try to have at least one release of each
maintenance branch per year. Future HDF5 releases indicated on this schedule
are tentative.

| Release | New Features |
| ------- | ------------ |
| 1.14.5 | oss-fuzz fixes, ros3 VFD improvements |
| 1.14.6 | Last maintenance release of 1.14 |
| 1.16.0 | Complex number support, updated library defaults (cache sizes, etc.) |
| 2.0.0 | Multi-threaded HDF5, crashproofing / metadata journaling, Full (VFD) SWMR, encryption, digital signatures, sparse datasets, improved storage for variable-length datatypes, better Unicode support (especially on Windows), semantic versioning |

Some HDF5 2.0.0 features listed here may be released in a 1.16.x release.

This list of feature release versions is also tentative, and the specific release
in which a feature is introduced may change.


SNAPSHOTS, PREVIOUS RELEASES AND SOURCE CODE
--------------------------------------------
Periodically development code snapshots are provided at the following URL:
    
   https://github.com/HDFGroup/hdf5/releases/tag/snapshot

Source packages for current and previous releases are located at:
    
   https://support.hdfgroup.org/downloads/HDF5

Development code is available at our Github location:
    
   https://github.com/HDFGroup/hdf5.git

