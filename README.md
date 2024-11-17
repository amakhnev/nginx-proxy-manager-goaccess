# nginx-proxy-manager-goaccess
Easy setup of nginx proxy manager and goaccess

## What is this?

My way of setting up nginx proxy manager and goaccess to monitor traffic. 

* Minimal configuration, feel free to fork and modify for your needs, or just use it as is
* Required subdirectories are created and content not releveant for repo is included into gitignore 

## How to use

1. Clone this repo, cd into the directory

2. Run `docker compose up -d`

3. Go to `http://<host>:7880` to access goaccess

4. To delete all containers and volumes run `docker compose down -v`

## 


## Credits and relevant links

* https://github.com/stockrt/nginx2goaccess - script to convert nginx logs to goaccess format
* https://github.com/xavier-hernandez/goaccess-for-nginxproxymanager - goaccess distribution with a lot of work done