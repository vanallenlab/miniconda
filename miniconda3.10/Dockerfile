FROM ubuntu:22.04

WORKDIR /

RUN apt-get update && \
	apt-get upgrade -y && \
	apt-get install -y wget vim bzip2

RUN wget --quiet https://repo.anaconda.com/miniconda/Miniconda3-py310_23.1.0-1-Linux-x86_64.sh -O ~/miniconda.sh && \
	bash ~/miniconda.sh -b -p /opt/conda && \
	rm ~/miniconda.sh

ENV PATH /opt/conda/bin:$PATH

RUN conda update conda -y
