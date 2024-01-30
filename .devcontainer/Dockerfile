FROM mcr.microsoft.com/devcontainers/python:1-3.12-bullseye
RUN apt-get update \
    && apt-get install -y wget \
    bash \
    git \
    gcc \
    g++ \
    gfortran \
    liblapack-dev \
    libamd2 \
    libcholmod3 \
    libopencv-dev \
    libmetis-dev \
    libsuitesparse-dev \
    libnauty2-dev \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* \
    && pip3 install --upgrade setuptools wheel pip
