# Cloud technologies 
Simple breakdown of core cloud technologies and their corollary in other clouds. 


|Cloud Service        | AWS           | Azure                          | GCP                           |
|---------------------|---------------|--------------------------------|-------------------------------|
|Object Storage       | S3            | Blob Storage                   | Cloud Storage                 |
|Virtual Machine       | EC2           | Virual Machine                 | Compute Engine                |
|SQL Database         | RDS           | Azure SQL Database<sup>1</sup> | Cloud SQL                     |
|Serverless Functions | Lambda        | Function App                   | Cloud Functions               |
|NoSQL                | Dynamo DB     | Cosmos DB                      | Cloud Datastore or Firestore  |
|Managed App          | Beanstalk     | Web App                        | App Engine                    |
|Hard Disk            | EBS           | Disk Storage                   | Persistent Disk               |
|Cloud Permissions    | IAM           | IAM (Active Directory)         | IAM                           |
|Container            | ECS           | Container Instances<sup>2</sup>| Cloud Run                     |
|Messaging Queue      | SQS           | Service Bus                    | Cloud Pub/Sub                 |
|Pub/Sub              | SNS           | Pub Sub                        | Cloud Pub/Sub                 |
|Kubernetes           | EKS           | AKS                            | GKE                           |
|Machine Image        | AMI           | (No Named Service)             | (No Named Service)            |
|Firewalls/IP routing | Security Group| Security Group or Netwworking  | Networking/Firewall rules     |
- (No Named Service)
  - It can be done with similar steps but there is not dedicated named service for it

1. Azure Database for PostgreSQL is desired for most curricula. Azure SQL database is managed service with an API different than a normal Postgres Driver.
2. Container instances is not free tier. A free tier version would be container App. Little bit trickier to set up however.