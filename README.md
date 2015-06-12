mosquitto
=========

a docker encapsulation of the mosquitto mqtt broker available at  http://mosquitto.org

uses the latest build from ppa:mosquitto-dev/mosquitto-ppa on a ubuntu:trusty base image

just a basic mosquitto server listening on 1883 without config files (the defaults that the server starts with)

Start
=====

	docker run -p 1883:1883 benediktarnold/mosquitto
