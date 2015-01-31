## udev-usbmon

[![Travis CI](http://img.shields.io/travis/ypid/ansible-udev-usbmon.svg?style=flat)](http://travis-ci.org/ypid/ansible-udev-usbmon)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-ypid.udev-usbmon-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/2758) [![Platforms](http://img.shields.io/badge/platforms-debian%20/%20ubuntu-lightgrey.svg?style=flat)](#)

Adds a udev rule for changing the permissions of usbmon devices to allow anyone who is in the specified group to use usbmon.

See http://superuser.com/a/861052.

### Installation

This role requires at least Ansible `v1.3`. To install it, run:

    ansible-galaxy install ypid.udev-usbmon



### Role variables

List of default variables available in the inventory:

    ---
    
    udev_usbmon_group: "usbmon"
    udev_usbmon_permissions: "0640"




### Authors and license

`udev-usbmon` role was written by:

- [Robin Schneider](https://github.com/ypid) | [e-mail](mailto:ypid@riseup.net)
License: [AGPLv3](https://tldrlegal.com/license/gnu-affero-general-public-license-v3-%28agpl-3.0%29)

***

README generated by [Ansigenome](https://github.com/nickjj/ansigenome/).
