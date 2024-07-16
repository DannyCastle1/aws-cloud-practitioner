## Domain 1: Cloud Concepts (24% of scored content)

![AWS Cloud Practitioner Domains](https://github.com/emiliedionisio/aws-cloud-practitioner-C02/blob/main/1-cloudconcepts.png)

#### What is Cloud Computing?

Cloud computing is the on-demand delivery of compute power, database, storage, applications, and other IT resources through a could services platform via the internet.

#### What are the three deployment models for cloud computing, their definitions, and uses?

The three deployment models for cloud computing are cloud-based, on-premise, and hybrid deployment. In cloud-based you can run everything on the cloud. You can design or migrate your own applications. You don't need to hire staff to manage any of it. On-premise means you have physical resources at a location, but managed virtually. Hybrid is a mix of both. You connect cloud-based resources with on-premise infrastructure.

#### What are the Benefits of cloud computing and their definitions?

The benefits of cloud computing are:
 - Trade upfront expense for variable expense: instead of having to invest in equipment you can only pay for what you use.
 - Stop spending money to run and maintain data centers: you don't need to rent a physical location or pay for IT resources to keep the business running.
 - Stop guessing capacity: you don't have to guess or overpay how much you'll need to start your business.
 - Benefit from massive economies of scale: you save because you're essentially sharing resources with a huge scale of people in the cloud. This means that you pay less than owning your own infrastructure.
 - Increase speed and agility: allows the flexibility to deploy applications instead of having to go out and purchase your own. You can add resources in minutes as needed.
 - Go global in minutes: you can deploy applications to customers around the world quick, even if your consumer base is located far away from you.

#### What are the Amazon EC2 instance types and their definitions?

The Amazon Elastic Compute Cloud instance types are:
- General purpose: they provide a balance of compute, memory, and networking resources.
- Compute optimized: they're ideal for compute-bound applications that benefit from high-performance processors.
- Memory optimized: they're designed to deliver fast performance for workloads that process large datasets in memory.
- Accelerated computing: They use coprocessors (hardware accelerators) to perform more efficient than regular CPU's.
- Storage optimized: They're designed for workloads that require high sequential read and write access to large datasets on local storage.

#### What is a Load Balancer?

A load balancer acts as a single point of contact for all incoming web traffic to your Auto Scaling group. Before adding more instances, they're routed to the load balancer first.

#### What is the primary purpose of AWS Regions in the global infrastructure?

The primary purpose of AWS Regions in the global infrastructure is that the AWS cloud is built around Regions and Availability Zones. A Region is a physical location in the world where they have multiple Availability Zones, and consists of one or more hidden data centers.

#### Describe the function of Amazon CloudFront in AWS's architecture.

The function of Amazon CloudFront is a Content Delivery Network service that securely delivers data, videos, applications, and API's to customers with low latency, and high transfer speed.

#### How do AWS Edge locations enhance the performance of Amazon CloudFront?

AWS Edge Locations enhance the performance of Amazon CloudFront because it allows CloudFront to store cached data on your content closer to them using Edge Locations for faster delivery.

#### Explain how Amazon Route 53 integrates with AWS Edge locations to enhance user experiences.

Amazon Route 53 integrates with AWS Edge Locations to enhance user experience in various ways. One is traffic flow. It routes end users to the best endpoint for your application based on geoproximity and latency. Another is Geo DNS, where it routes end users to a particular endpoint that's specified based on the users' location. Along with Edge Locations (where data is cached for easier delivery), it allows for seamless delivery no matter where you're located.

#### What are the advantages of using AWS Outposts for local data processing needs?

The advantages of using AWS Outposts for local data processing needs are the same as on-premise cloud deployments. You can control where your data is running and stored, but allows you to use the wide range of cloud resources as needed.

#### How are AWS Lambda and AWS Outposts different in what they offer for cloud computing?

AWS Lambda and Outposts differ in what they offer for cloud computing is that Lambda allows you to deploy applications without a server, but Outposts allows you to extend your AWS cloud to where your business isn't deployed.

#### What is high availability?

High availability means that any It resource is available at a high level, continously, and without intervention. It can handle and deliver quality performace with minimal or no downtime.

#### What are the benefits of AWS having a global infrastructure with multiple regions?

The benefits of using AWS global infrastructure is that it's the largest cloud provider so far, and it allows you more flexibilty to choose your deployment preference.

#### What is an AWS Region?

An AWS Region is a physical location in the world where they have multiple Availability Zones, and consists of one or more hidden data centers. They're largely separated but seamlessly connected.

#### Why is data sovereignty important in AWS Regions?

Data sovereignty is important in AWS Regions because you have control of where you manage your data in the cloud. You have the flexibility to choose where and how you run your data.

#### How do AWS Regions enhance disaster recovery capabilities?

AWS Regions enhance disaster recovery capabilities by having a continuous backup of data for a Region. Since each Region has mupltiple Availability Zones, they're isolated from each other.

#### What are the four main factors to consider when choosing an AWS Region?

The four main factors to consider when choosing an AWS Region are latency, price, service availability, and compliance.

#### What is an AWS Availability Zone?

An AWS Availability Zone are one more discreet data centers, each with their own power, network, and connectivity. They're also isolated from one another.


#### What is the purpose of having multiple Availability Zones within an AWS Region?

The purpose of having multiple Availability Zones within an AWS Region is to ensure security, network speed, and prevent any downtime in case of a disaster.

#### How does AWS ensure low latency communication between Availability Zones?

AWS ensures low latency communication between Availability Zones since they're interconnected with high-bandwidth while making sure network performance stays at peak level.

#### Why is it important to run EC2 instances across multiple AZs?

It's important to run EC2 instances across multiple AZ's because in the rare event that one AZ fails, your workload continues without disruption.

#### How do regional AWS services enhance high availability?

Regional AWS services enhance high availability by making sure of continuous uptime and resilience for your data.

#### What is the purpose of Amazon CloudFront?

The purpose of Amazon CloudFront is the AWS Content Delivery Network that allows secure delivery of data, videos, applications, and API's to customers with low latency, and high transfer speed.

#### What are edge locations in AWS?

Edge Locations in AWS are sites that store cached copies of your data closer to your customer for faster delivery.

#### What is AWS Outposts?

AWS Outposts is similar to on-premise cloud deployment. It allows you to extend your cloud infrastructure to any region you choose.
