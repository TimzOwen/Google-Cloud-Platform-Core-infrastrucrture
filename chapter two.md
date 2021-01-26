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


#### Cloud SQL and CLoud Spanner

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
