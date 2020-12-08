# docker-images-sync
pull docker images

## usage

- Pull images from dockerhub or other registry then retag push to youself dockerhub or aliyun registry

[![Build Status](https://www.travis-ci.org/Satangelsx/docker-images-sync.svg?branch=main)](https://www.travis-ci.org/Satangelsx/docker-images-sync)

use travis-ci pull docker images from google gcr.io or coreos quay.io to dockerhub or aliyun-registry

1. Save image url to images.txt.
2. Auto run travis-ci jobs to pull retag and push images.
3. login dockerhub or aliyun registry check images.
