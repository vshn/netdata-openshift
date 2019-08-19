# netdata-openshift

Docker image derived from official `netdata/netdata` image, but runs as
arbitrary user id, as long as the group is root.

Auto-build from Docker Hub is enabled.

## Build

    docker-compose build

## Run

    docker-compose up --build
