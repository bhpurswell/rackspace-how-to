---
permalink: rackspace-private-cloud-spheres-of-support/
node_id: 4244
title: Rackspace Private Cloud Spheres of Support
type: article
created_date: '2014-09-19'
created_by: Karin Levenstein
last_modified_date: '2016-01-16'
last_modified_by: Kelly Holcomb
product: Rackspace Private Cloud Powered by OpenStack
product_url: rpc-openstack
---

### Previous section
[Getting Started with Rackspace Private Cloud - OpenStack](/how-to/rpc-openstack)

Rackspace Private Cloud is the Rackspace architecture for and support of a production-ready, scalable, OpenStack based private cloud. To ensure ***Fanatical Support***<sup>&reg;</sup>, Rackspace provides support for specific server configurations and OpenStack projects in Rackspace Private Cloud v9 and v10.

This document describes what is and is not supported in Rackspace Private Cloud v9 and v10.

## Operating systems

Rackspace Private Cloud v9 and v10 support Ubuntu 14.04 LTS (Trusty Tahr) 64-bit server edition, with with Linux kernel version 3.13.0-34-generic or later. Only OpenStack API clients are supported.

Rackspace does not support the contents of user VMs and will not manage the VMs after they are running. We do not support clients on Windows.

## Web and database servers

Rackspace Private Cloud uses Apache for its web server, and MariaDB + Galera for its database server. No other web and database servers are supported

## Intended capabilities of Rackspace Private Cloud

Feature	| Description	| Rackspace data center	| Customer data center
--- | --- | --- | ---
**Monitoring** | Hardware, Compute/Disk/Memory, OpenStack Services | Yes | OpenStack services </br></br> CPU/Disk/Memory Utilization only
**Manual Patching Processes** |	Host OS |	Yes |	Yes
**Multi-Region Support** | Hosting components over multiple data centers	| Yes |	No
**OpenStack Endpoint SSL (Ingress)** |	Encryption of all API calls	| Yes - with SSL termination at a physical load balancer |	Yes - with SSL termination at a physical load balancer
**Encryption of all management traffic** | Encrypting management traffic in addition to the API call encryption |	No	| No
**Disaster Recovery** |	Recovery from data center failures or "Acts of God"	| No | No
**Deploy from mirror** | Deploy RPC from an off-line local repository | Not applicable |	No
**Customer images** | 	Reference glance images provided	| CentOS 6 and 7 </br></br> Ubuntu 12.04 LTS, 14.04 LTS, 14.10 </br></br> Windows 2012R2 Datacenter </br></br>  Red Hat Enterprise Linux (Contact Red Hat for availability of images and licensing) | CentOS 6 and 7 </br></br> Ubuntu 12.04 LTS, 14.04 LTS, 14.10 </br></br> Red Hat Enterprise Linux (Contact Red Hat for availability of images and licensing)

## OpenStack features

| | Installation |	Configuration	| Troubleshooting	| Monitoring | Patching |
| --- | --- | --- | --- | --- | --- |
| **Nova Compute** |	Yes |	Yes |	Yes	| Yes |	Yes |
| **Glance Image Service** |	Yes |	Yes |	Yes |	Yes |	Yes |
| **Keystone Identity Service** |	Yes |	Yes |	Yes |	Yes |	Yes |
| **Swift Object Store** |	v10 only |	v10 only |	v10 only |	v10 only |	v10 only |
| **Cinder Block Storage** | 	Yes |	Yes |	Yes |	Yes |	Yes |
| **Neutron Networking** |	Yes |	Yes |	Yes |	Yes |	Yes |
| **nova-network** |	No |	No |	No |	No |	No |
| **Horizon Dashboard** |	Yes |	Yes |	Yes |	Yes |	Yes |
| **Ceilometer Telemetry** |	No |	No |	No |	No |	No |
| **Heat Orchestration** |	Yes |	Yes |	Yes |	Yes |	Yes |


## Next section

[Private Cloud Tech
Resources](/how-to/private-cloud-tech-resources)
