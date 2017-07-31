# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).


## [2.9.0]
### Changed
- bugfix missing aptitude for upgrading packages, changed install order


## [2.8.0]
### Changed
- removed locales, suggesting https://galaxy.ansible.com/tersmitten/locales/
- added variable server_base_optional_packages


## [2.7.0]
### Changed
- check server_base_os is defined


## [2.6.0]
### Changed
- changed default setting to server_base_install_linux_image_extra: "no"


## [2.5.0]
### Changed
- new config server_base_install_linux_image_extra


## [2.4.0]
### Changed
- removed install of ntp
- removed install of timezone
- install ntp and timezone with geerlingguy.ntp


## [2.3.0]
### Changed
- added default package systemd

## [2.2.0]
### Changed
- fixed server_base_update_ntp, missing handler
- new config server_base_apt_upgrade
- added aptitude for using server_base_apt_upgrade with full and safe


## [2.1.0]
### Changed
- added default package multitail


## [2.0.0]
### Changed
- supporting ubuntu 16.04 xenial


## [1.3.0]
### Changed
- os specific configuration
- ubuntu14 specific configuration


## [1.2.0]
### Changed
- added default package curl
- added default package locate


## [1.1.1]
### Changed
- updated documentation
- updated aliases


## [1.1.0
### Changed
- added default apt package apt-transport-https
- added default apt package ca-certificates


## [1.0.0]
### Changed
- initial commit