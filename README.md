# Config files

Config files by Robin. This scripts collected via learning and work. You may get massive useful skills through the script.

## Version

Majority of scripts pass-test in RHEL 6.1, part of scripts pass-test in Debian 7.6/Ubuntu 14.04. I will give clear indication of this scripts in the lists of file.

## Installation

Clone or download zip.

## Usage

1. Clone or download zip.
2. Unzip and reuse configuration files.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Lists of File

* .bash_profile, Custom bash file. Use this configuration file in Mac OS X 10.9.5
* .vimrc, Vim  configuration file. Use this configuration file in Mac OS X 10.9.5. Use vgod's vimrc. Fork this on GitHub, https://github.com/vgod/vimrc
* 90-disk.rules [net], Storage binding via iscsi. Use this script in RHEL 6.1.
* cluster.conf [ha], Cluster conf through ocfs2. Use this script in RHEL 6.1.
* local_iso.repo [yum], Use local rhel iso to config local yum source. Use this script in RHEL 6.1.
* rc.local [config], Local linux config file. Define ntp, mount dir and restart httpd. Use this script in RHEL 6.1.
* nginx [d], Nginx config file. Use this script in RHEL 6.5 and Ubuntu 12.04.
	* api.dbarobin.conf [conf], Api configuration file of dbarobin.com.
	* default.conf [conf], Nginx default configuration file. Nginx installed via apt-get.
	* default.conf.bak [conf], Backup of nginx default configuration file. Nginx installed via apt-get.
	* example_ssl.conf.bak [conf], Nginx example ssl configuration file. Nginx installed via apt-get.
	* nginx.conf [conf], Nginx default configuration file. Nginx installed via source.
	* pma.conf [conf], Pma configuration file.
	* pma.dbarobin.conf [conf], Pma configuration file of dbarobin.com.
	* puma.conf [conf],  Puma configuration file.
	* redmine.conf [conf], Redmine configuration file.
	* webvirtmgr.conf [conf], Webvirtmgr configuration file.
	* dbarobin.conf [conf], The website of dbarobin.com configuration file.
* sublime-text-3 [d], Configuration file directory of Sublime Text 3.
	*  Default-OSX.sublime-keymap [conf], Key binding file of Sublime Text 3.
	*  MarkdownPreview.sublime-settings [conf], MarkdownPreview custom settings of Sublime Text 3
	*  Package Control.sublime-settings [conf], Custom package control settings of Sublime Text 3.
	*  Preferences.sublime-settings [conf], Custom preferences of Sublime Text 3.
	*  sublime_text_3_packages [file], Custom plugins of  Sublime Text 3.
* locale.gen [config], Generate locales use this config file. This config file exists in Debian 7.6. When updated this file, use 'locale-gen' command to re-generate locales.
* ssh_config [config], SSH configuration file. Use this in  Mac OS X 10.9.5.
* my_5.1.cnf [config], MySQL 5.1 configuration file on linux.
* my_mac_os_x.cnf [config], MySQL 5.6 configuration file on Mac OS X.
* my_multi.cnf [config], Multiple MySQL configuration file.
* my_multi_mysql_osx.cnf [config], Multiple MySQL configuration file. Update at 11:39:27 2015/01/14.
* tomcat_server.xml [xml], Tomcat server.xml. Resolve the "Tomcat : tomcat Connection refused" error.
* mongod.conf [config], MongoDB configuration file.

## History

* 2014-06-11, All of Scripts pass-test
* 2014-11-17, All of Scripts pass-test, and add the summary of scripts
* 2014-11-18, Add the nginx configuration file, and add the desc of this file
* 2014-11-20, Add the locale configuration file, and add the desc of this file
* 2014-11-24, Add MySQL configuration file
* 2014-12-12, Add Tomcat configuration file, server.xml
* 2014-12-12, Add mongodb configuration file
* 2011-01-13, Add config file of sublime, bash profile, vimrc, config file of ssh, etc
* 2011-01-14, Add multiple mysql configuration file in OS X

## Credits

* [vgod's vimrc](https://github.com/vgod/vimrc)

## Contact

blockxyz@gmail.com

## License

GPL-2.0.

