# devops-basic

This repository contains a collection of template scripts that can be used in DevOps projects. The scripts provided here are meant to serve as starting points or references for common tasks encountered in the DevOps domain. Feel free to adapt and modify these scripts to suit your specific needs.

## Table of Contents

- [Vagrant Scripts](#vagrant-scripts)
- [Bash Scripts](#bash-scripts)

## Vagrant Scripts

The `Vagrant/` directory contains scripts related to managing Vagrant environments. These scripts provide a starting point for setting up and provisioning development environments using Vagrant.

- `wordpress/`: Automated provisioning of Wordpress on Ubuntu box. As vagrant cannot create an additional file in the directory, I manually created the wordpress.conf, which is eqivalent to step 4 from https://ubuntu.com/tutorials/install-and-configure-wordpress#4-configure-apache-for-wordpress 
- `provision.sh`: A Bash script that is executed during the Vagrant provisioning process.

## Bash Scripts

The `Bash/` directory contains standalone Bash scripts that can be used for various DevOps-related tasks. These scripts are designed to provide examples and starting points for automating common tasks. I will mainly used them in conjuction with Vagrant, Terraform or Ansible.

- `script1.sh`: Description of script1.
- `script2.sh`: Description of script2.
- `script3.sh`: Description of script3.
- ...

## Acknowledgments

This repository is inspired by the all the super active contributors of the DevOps community. As this repo is the first ever in my life I view it with a lot of nostalgia and love.