# coreos-ubuntu-toolbox

Docker image for use as a toolbox image on CoreOS.

## Usage

Add file .toolboxrc into your user home directory with this content:

    vi ~/.toolboxrc

    TOOLBOX_DOCKER_IMAGE=schoolscout/coreos-ubuntu-toolbox
    TOOLBOX_USER=core

Run it via:

    toolbox --bind=/home/core
