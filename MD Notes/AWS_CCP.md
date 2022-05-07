# AWS CCP  
---
### How much, how long, how many questions?
> $100 USD  
> 90 Minutes  
> 65 Questions  
> 70% Passing Score  
> Valid for 3 years

### Exam Guide - Content Outline
|Topic|Weightage|
|---|---|
|Cloud Concepts| 28%|
|Security| 24%|
|Technology| 36%|
|Billing and Pricing| 12%|

---
### Six Advantages and Benefits of **Cloud Computing**
#### *Why go with a Cloud Provider over On-Premise ?*
1. No upfront-cost, Pay On-Demand
2. Benefit from massive economics of scale
3. Instead of paying for idle or underutilized servers, you can scale up or down to meet the current need.
4. Increase speed and agility
5. Stop spending money on running and maintaining data centers
6. Go global in minutes: *deploy your app in **multiple regions around the world with a few clicks**.*

### Types of Cloud Computing
- **SaaS** : For Customers
- **PaaS** : For Developers
- **IaaS** : For Admins

---

### AWS Global Infrastructure
- #### Regions
  A **goegraphically distinct** location which has multiple datacenters. (AZs)
  - AWS largest region is **US-EAST** (North Virginia)
  - ***New*** services almost always become available first in **US-EAST**
  - Not all services are available in all regions
  - US-EAST-1 is the region where you see all your billing information

- #### Availability Zones
  An AZ is a datacenter owned and operated by AWS in which AWS services run.
  - AZs are represented by a Region Code, followed by a letter identifier eg. **us-east-1<font color=red>b</font>**
  - Multi-AZ distributing your instances across multiple AZs allows failover configuration for handling requests when one goes down
  - Multi AZ are positioned in a region such that latency between AZs **< 10 ms**
  
- #### Edge Locations
  An Edge Location is a datacenter owned by a trusted partner of AWS which has a **direct connection** to the AWS network.
  - These locations serve requests for **CloudFront** and **Route 53**.
  - *S3 Transfer Acceleration* traffic and *API Gateway* allows **low latency** no matter where the end user is geographically located.
  
  <br>
- GovCloud (US)  
  GovCloud regions are only operated by employees who are US citizens, on US soil.
  
---
### Setting up an AWS account
Follow below steps:
1. Create AWS account
2. Set Billing Preferences, Budgets and Alarms
3. Change IAM user Sign-in Link
4. Activate MFA on your root account
5. 