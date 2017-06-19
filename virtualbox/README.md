# Virtualbox Guest

Crude initial implementation to install VirtualBox guest additions.

Currently only targeting Ubuntu 14.04, probably works on newer versions.

```bash
export DRT_VIRTUALBOX_VER='5.1.22'
```

#To Do

* Check hash of download guest addition iso
* Do cleanup
* Enable ability to use [cache-url](https://github.com/openstack/diskimage-builder/tree/master/diskimage_builder/elements/cache-url) element.
