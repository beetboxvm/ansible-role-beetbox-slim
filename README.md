# Ansible Role: Beetbox Slim

[![CircleCI](https://circleci.com/gh/beetboxvm/ansible-role-beetbox-slim.svg?style=svg)](https://circleci.com/gh/beetboxvm/ansible-role-beetbox-slim)

An Ansible role that creates a Slim project on beetbox.

## Requirements

This role is specifically developed as an extension to beetbox -- https://github.com/beetboxvm/beetbox

## Role Variables

Available variables are listed below, along with default values:

Create new Slim project.

    slim_create_new: no
    
Slim version.    
    
    slim_verison: ""
    
Add example Slim app.    
    
    slim_add_example: no
    
Add Slim .htaccess file.
    
    slim_add_htaccess: no


# beetbox

https://github.com/beetboxvm/beetbox

## Requirements

* [Vagrant](https://www.vagrantup.com/) >= 1.8
* [Virtualbox](https://www.virtualbox.org/)
* [Vagrant Hostsupdater](https://github.com/cogitatio/vagrant-hostsupdater)
* [Vagrant Auto-network](https://github.com/oscar-stack/vagrant-auto_network)

## Quickstart

  1. Open terminal (or [git bash](https://msysgit.github.io/) for windows users) and run the following commands --

  ```
  git clone https://github.com/beetboxvm/ansible-role-beetbox-slim.git slim && cd $_
  vagrant up
  ```

  2. Go to http://slim.local/

  ```
  username: admin
  password: admin
  ```

## License

MIT
