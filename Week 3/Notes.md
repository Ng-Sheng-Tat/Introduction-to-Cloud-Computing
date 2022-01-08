## Week 3

Anatomy of cloud security
1. Zone
2. Subnet: allows users to deploy enterprise applications using the same multi-tier concepts used in on-premises environemtns
3. Access Control Lists (ACL) serve as subnet-level firewall
4. Security Groups provide security for Virtual Instances.
---
Cloud infrastructure consists of data centers, storage, networking components, and compute resources.

Virtualization is the process of creating a software-based version of physical resources, made possible through the use of hypervisors.

A few different types of Virtual Machines can be provisioned on the cloud. These include:

Shared or Public Cloud VMs that are provider-managed, multi-tenant deployments that can be provisioned on-demand with predefined sizes

Transient or Spot VMs that take advantage of unused capacity in a cloud data center

Reserved VMs that allow you to reserve capacity and guarantee resources for future deployments

Dedicated hosts that offer single-tenant isolation

Bare metal servers are single-tenant physical servers that are dedicated to a single customer. Bare metal servers fulfill the demanding needs of high-performance computing (HPC) and data intense applications and are ideal for applications that have a high degree of security or compliance requirements.

Networking capabilities in the cloud are delivered as a service rather than in the form of rack-mounted devices. Cloud resources, such as VMs (or VSIs), storage, network connectivity, and load balancers, are deployed into subnets within Virtual Private Clouds (VPCs). Using private and public subnets allows users to deploy multi-tier enterprise applications securely. Load balancers distribute the traffic and allow applications to be responsive.

Containers are an executable unit of software in which application code is packaged, along with its libraries and dependencies, in common ways so that it can be run anywhere—desktops, traditional IT, or the cloud. Containers are lighter weight and consume fewer resources than Virtual Machines - helping streamline the development and deployment of cloud native applications.
---
**Storage Method**
1. Direct Attached
  - ephemeral (temporary)
  - not shared
  - non-resilient


2. File Storage
  - slower
  - low-cost
  - attach to multiple servers
  - ideal for storing hierarchical data
  - attached directly to a compute node to store data
  - less expensive
  - more resilient to failure
  - less disk management & maintenance for user
  - provision large amount of storage
  - offers encryption
  - workloads include departmental file share, 'landing zone' for incoming files, repository of files, low cost database storage

3. Block Storage
  - for database storage purpose
  - persistence
  - input output runs faster
  - IOPS input-output operations per seconds
  - **Snapshot** is a point in time image of the storage. It is fast to create, don't require downtime, record only changes to data, cannot recover individual files
  - files are broken into chunks or blocks of data
  - blocks are stored separately under a unique address
  - it must be attached to a computer node before it can be ultilized
  - mounted from remote storage appliances
  - extremely resilient to failure
  - data is more secure
  - signals move at the speed of light
  - higher price-point
  - perfect for workloads that need low-latency
  - consistent high speed
  - databases and mail servers
  - not suitable for shared storage between multiple servers
  - check out differences between file and block storage

4. Object Storage
  - least expensive (Gb us cent per month)
  - most commonly used for large unstructured data
  - slowest in speed and infinite in size
  - without connecting to particular compute node to use it, it uses an API via input and output
  - use metadata (data about the data) for data accessing
  - resilient and availablity is high
  - standard/archived/cold tiers with automatic archiving speed
---
Summary
Cloud storage is available in four main types–Direct Attached, File, Block, and Object Storage. These storage types differ in how they can be accessed, the capacity they offer, how much they cost, the types of data they are best suited to store, and their read-write speed.

Direct Attached (or Local) Storage is storage that is presented directly to a cloud-based server and is effectively either within the host server chassis or within the same rack.

File Storage is typically presented to compute nodes as a Network File System (NFS), which means that the storage is connected to compute nodes over a standard ethernet network.

Block Storage is presented to compute nodes using high-speed fiber connections, typically provisioned in volumes, which are mounted onto a compute node.  

Object Storage is accessed via an API and doesn’t need an underlying compute node. Object Storage offers infinite capacity as you can keep adding files to it and just pay for what you use. Compared to the other storage types, object storage is slowest in terms of read and write speeds.

A Content Delivery Network (CDN) is a distributed server network that accelerates internet content delivery by delivering temporarily stored or cached copies of website or media content to users based on their geographic location.
