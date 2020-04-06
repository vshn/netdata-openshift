# DEPRECATION NOTICE

This image was created at a time where `netdata/netdata` docker image was
not capable of running as an arbitrary user.

With the merge of [PR#6543](https://github.com/netdata/netdata/pull/6543)
this is now in the base image, so this image is not necessary anymore.

We will archive this repository and delete the `vshn/netdata-openshift`
docker image on Docker Hub on **August 1, 2020**.

# netdata-openshift

Docker image derived from official `netdata/netdata` image, but runs as
arbitrary user id, as long as the group is root.

Auto-build from Docker Hub is enabled.

## Build

    docker-compose build

## Run

    docker-compose up --build
