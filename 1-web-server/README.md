# 1-web-server

## Commands 
Note: Run commands from this folder only
  - Create docker image using *Dockerfile* from current folder -> `docker build -t sv-dk-httpd .`
  - Run container on port 8080 -> `docker run -dit --name sv-webapp -p 8080:80 sv-dk-httpd`
