
### Introduction to Google Cloud 

#### For Data scientist check read on

[Google Big Data Course](https://www.coursera.org/learn/gcp-big-data-ml-fundamentals/home/welcome)

### GCP Services

    Compute 
    Storage
    Big data 
    Machine Learning 

### Cloud Computing

important CLoud traits:

    computing resources on demand and self service
    storage  and network you need
    Access resources from anywhere you want
    resources are elastic
    Measured service

## GCP regions and ZONEs

Zone --> deployment ares for Google cloud resources


Cloud also offers APIs intergrations from other open source providers

#### Security for GCP and Data 

Operational Security -->Intrusion detection & software and employees

internet communication --> Denial of service attack protection

Storage service-->Encryption at rest

User identitiy-->Central identity service U2F (attacker to systems and servers)

Service deployments-->Encryption of interservice communication

Hardware infrastructure--> premise security & secure boot stack from data loss



Quotas:
    prevent againest overuser of resoures

    Allocation quotas

    Rate quotas

Access management in the cloud

    workloads in GCP:
    
    uses Identity and Access Manager (IAM)

Interacting with GCP:

    APIs

    web-based Console

    SDK 

    commandline

    Mobile Apps

#### GCP REsource Hierachy

Grouped arccoding to the organization's structure

provide resources allocations and isolations

organizaition nde:
    
    The root node fro GCP resources

    File organization also affects user access and modification


#### Identitity and access Management

Allows adimins to allocate privilages to:

    Who can---> Group policy/ Google Account
    what can do ---> IAM
    Resources to operate on

Rights can be:
    view
    view/edit
    Manage all the entire resources
    editor

#### IAM Roles

Instance Admin Role:

    Listing VMs
    Reading and changing their configurations
    Strating and Stopping VMs

Custom Roles & Full previlage roles

Custom roles are only used at the project based or organization level only

service Accounts Control server-to-server interactions

    authenticate 

    provider server-to-server interactions

    control privilages used by resources

    identified by email addresses

#### Interacting with GCP platform

    Cloud platform Console --> web based admin console
    Cloud Shell and Cloud SDK --> Terminal based gsutil ,gcloud , Docker image
    Cloud console mobile app --
    REST-based API (Representations state Transfer paradigmn) 
        uses JSON 
        OAuth 2.0 for authentication and authorization
        Enables on GCP Console 
    
API explorer --> helps ypu write code

Libraries:

    Cloud Client Libraries

    Google API Cloud Libraries

### Deploying web apps 

LAMP (Linux, Apache, MySQL, PHP)



#### VPN in the Cloud

Connections via cloud 

#### Virtual Private Cloud (VPC)

Connecting to instances 

ALready configured subnets can are not affected by modifications   

#### Compute Engine

created from GCP console 

    or gcloud

    Run images on Linux or Windows Server

SSD allow qucik and fast task execution

Boot images: 

also the start up script

you can scale up or out of VMs

    use VMs for memory-and-compute-intensive applications
    Autoscaling fro resilence


#### VPC Network

provide security when providing services

#### Importance of VPC capabilities

you can control VPC and use it to root traffic within network 

have routing tables used for forwading traffic from one instance to another 

GCP automatically manages firewalls 

__VPC Peering__ : Establishes connections between 2 GCP Projets

__shared VPC__ uses __IAM__ to manage the communications between GCP

__CLoud Load balacing__ fully distributed software-defined to manage servies for all your traffic.

__HTTPS Load balacing__ allow scalling without any user notification 

__global SSL proxy load balancer__  for none http requests 

__Internal Load balancer__ rediret traffic between your internal projects not going to Google network

**Cloud DNS** managed cloud service running on same infrastructure as google 
    
    it is programmable and a user can manage multiple zones by usinf GCP console /API / CI

Edge caches accelerate content delivery and can be managed from th Google Cloud CDN

# GCP interconnections

    VPN --> secure multi-Gbps connections over VPN traffic
    Direct Peering -->Private connection between you and the Google cloud and hybrid cloud & workloads
    carrier Peering -->Connection through the largest partner network of service providers
    Dedicated Interconnect-> connect 10 N X 10G transport circuit for private 
                            cloud traffic to Google at Google  PoPs    
