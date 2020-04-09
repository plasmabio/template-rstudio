# Template materials with RStudio

Example repository to create an environment with TSudio and course materials.


## Try it on Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/plasmabio/template-rstudio/master?urlpath=lab) Jupyter+R

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/plasmabio/template-rstudio/master?urlpath=rstudio) RStudio


## Structure of the repo

This repository follows the [binder-examples/r](https://github.com/binder-examples/r) example very closely.

[`repo2docker`](https://repo2docker.readthedocs.io) is the underlying tool that is used to build an environment from a repository.

`repo2docker` can be configured with several types of files. In the case of this repo:

- `runtime.txt`: specify the R version tu use
- `install.R`: specify R dependencies

Both Jupyter Lab and RStudio are installed.

Once created, the environment can be reused without building it again.

For more information, see the [extensive rep2docker documentation](https://repo2docker.readthedocs.io).


## Materials

Materials can be added anywhere to this repository, either at the top level or in subdirectory.

When building the environment, the materials (and any other file) will be copied to the Docker image.

