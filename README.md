About viscid
============

Home: https://github.com/viscid-hub/Viscid

Package license: MIT License

Feedstock license: BSD 3-Clause

Summary: Visualize data on structured meshes in python

Python framework to visualize scientific data on structured meshes.

Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/viscid-hub/viscid-feedstock/master.svg?label=Linux)](https://circleci.com/gh/viscid-hub/viscid-feedstock)
[![OSX](https://img.shields.io/travis/viscid-hub/viscid-feedstock/master.svg?label=macOS)](https://travis-ci.org/viscid-hub/viscid-feedstock)
[![Windows](https://img.shields.io/appveyor/ci/viscid-hub/viscid-feedstock/master.svg?label=Windows)](https://ci.appveyor.com/project/viscid-hub/viscid-feedstock/branch/master)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-viscid-green.svg)](https://anaconda.org/viscid-hub/viscid) | [![Conda Downloads](https://img.shields.io/conda/dn/viscid-hub/viscid.svg)](https://anaconda.org/viscid-hub/viscid) | [![Conda Version](https://img.shields.io/conda/vn/viscid-hub/viscid.svg)](https://anaconda.org/viscid-hub/viscid) | [![Conda Platforms](https://img.shields.io/conda/pn/viscid-hub/viscid.svg)](https://anaconda.org/viscid-hub/viscid) |

Installing viscid
=================

Installing `viscid` from the `viscid-hub` channel can be achieved by adding `viscid-hub` to your channels with:

```
conda config --add channels viscid-hub
```

Once the `viscid-hub` channel has been enabled, `viscid` can be installed with:

```
conda install viscid
```

It is possible to list all of the versions of `viscid` available on your platform with:

```
conda search viscid --channel viscid-hub
```




Updating viscid-feedstock
=========================

If you would like to improve the viscid recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`viscid-hub` channel, whereupon the built conda packages will be available for
everybody to install and use from the `viscid-hub` channel.
Note that all branches in the conda-forge/viscid-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

