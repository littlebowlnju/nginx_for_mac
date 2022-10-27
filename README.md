# nginx_for_mac

a directly-useable nginx zip file for MacOS

No need to install homebrew or build from source by yourself😃

## Content

This is an nginx zip file that can be used directly like nginx-for-windows zip file.

By [building nginx from source](https://nginx.org/en/docs/configure.html) on macos system, generating an nginx directory that doesn't depend on any other specific directories or files to use.

The building uses:

- Nginx-1.22
  
- pcre-8.45
  
- openssl-1.1.0
  

## Use

Unzip the file, and use

- `./sbin/nginx -c ./conf/nginx.conf` to start nginx
  
- `./sbin/nginx -s quit` to stop nginx
  
- ...
  
- other commands please refer to [nginx](https://nginx.org/)
