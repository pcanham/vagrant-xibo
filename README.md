# Intro
This is a quick way of spinning up a xibo-cms instances for playing around with the new digital display boards.

[Currently Ansible can be run from any machine with Python 2.6 or 2.7 installed (Windows isn’t supported for the control machine).](http://docs.ansible.com/intro_installation.html#control-machine-requirements)


## Technology Stack for provisioning

- [Vagrant](http://www.vagrantup.com/)
- [CentOS 7](https://www.centos.org/)
- [Ansible](http://www.ansible.com/home)
- [Apache httpd](http://httpd.apache.org/)


### required applications/plugins
- [Oracle Virtualbox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](http://www.vagrantup.com/downloads.html)

### Start up two puppet masters running the different technology stacks
```
vagrant up --provision
```
