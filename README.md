vagrant-debian-x64
==================

This is a simple Vagrant project to run a VM with [Debian](http://www.debian.org/).

Copyright 2014, [Gianpaolo Macario](http://gmacario.github.io/).

Prerequisites
-------------

* [Vagrant](http://www.vagrantup.com/) - tested with version 1.6.2
* One virtualization solution - tested with [VirtualBox](https://www.virtualbox.org/) 1.3.10
* One host OS supported by Vagrant - tested with [MS Windows 7 64-bit](http://windows.microsoft.com/)
* At least 4 GB RAM
* About 20 GB free disk space where the VM will run
* A fast Internet connection

Step-by-step instructions
-------------------------

Create the guest VM with the following command:

    $ vagrant up

Really, that's all folks!

You may then login to the guest VM with the following command

    $ vagrant ssh

If you uncommented `vb.gui = true` in `Vagrantfile`, you may also login through the console of the guest VM (default username/password: vagrant/vagrant).
