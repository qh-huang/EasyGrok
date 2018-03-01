## SouceNav = docker + opengrok + vcs-tools

This project makes it easier to navigate source code.

#### usage:
##### 1. edit interested repositories
    vi source/<YAML file>
##### 2. download repositories
    ./sync_source.sh
##### 3. build docker image (only need to do once on each machine)
    ./build_docker.sh
##### 4. run docker image
    ./run_docker.sh
##### 5. browse the repositories on http://localhost:8080/source

#### branches:
- master: commits related to opengrok and docker
- develop: updating source repositories list (for my personal use, checkout this branch if you're interested what I'm currently studying)
