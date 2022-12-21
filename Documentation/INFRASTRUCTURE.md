
# Infrastructure :

Amazon Web Services (AWS) is the world’s most comprehensive and broadly adopted cloud platform, offering over 200 fully featured services from data centers globally. Millions of customers—including the fastest-growing startups, largest enterprises, and leading government agencies—are using AWS to lower costs, become more agile, and innovate faster.

## In this Project i have used 3 services from AWS: 

- **RDS** : Relational Database Service.
- **EB** : Elastic Beanstalk.
- **S3** : Scalable Storage in the Cloud.


### RDS:

 - Amazon RDS is a relational database service that manages common database administration tasks, resizes automatically, and is cost-friendly. i have used Relational DATABASE Service with Postgres Engine with following properitres: 
    - **DB instace identifier** : databse-1.
    - **Engine** : PostgreSQL.
    - **Region & AZ** : us-east-1b
    - **Size** : db.t3.micro
    - **Status** : Available ✅

### S3:
-  Amazon S3 is an object storage service that stores data as objects within buckets. An object is a file and any metadata that describes the file. A bucket is a container for objects. And we have used it to make static website for our clint side. 
    - **Buckets Name**: mohsen-udagram
    - **AWS REGION** : US East (N.Virginia) us-east-1
    - **Access** : Public

## EB:
- Elastic Beanstalk (EB) is a fairly straightforward way of setting up scalable applications. It uses Amazon Elastic Compute Cloud (EC2) instances, Amazon Simple Storage Service (S3) buckets, and load balancers to manage your application architecture for US.
   - **Application Name** : udagram-api
   - **Environment Name** : udagram-api-dev
   - **Health** : ok ✅  
   - **Platform State** : Supported ✅
   