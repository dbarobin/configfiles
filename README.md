# Config files-By Robin Wen #

## Project Summary ##

> Config files about linux and service on it. This scripts collected via work. You may get massive useful skills throgh the script.

## Version Information ##
> Majority of scripts pass-test in RHEL 6.1, part of scripts pass-test in Debian 7.6/Ubuntu 14.04. I will give clear indication of this scripts in the **Scripts and Dirs Summary**.

## Change Log ##

2014-06-11
> Documentation version is **1.0**, Documentation name is **Config files-By Robin Wen**, Comment is **All of Scripts pass-test**, By Robin。

2014-11-17
> Documentation version is **2.0**, Documentation name is **Config files-By Robin Wen**, Comment is **All of Scripts pass-test, and add the summary of scripts**, By Robin。

2014-11-18
> Documentation version is **2.1**, Documentation name is **Config files-By Robin Wen**, Comment is **Add the nginx configuration file, and add the desc of this file**, By Robin。

2014-11-20
> Documentation version is **2.2**, Documentation name is **Config files-By Robin Wen**, Comment is **Add the locale configuration file, and add the desc of this file**, By Robin。

## Lists of File ##

* 90-disk.rules [net]
* cluster.conf [ha]
* local_iso.repo [yum]
* rc.local [config]
* nginx [d]
	* api.dbarobin.conf [conf] 
	* default.conf [conf]
	* default.conf.bak [conf]
	* example_ssl.conf.bak [conf]
	* nginx.conf [conf]
	* pma.conf [conf]
	* pma.dbarobin.conf [conf]
	* puma.conf [conf]
	* redmine.conf [conf]
	* webvirtmgr.conf [conf]
	* dbarobin.conf [conf]
* locale.gen [config]

## Scripts and Dirs Summary ##

### 90-disk.rules [net] ###
> Storage binding via iscsi. Use this script in RHEL 6.1.

### cluster.conf [ha] ###
> Cluster conf through ocfs2. Use this script in RHEL 6.1.

### local_iso.repo [yum] ###
> Use local rhel iso to config local yum source. Use this script in RHEL 6.1.

### rc.local  [config] ###
> Local linux config file. Define ntp, mount dir and restart httpd. Use this script in RHEL 6.1.

### nginx [d] ###
> Nginx config file. Use this script in RHEL 6.5 and Ubuntu 12.04.

#### api.dbarobin.conf ####
> Api configuration file of dbarobin.com.

#### default.conf [conf] ####
> Nginx default configuration file. Nginx installed via apt-get.

#### default.conf.bak [conf] ####
> Backup of nginx default configuration file. Nginx installed via apt-get.

#### example_ssl.conf.bak [conf] ####
> Nginx example ssl configuration file. Nginx installed via apt-get.

#### nginx.conf [conf] ####
> Nginx default configuration file. Nginx installed via source.

#### pma.conf [conf] ####
> Pma configuration file.

#### pma.dbarobin.conf [conf] ####
> Pma configuration file of dbarobin.com.

#### puma.conf [conf] ####
> Puma configuration file.

#### redmine.conf [conf] ####
> Redmine configuration file.

#### webvirtmgr.conf [conf] ####
> Webvirtmgr configuration file.

#### dbarobin.conf [conf] ####
> The website of dbarobin.com configuration file.

### locale.gen [config] ###
> Generate locales use this config file. This config file exists in Debian 7.6. When updated this file, use 'locale-gen' command to re-generate locales.

Enjoy!

## About Author ##

温国兵

* Robin Wen
* Gmail：dbarobinwen@gmail.com
* CSDN：http://blog.csdn.net/justdb
* GitHub：https://github.com/dbarobin