# teuthology-neptune

Run teutology (ceph upstream integration tests) in generic fashion indipendent of any backends ( Libvirt, openstack, bare-metal).

# Motivation:

One developer could setup VMs via terraform-libvirt, define the cluster ceph via
https://github.com/MalloZup/ceph-open-terrarium

Once the cluster is done, it would be nice run `teutology` on libvirt, or via other backends.

Teuthology-neptune want to improve the developer experience  for setting up cluster and so on.

This projet aims to fullfill the missing feature/gap that is present at moment teuthology ( hardcoded to specific openstack or lab backends).

# Important:

At moment it is just experimental, feel free to join the efforts if you wish :)
