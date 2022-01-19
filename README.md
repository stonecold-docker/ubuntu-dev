# ubuntu-dev
![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721/ubuntu-dev)
![Docker Stars](https://img.shields.io/docker/stars/forumi0721/ubuntu-dev)



----------------------------------------
### x64
![Docker Image Size](https://img.shields.io/docker/image-size/forumi0721/ubuntu-dev/x64)
### aarch64
![Docker Image Size](https://img.shields.io/docker/image-size/forumi0721/ubuntu-dev/aarch64)



----------------------------------------
#### Description

* Distribution : [Ubuntu](https://www.ubuntu.com/)
* Architecture : x64,aarch64
* Appplication : -
    - Development environment



----------------------------------------
#### Run

```sh
docker run -i -t --rm \
           -e RUN_USER_NAME=<user_name> \
           -e RUN_USER_UID=<user_uid> \
           -e RUN_USER_GID=<user_gid> \
           forumi0721/ubuntu-dev:[ARCH_TAG]
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

