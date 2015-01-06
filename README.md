simple_webserver_container
==========================

A simple webserver image for Docker.  
This Dockerfile is used to demonstrate how a apache webserver can be setup, with content automatically installed.

To Build:
$ docker build --rm -t simple_web_server .

To Run:
$ docker run -d -p 8888:80 simple_web_server

    browse to http://localhost:8888 to verify container is working

