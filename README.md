# Config files-By Robin Wen #

## Project Summary ##

> Config files about linux and service on it. This scripts collected via work. You may get massive useful skills throgh the script.

## Version Information ##
> Majority of scripts pass-test in RHEL 6.1, part of scripts pass-test in Debian 7.6/Ubuntu 14.04. I will give clear indication of this scripts in the **Scripts and Dirs Summary**.

## Change Log ##

**22014-06-11**
> Documentation version is **1.0**, Documentation name is **Config files-By Robin Wen**, Comment is **All of Scripts pass-test**, By Robin。

**2014-11-17**
> Documentation version is **2.0**, Documentation name is **Config files-By Robin Wen**, Comment is **All of Scripts pass-test, and add the summary of scripts**, By Robin。

**2014-11-18**
> Documentation version is **2.1**, Documentation name is **Config files-By Robin Wen**, Comment is **Add the nginx configuration file, and add the desc of this file**, By Robin。

**2014-11-20**
> Documentation version is **2.2**, Documentation name is **Config files-By Robin Wen**, Comment is **Add the locale configuration file, and add the desc of this file**, By Robin。

**2014-11-24**
> Documentation version is **2.3**, Documentation name is **Config files-By Robin Wen**, Comment is **Add MySQL configuration file**, By Robin。

**2014-12-12**
> Documentation version is **2.4**, Documentation name is **Config files-By Robin Wen**, Comment is **Add Tomcat configuration file, server.xml**, By Robin。

**2014-12-12**
> Documentation version is **2.5**, Documentation name is **Config files-By Robin Wen**, Comment is **Add mongodb configuration file.**, By Robin。

**2011-01-13**
> Documentation version is **2.5.1**, Documentation name is **Config files-By Robin Wen**, Comment is **Add config file of sublime, bash profile, vimrc, config file of ssh, etc**, By Robin。

## Lists of File ##

* .bash_profile
* .vimrc
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
* sublime-text-3 [d]
	*  Default-OSX.sublime-keymap [conf]
	*  MarkdownPreview.sublime-settings [conf]
	*  Package Control.sublime-settings [conf]
	*  Preferences.sublime-settings [conf]
	*  sublime_text_3_packages [file]
* locale.gen [config]
* ssh_config [config]
* my_5.1.cnf [config]
* my_mac_os_x.cnf [config]
* my_multi.cnf [config]
* tomcat_server.xml [xml]
* mongod.conf [config]

## Scripts and Dirs Summary ##

### .bash_profile ###
> Custom bash file. Use this configuration file in Mac OSX 10.9.5

### .vimrc ###
> Vim  configuration file. Use this configuration file in Mac OSX 10.9.5. Use vgod's vimrc. Fork this on on GITHUB  https://github.com/vgod/vimrc

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

### sublime-text-3 [d] ###
> Configuration file directory of Sublime Text 3.

#### Default-OSX.sublime-keymap [conf] ####
> Key binding file of Sublime Text 3.

####  MarkdownPreview.sublime-settings [conf] ####
> MarkdownPreview custom settins of Sublime Text 3.

#### Package Control.sublime-settings [conf] ####
> Custom package control settings of Sublime Text 3.

#### Preferences.sublime-settings [conf] ####
> Custom preferences of Sublime Text 3.

#### sublime_text_3_packages [file] ####
> Custom plugins of  Sublime Text 3.

### locale.gen [config] ###
> Generate locales use this config file. This config file exists in Debian 7.6. When updated this file, use 'locale-gen' command to re-generate locales.

### ssh_config [config] ###
>  SSH configuration file. Use this in  Mac OSX 10.9.5.

### my_5.1.cnf [config] ###
> MySQL 5.1 configuration file on linux.

### my_mac_os_x.cnf [config] ###
> MySQL 5.6 configration file on Mac OS X.

### my_multi.cnf [config] ###
> Multiple MySQL configuration file.

### tomcat_server.xml [xml] ###
> Tomcat server.xml. Resolve the "Tomcat : tomcat Connection refused" error.

### mongod.conf [config] ###
> MongoDB configuration file.

Enjoy!

## About Author ##

温国兵

* Robin Wen
* Gmail：dbarobinwen@gmail.com
* Blog：http://dbarobin.com
* GitHub：https://github.com/dbarobin
