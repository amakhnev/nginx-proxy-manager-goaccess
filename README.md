# nginx-proxy-manager-goaccess
Easy setup of nginx proxy manager and goaccess

## What is this?

My way of setting up nginx proxy manager and goaccess to monitor traffic. 

* Minimal configuration, feel free to fork and modify for your needs/configuration, or just clone, remove .git folder (`rm -rf .git`) and change as you need.
* Subdirectories mentioned in docker-compose.yaml are created and content not releveant for repo is included into .gitignore files

## How to use

1. Clone this repo, cd into the directory

2. Run `docker-compose up -d`

3. Go to `http://<host>:7880` to access goaccess, go to `http://<host>:81` to access nginx proxy manager

4. To delete all containers and volumes run `docker-compose down -v`

## Credits and relevant links

* https://github.com/xavier-hernandez/goaccess-for-nginxproxymanager - goaccess docker build with GeoIP support and Nginx Proxy Manager out-of-box support
* https://github.com/stockrt/nginx2goaccess - script to convert nginx logs to goaccess format
