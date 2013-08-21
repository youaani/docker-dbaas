# Docker Databases As A Service

### Current stage: Alpha

## Purpose & features

* Deploy and monitor MySQL and MongoDB databases on [Docker](http://www.docker.io)
* Command line tool
* Web UI
* Pluggable database type (write your own adapter)

![Screenshot](./static/img/screenshot.png "List of servers")

## Install

TODO

## Use

TODO

## Depends and uses

* [Flask](http://flask.pocoo.org)
* [Flask-Script](http://flask-script.readthedocs.org/en/latest/)
* [Docker](http://www.docker.io)

## TODO

* See about the circular imports ugly mess (Flask Plugin/Extension?)
* Split optionnal and mandatory requirements (+ tests at import)
* Implement "port mapping?" option
* Automatic tests