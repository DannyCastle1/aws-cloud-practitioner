## Domain 3: Cloud Technology and Services (34% of scored content)

![AWS Cloud Practitioner Domains](https://github.com/emiliedionisio/aws-cloud-practitioner-C02/blob/main/3-cloudtech.png)

## Networking:

#### What is a VPC in AWS, and why is it important?

A Virtual Private Cloud is a virtual network dedicated to your AWS account. It's logically isolated from other virtual networks in the cloud. It's important because you can specify an IP range for the VPC, add subnets, gateways, and associate security groups.

#### What is a subnet, and how is it used in a VPC?

A subnet is a range of IP addresses in your VPC. It's used in a VPC by launching your EC2 instance into your subnet. From there you can connect a subnet to the internet, other VPC's, data centers, and route traffic from your subnets using route tables.

#### What is an Internet Gateway, and what role does it play in a VPC?
An interet gateway is a horizontally scaled, redundant, and highly available VPC component that allows communication between your VPC and the internet.

#### What is a NAT Gateway, and why would you use it in a VPC?

A NAT gateway is a Network Address Translation service. You would use it so that instances in a private subnet can connect to services outside of your VPC, but external services can't initiate connection with the instances.

#### What is a Route Table, and how does it function in a VPC?

A route table contains a set of rules, called routes, that determine where network traffic from your subnet or gateway is directed.
