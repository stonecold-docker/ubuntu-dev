# ubuntu-dev

#### [ubuntu-x64-dev](https://hub.docker.com/r/forumi0721ubuntux64/ubuntu-x64-dev/)
![Docker Image Version (tag latest semver)](https://img.shields.io/docker/v/forumi0721ubuntux64/ubuntu-x64-dev/latest)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/forumi0721ubuntux64/ubuntu-x64-dev/latest)
![MicroBadger Layers (tag)](https://img.shields.io/microbadger/layers/forumi0721ubuntux64/ubuntu-x64-dev/latest)
![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721ubuntux64/ubuntu-x64-dev)
![Docker Stars](https://img.shields.io/docker/stars/forumi0721ubuntux64/ubuntu-x64-dev)
#### [ubuntu-aarch64-dev](https://hub.docker.com/r/forumi0721ubuntuaarch64/ubuntu-aarch64-dev/)
![Docker Image Version (tag latest semver)](https://img.shields.io/docker/v/forumi0721ubuntuaarch64/ubuntu-aarch64-dev/latest)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/forumi0721ubuntuaarch64/ubuntu-aarch64-dev/latest)
![MicroBadger Layers (tag)](https://img.shields.io/microbadger/layers/forumi0721ubuntuaarch64/ubuntu-aarch64-dev/latest)
![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721ubuntuaarch64/ubuntu-aarch64-dev)
![Docker Stars](https://img.shields.io/docker/stars/forumi0721ubuntuaarch64/ubuntu-aarch64-dev)
#### [ubuntu-armhf-dev](https://hub.docker.com/r/forumi0721ubuntuarmhf/ubuntu-armhf-dev/)
![Docker Image Version (tag latest semver)](https://img.shields.io/docker/v/forumi0721ubuntuarmhf/ubuntu-armhf-dev/latest)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/forumi0721ubuntuarmhf/ubuntu-armhf-dev/latest)
![MicroBadger Layers (tag)](https://img.shields.io/microbadger/layers/forumi0721ubuntuarmhf/ubuntu-armhf-dev/latest)
![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721ubuntuarmhf/ubuntu-armhf-dev)
![Docker Stars](https://img.shields.io/docker/stars/forumi0721ubuntuarmhf/ubuntu-armhf-dev)



----------------------------------------
#### Description

* Distribution : [Ubuntu](https://www.ubuntu.com/)
* Architecture : x64,aarch64,armhf
* Appplication : -
    - Development environment



----------------------------------------
#### Run

```sh
docker run -i -t --rm \
           -e RUN_USER_NAME=<user_name> \
           -e RUN_USER_UID=<user_uid> \
           -e RUN_USER_GID=<user_gid> \
           forumi0721ubuntu[ARCH]/ubuntu-[ARCH]-dev:latest
```



----------------------------------------
#### Usage

* Run docker container and login.
    - Default user name : forumi0721



----------------------------------------
#### Docker Options

| Option             | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Ports

| Port               | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Volumes

| Volume             | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Environment Variables

| ENV                | Description                                      |
|--------------------|--------------------------------------------------|
| RUN_USER_NAME      | login user name (default:forumi0721)             |
| RUN_USER_UID       | login user uid (default:1000)                    |
| RUN_USER_GID       | login user gid (default:100)                     |

