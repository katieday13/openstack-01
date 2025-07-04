# Turn a disorganized openstack on Debian tutorial into Ansible Playbooks

[The inspiration](https://computingforgeeks.com/how-to-install-openstack-on-debian/)

## Usage

* `sudo apt-get install -y $(< packages.debian)`
* `vagrant up`

## Decisions

* Use Vagrant with vagrant-libvirt for test box
* Start with openstack command and work backwards on dependencies
* Capture libvirt dependencies
  * libvirt-dev

