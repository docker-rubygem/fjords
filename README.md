[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/fjords.svg)](https://hub.docker.com/r/rubygem/fjords/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/fjords.svg)](https://hub.docker.com/r/rubygem/fjords/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/fjords.svg)](https://hub.docker.com/r/rubygem/fjords/)
[![Gem Downloads](https://img.shields.io/gem/dt/fjords.svg)](https://rubygems.org/gems/fjords/)
# fjords

Auto-Generated Docker image for fjords to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/fjords`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/fjords`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/fjords`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/fjords/)
