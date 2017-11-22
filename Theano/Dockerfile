FROM resin/rpi-raspbian:stretch

RUN apt-get update && apt-get install -y \
  build-essential \
  gfortran \
  git \
  wget \
  liblapack-dev \
  libopenblas-dev \
  python3-dev \
  python3-numpy \
  python3-scipy \
  python3-pip \
  python3-nose 



RUN pip3 install --upgrade pip
RUN pip3 install --upgrade six

RUN apt-get install python3-setuptools
RUN pip3 install --upgrade --no-deps git+git://github.com/Theano/Theano.git



