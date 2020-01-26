# Docker

> Will create multiple set of scripts for clarity.
> Version details:
>    - OS: Win10 Home
>    - Docker version 19.03.5, build 633a0ea

## Basic/useful commands 
For details check my blog: http://sv-technical.blogspot.com/2019/12/terraform.html<br>
  - Check version -> `docker --version`
  - List images -> `docker image ls`
  - List all container -> `docker container ls --all`
  - Delete stopped containers -> `docker container prune`
  - Display processes or stopped processes (-a) -> `docker ps` or `docker ps -a`
  
## 1-web-server 
This folder contains sample scripts that
  - create docker image from httpd with version 2.4
  - Dockerfile -> has commands to be executed once docker is created
    - in this case files will be copied from source to destination
  - For more details go to folder and refer README.md

## 2-multiple-web-servers 
This folder contains sample scripts that
  - create docker image from httpd with version 2.4
  - Configure multiple virtual hosts
    - You need to add those names to local hosts file to test on local system (C:\Windows\System32\drivers\etc\hosts)
    - copy config for httpd vhosts
    - copy different folders for different hosts
  - Different folder contents delivered for different hosts
  - For more details go to folder and refer README.md
