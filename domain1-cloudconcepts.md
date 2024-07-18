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

AWS Regions enhance disaster recovery capabilities by having a continuous backup of data for a Region. Since each Region has multiple Availability Zones, they're isolated from each other.

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

#### How do Availability Zones within AWS Regions contribute to disaster recovery and high availability?

AZ's contribute to disaster recovery and high availability because your work is better protected from a single point of failure. Each AZ has their own backup, as well as being separate from each other.

#### How do AWS Edge locations and Amazon CloudFront improve content delivery?

AWS Edge Locations and CloudFront improve content delivery by storing cached copies of your content closer to your customers.

#### What is an API in the context of AWS?

An API in the context of AWS are mechanism that enables two software components to communicate with each other using a set of definitions and protocols.

#### What is the primary method of interacting with AWS services?

The primary method of interacting with AWS services is the AWS Management Console.

#### What are the main ways to interact with AWS services?

The main ways to interact with AWS services are the AWS Management Console, the Command Line Interface, and Sofware Development Kits.

#### Why is automation important in cloud deployment?

Automation is important in cloud development because it helps ensure optimal performace and its resources. It also helps reduce IT staff from managing repetitive tasks.

#### What is the primary advantage of using AWS Elastic Beanstalk over manual methods like the AWS Management Console?

The primary advantage of using AWS Elastic Beanstalk over manual methods is that it's the fastest way to get web applications up and running on AWS. Just upload your code, and Beanstalk handles everything from resource provisioning, load balancing, auto scaling, and monitoring.

#### What is AWS Elastic Beanstalk used for?
AWS Elastic Beanstalk is used for quick deployment and managing applications without having to control the infrastructure running the applications.

#### How does AWS CloudFormation help in managing AWS resources?

AWS CloudFormation helps in managing AWS resources by managing and set up cloud resources so you spend less time managing and just focus on your applications.

#### What are the main components of AWS Global Infrastructure?

The main components of AWS Global Infrastructure are Regions, Availability Zones, and Edge Locations.

#### Which AWS services automatically run across multiple Availability Zones?

The AWS services that automatically run across multiple AZ's are EC2, Beanstalk, and CloudFormation.

#### What is the recommended best practice for deploying infrastructure in AWS?

The recommended best practice for deploying infrastructure in AWS are CloudFormation.

#### What is Amazon EC2?

Amazon EC2 provides resizable compute capacity in the cloud.

#### What is Amazon EC2 and its primary benefits?

Amazon EC2 is designed to make web-scale computing easier for developers. Its primary benefits are that you trade fixed cost for variable cost. No need to invest in upfront hardware.

#### What is a Security Group in EC2?

A Security Group in EC2 acts as a virtual firewall that controls network access to your instances.

#### What are the four main purchasing options for EC2 instances, and what are their key characteristics?

The four main purchasing options for EC2 instances are:
- On-Demand: pay for compute capacity as needed.
- Reserved: Allows you to reserve as needed.
- Savings Plan: flexible pricing model in exchange for a one or three year commitment.
- Spot: Allows you to take advantage of unused EC2 capacity available in the cloud, but it can be interrupted by AWS at anytime (and with a warning).

#### How does EC2 pricing work?

The pricing differ depending on which instance you purchase. The four are:
- On-Demand: you pay per hour, and depends on which EC2 you decide.
- Reserved: up to 72% discount (compared to On-Demand).
- Savings Plan: flexible pricing in exchange for a one or three year commitment.
- Spot: request spare EC2 (for up to 90% discount) that can be interrupted by AWS at any time with a warning.

#### What is an Amazon Machine Image (AMI)?

An AMI is an image that provides the information required to launch an instance.

#### How does EC2 integrate with other AWS services?

EC2 integrates with other AWS services throught the AWS Management Console.

#### What are the different computing models available in AWS?

The different computing models available in AWS are General Purpose, Compute Optimized, Accelerated Computing, Memory Optimized, and Storage Optimized.

#### What is an instance and its use cases?

An instance is a virtual machine in the AWS cloud.
