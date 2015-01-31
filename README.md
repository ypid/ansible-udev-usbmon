# Ansible udev usbmon

[![Build Status](https://travis-ci.org/ypid/ansible-udev-usbmon.svg?branch=master)](https://travis-ci.org/ypid/ansible-udev-usbmon)

[udev-usbmon](https://galaxy.ansible.com/list#/roles/2758) is an [ansible](http://www.ansible.com) role which:

* Adds a udev rule for changing the permissions of usbmon devices to allow anyone who is in the specified group to use usbmon.

See http://superuser.com/a/861052.

## Default variables

```yaml
udev_usbmon_group: "usbmon"
udev_usbmon_permissions: "0640"
```

## License
AGPLv3
