## Domain 3: Cloud Technology and Services (34% of scored content)

![AWS Cloud Practitioner Domains](https://github.com/emiliedionisio/aws-cloud-practitioner-C02/blob/main/3-cloudtech.png)

## Networking:

#### What is a VPC in AWS, and why is it important?

A Virtual Private Cloud is a virtual network dedicated to your AWS account. It's logically isolated from other virtual networks in the cloud. It's important because you can specify an IP range for the VPC, add subnets, gateways, and associate security groups.

#### What is a subnet, and how is it used in a VPC?

A subnet is a range of IP addresses in your VPC. It's used in a VPC by launching your EC2 instance into your subnet. From there you can connect a subnet to the internet, other VPC's, data centers, and route traffic from your subnets using route tables.

#### What is an Internet Gateway, and what role does it play in a VPC?
An internet gateway is a horizontally scaled, redundant, and highly available VPC component that allows communication between your VPC and the internet.

#### What is a NAT Gateway, and why would you use it in a VPC?

A NAT gateway is a Network Address Translation service. You would use it so that instances in a private subnet can connect to services outside of your VPC, but external services can't initiate connection with the instances.

#### What is a Route Table, and how does it function in a VPC?

A route table contains a set of rules, called routes, that determine where network traffic from your subnet or gateway is directed.

#### What is a VPC Peering Connection, and what are its use cases?

A VPC Peering connection is a network connection between two VPC's that enables you to route traffic between them using private IP addresses. Its use cases are for when you want instances to communicate in private between each other.

#### What is a Security Group, and how does it enhance security in a VPC?

A security group controls the traffic that's allowed to reach and leave the resources that it's associated with. The security group acts as a virtual firewall. The only traffic that reaches your instance is the traffic allowed by the security group.

#### What is a Network ACL (Access Control List), and how does it differ from a Security Group?

A Network ACL is made up of rules that either allow or deny access to a computer environment. It differs from a security group because security groups controls at the instance level, where ACL's control at the VPC subnet level.

#### How do you use Network ACLs to enhance security within a VPC?

You use ACL's to enhance security within a VPC to control network acess at subnet level. It's stateless so it doesn't save any previously sent information.

#### What is an Elastic IP Address, and how is it used in a VPC?

An Elastic IP address is a static, public IPv4 address designed for the dynamic nature of cloud computing. It's used to mask the failure of an instance.

#### What is a Virtual Private Gateway, and how does it function in a VPC?

A virtual private gateway is a logical, fully redundant distributed edge routing function that sits at the edge of your VPC. It functions as the VPN endpoint on the Amazon side of your connections that can be attached to a VPC.

### What is Amazon Route 53, and what are its primary functions?

Amazon Route 53 allows you to create and manage your public DNS records. Its primary functions are to register domain names, route internet traffic to the resources for your domain, and to check the health of your resources.

#### What is the purpose of DNS in the context of Route 53?

The purpose of DNS in the context of Route 53 is that it searches the DNS zone for a websites' IP address and returns it to the DNS resolver.

#### How does Route 53 provide high availability and reliability for DNS queries?

Route 53 is designed to automatically answer queries from the optimal location depending on network conditions. 

#### What is geolocation routing in Route 53, and what are its benefits?

Geolocation routing lets you balance the load on your resources by directing requests to specific endpoints based on the grographic location from which the requests originates. It offers low query latency for your end users.

#### What is Amazon CloudFront, and what are its primary functions?

Amazon CloudFront is a Content Delivery Network service that securely delivers information to customers globally with low latency and high transfer speeds. Its primary functions are that it automatically maps network conditions and intelligently routes your user's traffic to the most performant ege location to serve up chached or dynamic content.

#### What are the benefits of using Amazon CloudFront?

The benefits of Amazon CloudFront are that users get lower latency and higher data transfer rates.

#### What is AWS Global Accelerator, and what is its purpose?

AWS Global Accelerator is a service in which you create accelerators to improve the performance of your applications for local and global users. Its purpose is to reduce latency and jitter globally for applications that require custom logic to map users to specific endpoints.

#### What is the difference between Amazon CloudFront and AWS Global Accelerator?

The difference between is that CloudFront uses edge locations to cache content while Global Accelerator uses edge locations to find an optimal pathway to the nearest regional endpoint. CloudFront is designed to handle HTTP and Global Accelerator is for both HTTP, TCP, and UDP.

#### What is edge location in the context of Amazon CloudFront?

Edge locations are a network of data centers. When a user requests content with CloudFront, the request is routed to the edge location that provides the lowest latency.

#### What is AWS Direct Connect, and what are its primary benefits?

AWS Direct Connect is a networking service that provides an alternative to using the internet to connect to AWS. Its benefits are to reduce network costs, increase bandwidth throughput, and provide a more consistent network experience than internet-bases connections.

#### What are common use cases for AWS Direct Connect?

Common use cases for AWS Direct Connect to access service provider services hosted in AWS.

#### What is AWS VPN, and how does it differ from AWS Direct Connect?

An AWS VPN is a managed client-based VPN service that enables you to securely access your AWS resources or your on-premise network. AWS Direct Connect bypasses the public internet and establishes a secure, dedicated connection from your infrastructure into AWS.

#### What types of AWS VPN connections are available?

The types of AWS VPN connections are Site-to-Site VPN and Client VPN.

#### What is a Transit Gateway, and how does it benefit network connectivity?

AWS Transit Gateway helps you design and implement networks at scale by acting as a cloud router. As your network grows, managing incremental connections can slow you down. AWS Transit Gateway connects VPC's and on-premise networks through a central hub.

## Storage: 

#### What is object storage typically used for in cloud computing?

Object storage is best used for large amounts of unstructured data.

#### How does Amazon S3 handle durability and availability for object storage?

S# stores data redundantly across a minimum of 3 availability zones by default, providing built-in resilience against widespread disaster.

#### What are some typical use cases for Amazon S3?

Some typical use cases for S3 are backup/restore, disaster recovery, archive, data lakes for analytics, and hybrid cloud storage.

#### What is the main difference between Amazon S3 Standard and Amazon S3 Standard-IA storage classes?

The main different between S3 and S3-IA is that S3-IA is for data accessed less frequently, but requires rapid access when needed. Price is also a difference. It's lower per GB storage and retrieval than S3.

#### What is the Amazon S3 Glacier storage class used for?

S3 Glacier storage is used for backup and archive data that's rarely accessed and low cost.

#### How does Amazon S3 Intelligent-Tiering work, and what are its benefits?

S3 IT works by automatically storing objects in three access tiers. Its benefits are its cost-effective, and there's no retrieval charges.

#### Explain the use case for Amazon S3 One Zone-IA.

S3 One-Zone IA is for data that's accessed less frequently, but requires rapid access when needed.

#### What is Amazon Elastic Block Store (Amazon EBS) and what are its primary use cases?

Amazon EBS is block storage for cloud workloads. Its primary use cases are for providing persistent storage for EC2 instances.

#### What are the main types of EBS volumes and their characteristics?

The main types pf EBS volumes are SSD, HDD, and Magnetic. SSD are for transactional workloads involving frequent read/write with small I/O size. HDD are for large streaming workloads where the dominant performance attribute is throughput. Magnetic are for workloads with small datasets where data is accessed infrequently and performance is not of primary importance.

#### What is the difference between Amazon EBS and instance store?

The difference between EBS and instance store is that your data in EBS will retain on the volume until you delete it, instance store will lose your data as soon as you terminate your instance.

#### What are some common use cases for instance store volumes?

Common use cases for instance store volumes are temporary caching, stateful applications, and high-performance workloads.

#### Can you attach an EBS volume to multiple EC2 instances at the same time?

Yes with EBS Muti-Attach for shared storage.

#### What is the maximum size of a single Amazon EBS volume?

The maximum size is 64 TiB.

#### How do you ensure the durability of data stored in Amazon EBS?

By replicating the EBS volume data across multiple servers in a n availability zone.

#### What is Amazon EBS Snapshots and how are they used?

They're a point-in-time copy of your data, and they're used to enable disaster recovery, migrating data across regions or accounts, and improve backup compliance.

#### Can you change the volume type of an existing Amazon EBS volume?

You can with EBS Elastic Volumes.

#### What is Amazon Elastic File System (Amazon EFS) and what are its primary use cases?

Amazon EFS provides shared file storage for use with instances in the cloud and on-premise servers. Its primary cases are for applications that require shared file access, storage for containerized and serverless applications.

#### What are the key features of Amazon EFS?

Scalability, elasticity, performace, durability/availability, backup/restore, and encryption.

#### What is Amazon FSx and what file systems does it support?

FSx provides fully managed Windows file servers, backed by fully native windows file system. It supports a broad set of Windows workloads and Server Message Block.

#### What are common use cases for Amazon FSx for Windows File Server?
Migrate Windows file servers to AWS, accelerate hybrid workloads, reduce SQL Server deployment costs, simplify virtual desktops, and streaming.

#### Can Amazon EFS be accessed from on-premises environments?

Yes it can.

#### What is the difference between Amazon EFS and Amazon FSx for Windows File Server?

EFS is used for NFS and Linux-based workloads. FSx is for Windows-based workloads and uses SMB protocol.

#### What are the performance modes available in Amazon EFS?

Bursting, Elastic, and Provisioned.

## Databases:

#### What is Amazon RDS, and what are its key features?

RDS is an easy-to-manage relational database service. RDS automates the undifferentiated database management tasks, enables customers to create new databases in minutes, and offers flexibility across eight engines and two deployment options.

#### What are the benefits of Amazon RDS?

Easy to manage, choice of engine, high availability, and operational expertise.

#### What is Amazon DynamoDB, and what are its use cases?

DynamoDB is a server;ess, NoSQL database that enables you to develop modern applications at any scale. Use cases can be financial service applications, gaming and streaming applications.

#### What is Amazon Aurora, and how does it differ from other RDS engines?

Aurora is a fully managed relational database compatible with MySQL and PostgreSQL, RDS has both but also MariaDB, SQL Server, and Oracle.

#### What is Amazon Redshift, and what is it used for?

Redshift is a data warehousing solution from AWS. It's used for large-scale data migrations.

#### What is AWS Database Migration Service (DMS), and what are its benefits?

DMS is a managed migration and replication service that helps you move your database to AWS. Its benefits are minimal downtime, supports widely used databases, fast setup, low cost, and reliability.

#### What is the Schema Conversion Tool (SCT) used for in AWS database migrations?

SCT provides project-based user interface to automatically convert the database schema of your source database into a format compatible with your RDS instance.

#### What are the common steps involved in a database migration using AWS DMS?

Create an AWS replication instance, configure source RDS for SQL server database, create AWS DMS source endpoint, configure target S3 bucket, configure DMS target endpoint, create and then run the AWS DMS task.

#### What are the benefits of using AWS managed databases over EC2-hosted databases?

RDS is easier to set up, manage, and maintain than EC2-hosted databases.

#### What are some of the AWS managed database services available?

Aurora, RDS, Redshift, DynamoDB, Elasticache, MemoryDB, DocumentDB, Keyspaces, Neptune, Timestream, and Ledger database Service.

#### How does Amazon Aurora differ from Amazon RDS?

Aurora is a propriwtarym fully-managed relational database engine for MySQL, and PostgreSQL. RDS is a hosted database service that supports more than the two formerly mentioned.

#### Why might you choose Amazon DynamoDB for your application?

To build modern, serverless applications that can start small and scale globally.

#### What are the benefits of using Amazon Redshift for data warehousing?

Redshift enables fine grained access controls such as role-based acceess controls, row and column level security, and a an easy authentication experience with single sign-on for your organization.
