# Face Recognition

This is a webservice for deployment on AWS Elastic Beanstalk based on [Adam Geitgey's](https://github.com/ageitgey/face_recognition) facial recognition project.

# To Use
This webservice can be deployed to an AWS EC2 instance through docker.

the pre built docker image is here: fhboswell/face-recognition
`docker pull fhboswell/face-recognition`

More information on deployment [here](https://docs.docker.com/get-started/part6/#deploy-your-app-on-a-cloud-provider)


# Info

Built using [dlib](http://dlib.net/)'s state-of-the-art face recognition
built with deep learning. The model has an accuracy of 99.38% on the
[Labeled Faces in the Wild](http://vis-www.cs.umass.edu/lfw/) benchmark.


[![PyPI](https://img.shields.io/pypi/v/face_recognition.svg)](https://pypi.python.org/pypi/face_recognition)
[![Build Status](https://travis-ci.org/ageitgey/face_recognition.svg?branch=master)](https://travis-ci.org/ageitgey/face_recognition)
[![Documentation Status](https://readthedocs.org/projects/face-recognition/badge/?version=latest)](http://face-recognition.readthedocs.io/en/latest/?badge=latest)


## Thanks

* Thanks to [Adam Geitgey's](https://github.com/ageitgey/face_recognition) facial recognition api project.
* Many, many thanks to [Davis King](https://github.com/davisking) ([@nulhom](https://twitter.com/nulhom))
for creating dlib and for providing the trained facial feature detection and face encoding models
used in this library. For more information on the ResNet that powers the face encodings, check out
his [blog post](http://blog.dlib.net/2017/02/high-quality-face-recognition-with-deep.html).
* Thanks to everyone who works on all the awesome Python data science libraries like numpy, scipy, scikit-image,
pillow, etc, etc that makes this kind of stuff so easy and fun in Python.
* Thanks to [Cookiecutter](https://github.com/audreyr/cookiecutter) and the
[audreyr/cookiecutter-pypackage](https://github.com/audreyr/cookiecutter-pypackage) project template
for making Python project packaging way more tolerable.
