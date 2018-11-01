# teuthology-neptune

Run teutology (ceph upstream integration tests) in generic fashion indipendent of any backends ( Libvirt, openstack, bare-metal).

# Motivation:

One developer could setup VMs via terraform-libvirt, define the cluster ceph via
https://github.com/MalloZup/ceph-open-terrarium

Once the cluster is done, it would be nice run `teutology` on libvirt. 

This projet aims to fullfill the missing feature/gap.
