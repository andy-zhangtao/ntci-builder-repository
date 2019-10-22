# ntci-builder-repository [![Build Status](https://travis-ci.org/andy-zhangtao/ntci-builder-repository.svg?branch=master)](https://travis-ci.org/andy-zhangtao/ntci-builder-repository)
All NTCI Builder Docker Base Image

All base image has a common name: `vikings/ntci-base`. Language as a suffix after this name, like `go`, it's name is `vikings/ntci-base-go:[tag]`.

## BaseImage

There has a base image. It base on ubuntu, install `docker`, `curl`, `git` and `wget`.

If you wants to build your image, there are two tool must install.

## Require Tool:

* git
* docker

The belowing is valid language and its image:
## Valid Language:

1. [Golang]

    * go:latest

2. [generic]

    * ubuntu:latest

3. [node]

    * node:yarn