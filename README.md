About opencascade
=================

Home: https://www.opencascade.com

Package license: LGPL

Feedstock license: BSD 3-Clause

Summary: An object-oriented C++ class library for CAD/CAM/CAE applications

Open CASCADE Technology (OCCT) is an object-oriented C++ class library
designed for rapid production of sophisticated domain-specific
CAD/CAM/CAE applications.


Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/conda-forge/opencascade-feedstock.svg?style=shield)](https://circleci.com/gh/conda-forge/opencascade-feedstock)
OSX: [![TravisCI](https://travis-ci.org/conda-forge/opencascade-feedstock.svg?branch=master)](https://travis-ci.org/conda-forge/opencascade-feedstock)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/conda-forge/opencascade-feedstock?svg=True)](https://ci.appveyor.com/project/conda-forge/opencascade-feedstock/branch/master)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/guyer/opencascade/badges/version.svg)](https://anaconda.org/guyer/opencascade)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/guyer/opencascade/badges/downloads.svg)](https://anaconda.org/guyer/opencascade)

Installing opencascade
======================

Installing `opencascade` from the `guyer` channel can be achieved by adding `guyer` to your channels with:

```
conda config --add channels guyer
```

Once the `guyer` channel has been enabled, `opencascade` can be installed with:

```
conda install opencascade
```

It is possible to list all of the versions of `opencascade` available on your platform with:

```
conda search opencascade --channel guyer
```




Updating opencascade-feedstock
==============================

If you would like to improve the opencascade recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`guyer` channel, whereupon the built conda packages will be available for
everybody to install and use from the `guyer` channel.
Note that all branches in the conda-forge/opencascade-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.