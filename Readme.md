## Table of Content
- [Overview](#overview)
- [History](#history)
- [Certifications](#certifications)
- [Installation](#installation)
- [Modules](#modules)
- [Appendix](#appendix)

## Overview
- The idea of this tutorial is to provide my perspective and knowledge on **Amazon Web Service (AWS Cloud)**.
- AWS is a subsidiary of **Amazon** that provides on-demand cloud computing platforms and APIs to individuals, companies, and governments, on a metered pay-as-you-go basis.
- For any company to innovate, infrastructure is the pre-requisite. AWS helps organizations to resolve this concern. Ther are three types of cloud solutions providers
  - **IAAS**: Infrastructure As A Service, this service is used to provide enterprise requirements of Compute, Storage, Network, and Security. Offering hear include EC2, S3, VPC, EBS etc...
  - **PAAS**: Platform As A Service, this service is used to provide a platform for the developer to easily deliver their solutions like Fargate, Lambda, RDS etc...
  - **SAAS**: Software As A Service, this service is an end software product used by the customer. AWS does not have any offering in this area but there are companies like Netflix, Amazon Prime, etc... provide solutions to end customers.
- AWS is trying to resolve enterprise customers datacenter requirements like autoscaling, multi-region availability, fault-tolerant, and security. These are provided with below:
  - **Regions**: There are different areas where AWS provides datacenters like Virginia, London, etc... The exact location details of these regions are highly classified to avoid threats from terrorist attacks as this contains multiple enterprise customer's data.
  - **Availability Zones**: These are exact areas where data centers are available. Alphanumeric names will be used to indicate these areas like 1a, 1b. In a region, there will be atleast two availability zone. These are typically located in extreme opposite locations in a region to avoid environmental catastrophes. A completed list of AWS AZ's are listed [here](https://aws.amazon.com/about-aws/global-infrastructure/).
  - **Global Network**: Every data center, AZ, and AWS Region is interconnected via private global network infrastructure managed by AWS. Connectivity details are available [here](https://aws.amazon.com/about-aws/global-infrastructure/global_network/)


---
## History
- AWS started in **2002** by providing SOAP and XML interfaces for the Amazon product catalog.
- In **2003**, during an executive retreat at Jeff Bezos’ house, the Amazon leadership team was asked to identify the core strengths of the company. Its infrastructure was identified as a huge advantage over their competition.
- The company decided to provide a combination of infrastructure services and developer tools as an actual product for developers over the internet. They started to think of this set of services as a sort of operating system for the internet. 
- In late **2003**, the AWS concept was publicly reformulated when **Chris Pinkham** and **Benjamin Black** presented a paper describing a vision for **Amazon's retail computing infrastructure**.
- In **2004**, the company’s first public acknowledgment AWS in a [blog post](https://aws.amazon.com/blogs/aws/welcome/).
- In **November 2004**, the first AWS service launched for public usage, **Simple Queue Service (SQS)**. Thereafter **Pinkham** and lead developer **Christopher Brown** developed the **Amazon EC2** service, with a team in **Cape Town, South Africa.**
- AWS was officially re-launched on **March 14, 2006**, with three services S3, SQS and EC2. **Andy Jassy** was AWS founder and Vice President in 2006. In 2016, Jassy was promoted to CEO of the division.
- Milestones
  - In November 2010, Amazon.com's retail sites had migrated to AWS.
  - In November 2012, AWS hosted its first customer event in Las Vegas.
  - In 2014, AWS launched its partner network entitled APN (AWS Partner Network).
  - In January 2015, Amazon Web Services acquired Annapurna Labs, an Israel-based microelectronics company.
  - In January 2018, Amazon launched an autoscaling service on AWS.
  - In November 2018, AWS announced customized ARM cores and ground stations to communicate with customer's satellites.
  - [Timeline](https://en.wikipedia.org/wiki/Timeline_of_Amazon_Web_Services)
- [Outages](https://en.wikipedia.org/wiki/Timeline_of_Amazon_Web_Services)

---
## Certifications
- AWS Certification validates cloud expertise to help professionals highlight in-demand skills and organizations build effective, innovative teams for cloud initiatives using AWS.
- Below are the different [certifications](https://aws.amazon.com/certification/) provided by AWS. This tutorial focus on fundaments for **AWS Associate Developer**. 
  - Foundation is optional for Associate.
  - Associate is mandatory for Professional program.
  - Atleast one Foundation/Associate program required for Specialization Program.
  ![](./01-Images/01-Certificates.png) 

---
## Installation
- AWS Support accessing management console using below. This tutorial focus on using AWS Console. A brief overview of other access mechanisms is detailed in the Identity module below. 
  - [AWS UI Console](https://console.aws.amazon.com) 
  - AWS CLI
  - AWS Rest API

---
## Modules
- There are multiple modules of AWS that we have to go through to master it. Below is a comprehensive list of modules that will be covered as part of this tutorial.

---
## Appendix
- Reference
  - [LinuxAcademy](https://linuxacademy.com/learning-path/amazon-web-services-master-level/)
  - [Greatlearning](https://www.greatlearning.in/academy/enterprise/courses/cloud-computing-with-aws)
    