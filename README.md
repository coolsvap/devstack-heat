devstack-heat
=============
Devstack and Heat localrc

Prerequisites:
--------------
- DevStack setup requires to have 1 VM/ BM machine with internet connectivity.
- Setup a fresh supported Linux installation. (Ubuntu/Fedora/CentOs)
- Install Git

Steps
-----
Clone devstack
```
$git clone https://github.com/openstack-dev/devstack.git
```

Clone devstack-heat
```
$git clone https://github.com/svashu/devstack-heat.git
```

Copy localrc from devstack-heat to devstack
```
$ cp devstack-heat/localrc devstack

```

Modify the devstack/localrc for IP and password modifications

Deploy your Devstack

```
$cd devstack && ./stack.sh
```
