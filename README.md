# Ansible Role: Nginx

## Description
This Ansible role installs and starts the Nginx web server on Ubuntu systems.

## Requirements
- Ubuntu 20.04 or later
- Ansible 2.9+

## Role Variables
None (default configuration)

## Usage
```yaml
- hosts: web
  become: yes
  roles:
    - nginx
