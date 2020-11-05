# clouds-compared

| | AZURE | AWS | GCP 
--- | --- | --- | --- 
**compute** | Azure VM | Elastic Compute Cloud (EC2) | Compute Engine 
**images** | VM (OS) image | Amazon Machine Image (AMI) | |
**compute billing** | - billed per minute<br/>- license included | - billed per hour <br/>- license included | | 
**storage** | Virtual disks in Azure blob storage | Virtual disks in EBS | 
**network** | Virtual networks | Networks in VPCs | 
**API endpoints** <br/> Single entryway that allows multiple APIs or microservices to act cohesively | API Management | API Gateway | Cloud Endpoints 
**Autoscaling** <br/> Scales resources (of a group) up or down based on usage and rules | VM Scale Sets | Auto-scaling group| Compute Engine Autoscaler
**Availability Zone (AZ)** <br/> Distinct locations (within regions) where resources are housed - designed to be isolated from failures in other AZs | Availability Zone| Availability Zone | Availability Zone
**Compute Instances** <br/> Scalable compute instances (servers) | Azure VM| Elastic Compute Cloud (EC2) | Compute Engine 
**Content Delivery Network (CDN)** <br/> Global network that delivers content based on the geographic locations of the user | Azure CDN| Cloudfront| Cloud CDN or CDN Interconnect
**Data Warehouse** <br/> Central repositories of integrated data from one or more disparate sources | SQL Data Warehouse| Redshift| BigQuery 
**Domain Name System (DNS)** <br/> Naming database in which internet domain names are located and translated into IP addresses | Azure DNS or Traffic Manager| Route 53| Cloud DNS 
**Identity and Access Management (IAM)** <br/> Manage access to cloud services and resources securely | Azure Role-Based ACL (RBAC) or Azure AD| Identity Access Management (IAM)| Cloud IAM
**Internet Gateway** <br/> VPC component that allows communication between instances in VPCs and the internet | | IGW| 
**Load Balancing** <br/> Pushes traffic (in a balanced way) across multiple targets in multiple AZs | Load Balancer or Application Gateway| ELB| Cloud Load Balancing 
**Managed Data Stream Processing Service** | Stream or Data Lake Analytics | Kinesis | Dataflow (processing) or Pub/Sub (ingest)
**Managed Kubernetes (K8s) Service** <br/> Allows you to run K8s without needing to install and operate your own K8s cluster | Azure Kubernetes Service (AKS)| Elastic Kubernetes Service (EKS)| Google Kubernetes Engine (GKE)
**Managed NoSQL Database Service** <br/> Distributed non-relational database service | Cosmos DB | DynamoDB | Cloud Firestone, Cloud Bigtable or Cloud Database
**Managed SQL Database Engine** <br/> High performance managed SQL engine that runs on a cloud's managed SQL service| | Aurora| Cloud Spanner
**Managed SQL Database Service** <br/> Distributed relational database service capable of running multiple SQL engines | SQL Database or Azure Database for MySQL| Relational Database Service| Cloud SQL
**Messaging Queue Service** <br/> Fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications | Azure Queue Storage or Service Bus | SQS Queues | Cloud Pub/Sub
**Network Address Translation (NAT)** <br/> Enable outbound internet traffic from instances in a private subnet | NAT Gateways| NAT Gateways| Cloud NAT
**Network Peering** <br/> A networking connection between two VPCs that enables the routing traffic between them using private IP addresses | Virtual Network Peering| VPC Peering Connections | VPC Network Peering 
**Network Routes/Routing** <br/> A set of rules that are used to determine where network traffic from subnets and/or gateways are directed | Azure Virtual Network Routing| Route Tables | Routes
**Object Storage** <br/> Scalable, highly available storage for objects | Blob Storage| S3  Buckets| Cloud Storage
**Pub/Sub Messaging** <br/> Fully managed pub/sub messaging service that enables you to decouple microservices, distributed systems, and serverless applications | Event Grid| SNS Topics| Cloud Pub/Sub
**Region** <br/> Worldwide locations where resources are hosted | Region| Region| Region
**Security Groups** <br/> Contains a list of security rules that allow or deny network traffic to resources | Network Security Group| Security Group| Compute Engine Firewall Rules 
**Serverless Container Service** <br/> Run containers without managing servers | Azure Container Instances (ACI)| Fargate| Cloud Run (+GKE)
**Serverless Functions** <br/> Event-driven, serverless computing service that runs code in response to events and automatically manages the computing resources required by that code | Azure Functions| Lambda Functions| Cloud Functions
**Serverless Orchestration** <br/> Task, processes, and workflow orchestration | Logic Apps| Step Functions
**Subnet** <br/> Logical subdivision of an IP network. Can be private or public | Subnet | Subnet| Subnet
**Third Party or Guest Access** <br/> Grant access to resources in your cloud account, another cloud account you own, or a third-party account | RBAC - Guests| Cross-account Roles| Cloud IAM - Service Account 
**Virtual Private Cloud (VPC)** <br/> A logically isolated section of the cloud where you can launch resources | Virtual Network (VNet)| Virtual Private Cloud (VPC)| Virtual Private Cloud (VPC)
**VPC Endpoints** <br/> Privately connects VPC to other cloud and endpoint services | Virtual Network Service Endpoint| VPC Endpoints | Private Services, Private Google Access and/or Shared VPC
**VPN Gateway** <br/> Private connection to VPCs | Azure VPN Gateway| Virtual Private Gateway | Cloud VPN