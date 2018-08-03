About aom
=========

Home: https://aomedia.org/

Package license: BSD custom:PATENTS

Feedstock license: BSD 3-Clause

Summary: Alliance for Open Media video codec

AOMedia Video 1 (AV1), is an open, royalty-free video coding format designed for
video transmissions over the Internet.


Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/loopbio/aom-feedstock/master.svg?label=Linux)](https://circleci.com/gh/loopbio/aom-feedstock)
![OSX disabled](https://img.shields.io/badge/OSX-disabled-lightgrey.svg)
![Windows disabled](https://img.shields.io/badge/Windows-disabled-lightgrey.svg)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-aom-green.svg)](https://anaconda.org/loopbio/aom) | [![Conda Downloads](https://img.shields.io/conda/dn/loopbio/aom.svg)](https://anaconda.org/loopbio/aom) | [![Conda Version](https://img.shields.io/conda/vn/loopbio/aom.svg)](https://anaconda.org/loopbio/aom) | [![Conda Platforms](https://img.shields.io/conda/pn/loopbio/aom.svg)](https://anaconda.org/loopbio/aom) |

Installing aom
==============

Installing `aom` from the `loopbio` channel can be achieved by adding `loopbio` to your channels with:

```
conda config --add channels loopbio
```

Once the `loopbio` channel has been enabled, `aom` can be installed with:

```
conda install aom
```

It is possible to list all of the versions of `aom` available on your platform with:

```
conda search aom --channel loopbio
```




Updating aom-feedstock
======================

If you would like to improve the aom recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`loopbio` channel, whereupon the built conda packages will be available for
everybody to install and use from the `loopbio` channel.
Note that all branches in the loopbio/aom-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.