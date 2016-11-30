# Nginx with Lua module support

This repo is Dockerfile for [firesh/nginx-lua](https://hub.docker.com/r/firesh/nginx-lua/) images in docker hub.
It is base offical [Nignx Dockerfile](https://github.com/nginxinc/docker-nginx/blob/master/stable/alpine/Dockerfile).
To minimize the docker image, we build from Apline Linux.

Only 2 modules is add:
 - [simpl/ngx_devel_kit](https://github.com/simpl/ngx_devel_kit)
 - [openresty/lua-nginx-module](https://github.com/openresty/lua-nginx-module)

## Tags
 - [latest]()
 - [alpine]()

## Usage
 ```
 docker run -d -p 80:80 -p 443:443 firesh/ngingx-lua
 ```
