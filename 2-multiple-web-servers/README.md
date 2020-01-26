# 2-multiple-web-servers

## Commands 
Note: Run commands from this folder only
  - Create docker image using *Dockerfile* from current folder -> `docker build -t sv-dk-httpd .`
  - Run container -> `docker run -dit --name sv-webapp -p 80:80 sv-dk-httpd`
