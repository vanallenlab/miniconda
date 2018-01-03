# Miniconda
Miniconda is a minimal implementation of Anaconda and these Docker images build upon Ubuntu 17.04. 

These installations of Miniconda only contain the conda package manager and Python. Once Miniconda is installed, you can use the conda command to install any other packages, create environments, etc. 

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
