# Raspberry Pi - Docker image

## Why? 

To allow compilation of C software to binaries compatible with raspberry pi.

On the distribution used by 'Rasplex', for example, there is no package manager,
and no (easy) way to install `make` for instance.

With this image, it is possible to compile binaries directly on your computer.
And they'll be compatible with your Raspberry Pi ... hopefully :)

> ## Note
> 
> The build is not automated w/ Docker Hub because Docker Hub does not support building RaspberryPi images.  
> Use: `push_image.sh` script instead.
>
> Might want to use one of these images actually: (as base)
> https://docs.resin.io/runtime/resin-base-images/?ref=dockerhub#raspberry-pi-3
>
