# dl-nn-docker

Deep Learning Docker image containing neural networks tools

## Description

Deep Learning base image containing neural networks tools for machine learning such as Python 3, Keras with Tensorflow and SciKitLearn (based Ubuntu 16.04).

Based on: https://hub.docker.com/r/waleedka/modern-deep-learning/~/dockerfile/


## Usage

```
sudo docker build --rm -t zlig/dl-nn-docker .
sudo docker run -it -p 9888:8888 -p 6006:6006 -v /tmp:/host zlig/dl-nn-docker
sudo docker exec -it <IMAGE_ID> /bin/bash
./run_jupiter.sh
```
