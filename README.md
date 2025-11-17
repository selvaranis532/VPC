# VPC

 ## NAME: SELVARANI S
 ## REG NO : 212224040301

## Aim:
To set up of a Private Cloud  in AWS.
         Setting up of a private cloud in AWS:
Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC),
involves creating a logically isolated virtual network that you can use to launch AWS
resources.
This provides you with full control over your virtual networking environment,
including resource placement, connectivity, and security.
Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual
networking environment, including resource placement, connectivity, and security. Get
started by setting up your VPC in the AWS service console. 
Next, add resources to it such as
Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS)
instances. Finally, define how your VPCs communicate with each other across accounts,
Availability Zones, or AWS Regions.
## Procedure:
1. Plan Your VPC:
```
● Determine your needs:
Define your use case, including application requirements, security needs, and
compliance standards.

● Plan IP address ranges:
Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.

● Select Availability Zones:
Decide which Availability Zones (AZs) you'll use for your resources, considering
redundancy and performance.

● Plan internet connectivity:
Determine if you need public internet access and how to configure it.

● Define security:
Plan your security groups, network ACLs, and access controls to ensure a secure
environment.
```
2. Create Your VPC:
```
•	Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.
•	 Choose "Create VPC": Initiate the VPC creation process.
•	Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and other necessary settings.
•	Create subnets: Define subnets within your VPC to isolate different parts of your network.
•	Create route tables: Specify how traffic is routed within and outside the VPC.
•	 Create security groups: Define access control rules for your resources.
```
3. Deploying Resources:
```
•	Launch EC2 instances: Create and launch virtual machines within your VPC.
•	 Set up RDS instances: Deploy databases for your applications.
•	Configure networking: Connect your resources to the appropriate subnets, security groups, and route tables.
•	Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.
```
4.Managing and Monitoring:
```
•	Use AWS CloudWatch: Monitor your VPC and resources for performance and  health.
•	Configure logging and auditing: Track access and activity within your VPC for security and compliance.
•	Implement security best practices: Regularly review and update your security configuration.
•	Scale and adjust as needed: Adjust your VPC infrastructure to meet changing demands.
```
## SnapShot 1:
  
<img width="1914" height="917" alt="Screenshot 2025-10-24 161557" src="https://github.com/user-attachments/assets/8ce98d88-6779-4f8b-bb64-55d0ba4eef76" />

## Snapshot 2:

<img width="1919" height="856" alt="Screenshot 2025-10-24 161651" src="https://github.com/user-attachments/assets/3ddc4b99-4fbf-40d2-b1c8-8cac5f094129" />

## Snapshot 3:

<img width="1916" height="892" alt="Screenshot 2025-10-24 135530" src="https://github.com/user-attachments/assets/d92b9d0b-720d-40df-9f9a-c5d9839b1f93" />

## Snapshot 4:

<img width="1919" height="962" alt="Screenshot 2025-10-24 135558" src="https://github.com/user-attachments/assets/456dc8f9-7810-4d55-9f09-c0bf54be651d" />

## Result:
Thus, a  private cloud on AWS involves using VPCs has been created for  a dedicated, isolated network where we can manage our resources and control access according to our requirements.
