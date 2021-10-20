### Generate base jupyterhub image for pyansys.com

This repository contains a `Dockerfile` to generate the base image
required for upstream images for pyansys.com.  Images are generated by
pushing a git tag starting with `v`.

The image is pushed to the github repository ghcr.io.

It can be run locally with `build_and_run_image.sh`

#### Notes
 - GPU image on dev.pyansys.com contains additional GPU remote
   rendering features not included in this image.  Ping @akaszynski to
   create that branch.
