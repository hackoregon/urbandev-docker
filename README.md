# HackOregon UrbanDev Docker Environment

Fork this repository to generate a local testing environment.

Please help document any processes here!

This is very much a work in progress.

Implements:
 - postgresql server
 - nginx w/uwsgi
 - deployment of backend
 - deployment of frontend

Docker Container:
 - NGINX will be available at http://localhost:8080
 - Postgres is available at pgsql://localhost:55432
 - urbandev frontend and backend are cloned to the 'src' directory.
 - Databases will be populated from a dump file not included in this repository.


## Docker Installation

You will need to install both VirtualBox and Docker for your operating system.

Operating system in Docker container is Ubuntu 14.04.x LTS.
