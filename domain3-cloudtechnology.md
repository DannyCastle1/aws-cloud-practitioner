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


