# fflo/java8-server-jre
A build on top of Debian 9

## Image Sizes 
[![](https://badge.imagelayers.io/fflo/java8-server-jre:latest.svg)](https://imagelayers.io/?images=fflo/java8-server-jre:8u202) 8u202, latest

## Using this Image
Primarily, this image has been built to be a base for any Java Application that requires the Server JRE. It also strips out as much as possible to keep the image as lean as it can be.

```Dockerfile
FROM fflo/java8-server-jre:latest
MAINTAINER me <me@me.com>

# Build your java app container here

```
