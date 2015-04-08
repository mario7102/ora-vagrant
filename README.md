# ora-vagrant
## Introduction
This is a Vagrant Virtual Machine for ORA project

## Installation
The recommended way to get a working copy of this project is to clone the repository and run the virtual machine.

``` shell
git clone https://github.com/cocoonprojects/ora-vagrant.git
cd ora-vagrant
vagrant up
```
Then log into the machine and clone the O.R.A. repository
``` shell
vagrant ssh
cd /var/www
```
## Content
* Apache Web Server + PHP 5.5
* Composer
* MySql
* NodeJS
* Bower
