## Google Cloud Storage

### Storage Options for GCP

    Cloud Storage
    Cloud SQL
    Cloud Spanner
    Cloud Data Store
    Google Big table

### Cloud Storage

Allows scaling 
simple administration

Cloud stores data with encryptions

both on transit and on rest, Data is encrypted

__Buckets__ are used to distributed your servers or storage systems in differemt data centers

Buckerts allow a user to create and cconfigure services in the cloud

Data can be transfered online and offline 

ACL - Access Control List, defines who has access to a certain operations of bucket

__scope__ defines who has access

__permission__ defines actions to be perfomred with the permissions

__lifer cycle__ management policiy for __versioning__ which allows quick modification of elements in a container


### Choosing between Cloud storage

1. Multiregional
2. Regional
3. Nearline (Access infriquently accessed data)
4. Coldline  (Data archiving, oinline backup, Disaster recovery)

### Data upload 

    Online Transfer (Self-managed, copies using commandline or Drag and Drop)
    Storage Transfer (Scheduled, managed batch transfer, )
    Transfer Appliance( Rackable appliance to securely ship your data)

### Other supported GCP services on storage:

    import and export tabels with BigQuery
    Objects storage,logs & data store backup with App Engine
    startuo scripts, images & General Objects storage with Compute Engine
    Import and Export tables with Cloud SQL
### Cloud Bigtable

Google's NoSQL big data database service

__Database Schema__ a relational db offering columns and rows for data input 

__Enforce Schema__ helps organizr big data for some application

__NOSQL Bigdata__ allows storage upto perabytes of data to terabytes of data 

Support high throughout 

### Managing Cloud Bigtable

    Accessed using HBase API
    Native Compatibility with big data & hadhoop Ecosystems

### Cloud Bigtable 

    Managed and Scalable Storage
    Data Encryption in-flight and at rest
    Control Access eith IAM
    Bigtable drives major applications such as Gmail, Google Analytics

### Access Paterns for Bigtable

    Application API 
    Streamig
    Batch Processing


### Cloud SQL and CLoud Spanner

__Relational db Services__  uses db schema to help your data be consistent and correct 

    Also performs transactions 

Provides   MYSQL  and PostgreSQLBeta db as a service

Automatic replicaiton

Managed Backups

vertical scaling (r/w)

Horizontal scaling (r)

Google Security

Accessed by other external services


__Cloud Spanner__ offers Horizontal scalable RDMNS

    Strong global Consistency
    Manage instance with high availability
    SQL queries
    Automatic replication

### Cloud DataStore

    Is a Horizontal SQL
    Free daily Quota
    Designed for Application backend
    Supports Transactions


## Containerization



### Kubernetes and Kubernetes Engine

##### Containers in the Cloud:

Easy scaling and deployments 

Kubernetes is an opern source ochestrator for containers for scaling and managing applications.

__kubectl__ allows you to control kubernetes engine

__CLuster__ set of master commands that control a system as a whole and set of nodes that run container

Create a complete cluster in cloud

    gcloud container clusters create k1

__Pod__ Smallest deployable unit in kubernetes

Run a container in POD:

    kubectl run 

__Deployment__ represent a group of replica of the same pod

See running pods in kubernetes

    kubectl get pods

Make your kubernetes visvible to the public,

    kubectl expose deployments nginx --port=80 --type=loadbalancer

Service groups:

    provide endpoint services for clients access outside public IP 

    allow easy management and stability

GEt setvice

    kubectl get services

Scale service

    kubectl scale nginix --replica=3

Auto scale based on CPU usage

    kubectl autoscale --min=10 --max=25 --cpu=80

    kubectl get replicasets -------> view replicas

    kubectl get pods -----------> get pods 

#### Hybrid and Multi-Cloud Computing 

___Modern Distributed Systems__ Allows a more agile approach to managing your compute

    Move only some compute workloads to the Cloud 
    Move at your own pace
    take advantage of Cloud's scalability and low cost
    add specialized services to your compute resources stack

### Anthos:

Googl's modern solution for hybrid and multi-cloud systems and service management

    Kubernetes and GKE on premise foundation
    On-premise and cloud environment stay in sync 
    provide a rich set of tools:
        Managing service on-premise and in the Cloud 
        Monitoring systems and services
        migrating applications from Vms into your clusters
        maintaining consistent policies across all clusters, whether on premise  or in the Cloud.

stack driver:

    Built-in Monitoring and logging solutions for Google Cloud

**Google Anthos** also manages __Microservices__ for easy anlysis where there are too many microservices
