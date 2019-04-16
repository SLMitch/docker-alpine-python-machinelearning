[![Docker Stars](https://img.shields.io/docker/stars/slmitch/alpine-python-machinelearning.svg?style=flat-square)](https://hub.docker.com/r/slmitch/alpine-python-machinelearning/)
[![Docker Pulls](https://img.shields.io/docker/pulls/slmitch/alpine-python-machinelearning.svg?style=flat-square)](https://hub.docker.com/r/slmitch/alpine-python-machinelearning/)


Python Machine Learning tools Docker image
==========================================

This image contains popular Machine Leaning tools:

* numpy
* pandas
* scipy
* scikit-learn

Download size of this image is only:

[![](https://images.microbadger.com/badges/image/slmitch/alpine-python-machinelearning.svg)](http://microbadger.com/images/slmitch/alpine-python-machinelearning "Get your own image badge on microbadger.com")


Usage Example
-------------

```bash
$ docker run --rm slmitch/alpine-python-machinelearning python3 -c 'import numpy; print(numpy.arange(3))'
```

Once you have run this command you will get printed `array([0, 1, 2])` from Python!
