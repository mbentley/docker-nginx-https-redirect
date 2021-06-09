mbentley/nginx-https-redirect
=============================

*Note*: the Dockerfile for this repo has been moved to [mbentley/docker-nginx](https://github.com/mbentley/docker-nginx)

docker image for redirecting traffic to https using nginx
based off of mbentley/nginx:latest

To pull this image:
`docker pull mbentley/nginx-https-redirect`

Example usage:
`docker run -d -p 80:80 --name nginx-ssl-redirect mbentley/nginx-https-redirect`

By default, all requests are redirects to https to the same host and URI.
