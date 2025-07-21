# AWS-
Using the cloud platform Amazon AWS i created A VPC as well as configuring subnets and an internet gateway.

<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Build a Virtual Private Cloud

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-networks-vpc)

**Author:** Daniel Soledad  
**Email:** daniel.soledad10@gmail.com

---

## Build a Virtual Private Cloud (VPC)

![Image](http://learn.nextwork.org/calm_olive_peaceful_zebra/uploads/aws-networks-vpc_2facf927)

---

## Introducing Today's Project!

### What is Amazon VPC?

Amazon VPC is useful for the security and infrastructure of my resources. With VPC, I can segment resources so that on the cloud region that corresponds with my locations to isolate some resources so that I can have components private and segmented with the use of private and public subnets.  

### How I used Amazon VPC in this project

In this project, I used Amazon VPC to segment a part of the cloud region I selected, which is US-West-1, so that I could be able to host resources inside the VPC. With the use of subnets to segment the VPC and with an internet gateway, I was able to give access to the internet.

### One thing I didn't expect in this project was...

One thing I didn't expect in this project was that once you create your AWS account, it creates default resources already, so before I created an internet gateway or subnet, there were already some that were created by default.

### This project took me...

This project from start to finish took me about 20 minutes, and I was researching to gain knowledge and build at the same time. I would now be able to make this project quicker, now that I have a better understanding.

---

## Virtual Private Clouds (VPCs)

VPCs are what allow us to segment and break our cloud environment into multiple different resources/groups. They can allow us to make some parts of the cloud private for security, but also to help us have a better infrastructure for our resources.

There was already a default VPC in my account ever since I created my AWS account. This is because sets up a default VPC for you! This default VPC is why you could launch resources and connect services together from Day 1.

To set up my VPC, I had to define an IPv4 CIDR, which means a range of IP addresses that my VPC can allocate to the resources deployed into my VPC

![Image](http://learn.nextwork.org/calm_olive_peaceful_zebra/uploads/aws-networks-vpc_2facf927)

---

## Subnets

Subnets are subdivisions of my VPC, just like how neighborhoods are subdivisions of a city. There are already subnets existing in my account based on the regions where I set up my VPC. I'm in the us-west-1 region, which already has two default subnet

Once I created my subnet, I enabled auto assign public IPv4 addresses. This setting makes sure that anytime a resouces gets launched in that subnet it will instanlty get a public IP address so that It can access resources outside of the subnet like the internet.

The primary difference between public and private subnets is that private subnets are not directly connected to the internet and are used by internal resources that require public access. Public subnets are connected to the internet via an internet gateway, allowing resources within the public subnet to access the internet.

![Image](http://learn.nextwork.org/calm_olive_peaceful_zebra/uploads/aws-networks-vpc_157c4219)

---

## Internet gateways

Internet gateways are what allow VPC component access to the internet. So any resource inside my VPC can reach an internet server. An internet gateway is also how users in the public can access my resource in the public subnet 

Attaching an internet gateway to a VPC means that all the resources inside the VPC can use the internet gateway to be able to access the internet because it is outside of the VPC, and without the gateway component in the resources would not be able to reach the internet.

![Image](http://learn.nextwork.org/calm_olive_peaceful_zebra/uploads/aws-networks-vpc_4ae90410)

---

## Using the AWS CLI

---

---
