FROM continuumio/miniconda

RUN apt-get update
RUN apt-get install -y build-essential

RUN conda install -y python=3.7

RUN conda install cudatoolkit=10.1 cudnn

RUN pip install brainreg 
RUN pip install cellfinder

