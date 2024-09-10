FROM mcr.microsoft.com/devcontainers/anaconda:1-3


RUN conda install -y python=3.6
RUN conda create -n pysyft python=3
RUN conda activate pysyft
RUN conda install numpy jupyter notebook
RUN conda install pytorch torchvision -c pytorch
RUN pip install syft
#make jupyter use password instead of token
RUN jupyter server password
RUN jupyter notebook