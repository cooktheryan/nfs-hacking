# nfs-hacking
The Vagrant file will deploy two kind clusters, deploy nfs, connect the two kind clusters to the nfs server as storageclasses, and clone the KCP repo into /root/kcp.

To access the clusters `sudo su -` as items have been created as the root user.

## Requirements
The following must be available on a system based on the requirements of the Vagrantfile.
* libvirt
* vagrant

## Launching
To launch the environment.
```
vagrant up
```

To access the environment
```
vagrant ssh
```
