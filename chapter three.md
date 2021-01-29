
### Google App Engine

__App Engine__ Focuses on user Code and not infrastructure

__Paas__ Manages Network and Hardwa needed to run your code

Environments offered:

    1.0 Standard 
        Easy to deploy apps
        Offfers autosacle
        Free daily quota
        usaged based on pricing

Requirements for runing standard App Engine

    Specific to Java,Python,PHP and GO
    allows Sandbox 

    2.0 Flexible Environment:

        Build and deploy containerized apps with a CLick
        No sandbox constraints
        Can access App Engine Resources

### APIs Hide Details;

API Mamagement Tools:

    API Console
    RESTFul Interface

Cloud End Points:

    Helps you create and Maintain Cloud APIs
    Control Access and Validate Calls with JSON web tokens and Google API Keys
    Generate Client Libraries

__Apigee__ helps you __secure__ and __monetize__ APIs

### Developement in the Cloud

__IaaS__ 

    Monitoring: Proactive instrumentation

__Cloud Source repositories__ 

    Fully deatured Git repository hosted on Google GCP

Cloud Functions:

    Create single-purpose Functions that respond to events without a server or runtime

    Written in JavaScript

#### Deployment Manager:

    provides repeatable deployments
    Create a.yaml describing your environment and use deployment manager to create resources


### Proactive Instrumenting 

Stackdriver:

    Monitor 
    Log 
    Debug
    Error reporting 
    Trace

### Big Data and Machine Learning

Big data: (Fully mananged and Scalable)

    Cloud dataproc
        Easily migrate on-premises Hadoop jobs to Cloud
        save money on preemptive instances

        you can use Spark ML (MLlib)to run classification Algorithms

    Cloud dataflow
    BigQuery
    Cloud Pub/Sub
    Cloud datalab

#### CLoud DataFlow

Offers Managed data pipelines

Works for both batch and Streaming data

Fully automates any tasks


__Use Cases__:

    ETL (Extract Transform Load) pipelines to move, Filter, Enrich and shape data

    Data Analysis : Batch Computations / continuous computations using streaming



#### BigQuery

Fully managed Data WareHouse

provides near real-time interactive analysis of massive datasets using SQL snytax 2011

Run's on Google's High-performance Infrastructure

    Compute and storage are separated with a terabit network in between
    pay for storage and processing used
    Long-term storage discount

### Cloud Pub/Sub and Cloud Datalab

Scalable reliable messaging:

    support many-many asynchronous messaging
    app components make pull/push 
    include support for offline customers

### Google Cloud Machine Learning:

Learning Platform:

    Tensorflow
    Cloud ML
    ML APIs

Machine Learning API

    CLoud Visoin API:

        Analyse image with simple REST API
        logo dection, Label detection

    Gain insight from images
    Detect inapropriate Content
    Analyze sentiments
    Extract text

Cloud narural Language API:
    
    return text in realtime
    High Accuracy
    Access from any device
