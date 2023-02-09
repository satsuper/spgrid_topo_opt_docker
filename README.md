# Dockerfiles for spgrid_topo_opt
Dockerfiles for [yuanming-hu/spgrid_topo_opt](https://github.com/yuanming-hu/spgrid_topo_opt)

## TODO
- [ ] CUDA support
- [ ] Vulkan support

## Troubleshooting
You may see warnings that Qt could not be initialised or that views cannot be created.

You can get past this by connecting the container to an X server on the Docker host.

# Docker Hub
Images can be found at [satsuper/spgrid_topo_opt](https://hub.docker.com/r/satsuper/spgrid_topo_opt).

As the code uses SIMD it's probably best to build the image from the Dockerfile yourself to optimise to your hardware.
