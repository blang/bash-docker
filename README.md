# Minimal bash docker images
You need bash, but ubuntu images are around 200MB huge? 

Check out my [blog post](https://www.blang.io/2015/04/18/how-to-build-the-smallest-docker-containers.html) about the smallest base images for docker.

Here are solutions:

- Based on busybox (6MB) `blang/busybox-bash` ([Github](https://github.com/blang/busybox-bash-docker), [Dockerhub](https://registry.hub.docker.com/u/blang/busybox-bash/))
- Based on gliderlabs/alpine (6.5MB) `blang/alpine-bash` ([Github](https://github.com/blang/alpine-bash-docker), [Dockerhub](https://registry.hub.docker.com/u/blang/alpine-bash/))

If you only need bash in the future, use busybox. Otherwise use alpine.