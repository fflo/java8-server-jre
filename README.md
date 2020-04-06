# fflo/java8-server-jre
A build on top of Debian or Ubuntu Linux

## Image Sizes 
[![](https://badge.imagelayers.io/fflo/java8-server-jre:latest.svg)](https://imagelayers.io/?images=fflo/java8-server-jre:latest) 8u202, latest

## Using this Image
Primarily, this image has been built to be a base for any Java Application that requires the Server JRE. It also strips out as much as possible to keep the image as lean as it can be.

Default (:latest) image is based on Ubuntu 18.04 LTS (Bionic Beaver):

```Dockerfile
FROM fflo/java8-server-jre:latest
MAINTAINER me <me@me.com>

# Build your java app container here

```

You can also choose to base on Debian, i.e. Debian 9 (Stretch):

```Dockerfile
FROM fflo/java8-server-jre:debian-stretch
MAINTAINER me <me@me.com>

# Build your java app container here

```
