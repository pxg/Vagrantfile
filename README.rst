Description
===========

A template for provisioning any new [Vagrant](http://vagrantup.com/) project
using Ansible, it will install a core set of useful packages and have the server
ready for uwsgi app development.

To Run
======

 - install vagrant
 - copy your public key to `ansible/id_rsa.pub`
 - `vagrant up`
 - NOTE: the NFS will prompt for your password
 - `vagrant ssh` then on the box `sudo nginx start`. Nginx will now be running on 127.0.0.1:8080