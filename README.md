# python-cli-whereami

## Description
This is a POC project to demonstrate
a python console app.

## Tech stack
- perl
- python3
  - os

## Docker stack
- docker-cli
- alpine:latest
- centos:latest
- ubuntu:latest

## Requirements
Docker desktop must be installed and the application
being called must be linux compatiple.

## To run
Alpine: `sudo ./install.sh -u`
Centos: `sudo ./install.sh -u -c`
Ubuntu: `sudo ./install.sh -u -u`

## To stop (optional)
`sudo ./install.sh -d`

## To see help
`sudo ./install.sh -h`
