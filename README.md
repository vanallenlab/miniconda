# Miniconda
Miniconda is a minimal implementation of Anaconda that only contains the conda package manager and Python. These Docker images build upon Ubuntu 17.04, as oppose to the [official continuumio images](https://hub.docker.com/r/continuumio/miniconda3/) which use Debian. Once Miniconda is installed, you can use the conda command to install any other packages, create environments, etc.

```
$ conda install numpy
...
$ conda install -c bioconda samtools
...
$ conda create -n py3k anaconda python=3
...
```

## Offical documentation
[Read more about Miniconda here](https://conda.io/miniconda.html). This README.md file is slightly modified version of information from the official page.

## Van Allen Lab hyperlinks for miniconda
[Dockerhub for miniconda base images](https://hub.docker.com/r/vanallenlab/miniconda/)

[Github repository for miniconda](https://github.com/vanallenlab/miniconda)
