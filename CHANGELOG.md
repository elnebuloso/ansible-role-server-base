# changelog

## 2.6.0

- changed default setting to server_base_install_linux_image_extra: "no"

## 2.5.0

- new config server_base_install_linux_image_extra

## 2.4.0

- removed install of ntp
- removed install of timezone
- install ntp and timezone with geerlingguy.ntp

## 2.3.0

- added default package systemd

## 2.2.0

- fixed server_base_update_ntp, missing handler
- new config server_base_apt_upgrade
- added aptitude for using server_base_apt_upgrade with full and safe

## 2.1.0

- added default package multitail

## 2.0.0

- supporting ubuntu 16.04 xenial

## 1.3.0

- os specific configuration
- ubuntu14 specific configuration

## 1.2.0

- added default package curl
- added default package locate

## 1.1.1

- updated documentation
- updated aliases

## 1.1.0

- added default apt package apt-transport-https
- added default apt package ca-certificates

## 1.0.0

- initial commit