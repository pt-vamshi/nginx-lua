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
 - [alpine-3.8]()
 - [alpine-3.18]()

## Usage
 ```
 docker run -d -p 80:80 -p 443:443 firesh/nginx-lua
 ```
## How
Please view Lua script in nginx conf:

https://github.com/firesh/nginx-lua/blob/master/stable/alpine/nginx.vh.default.conf#L14

## Dockerfile
https://github.com/firesh/nginx-lua/blob/master/stable/alpine/Dockerfile