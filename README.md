# Configure Layered Security - AWS VPC

## Objective

The objective of this lab was to set up a Virtual Private Cloud (VPC) and launch EC2 instances within this environment on AWS. The tasks included creating a new VPC, setting up internet gateways, subnets, route tables, security groups, and network ACLs, and launching EC2 instances for public and private network access. This project aimed to demonstrate the fundamental components of networking within AWS to ensure secure, scalable, and isolated network environments for applications running on EC2 instances.


### Skills Learned

- VPC Configuration: Learned how to create and configure a VPC with custom IP ranges, enhancing understanding of network isolation and segmentation in cloud environments.
- Subnet Management: Gained skills in subnetting a VPC for public and private resources, which is critical for effective network design.
- Internet Gateway Setup: Configured and attached internet gateways to the VPC, enabling connectivity between the EC2 instances and the internet.
- Route Tables Configuration: Set up route tables with appropriate routes for directing traffic from subnets to destinations like the internet gateway.
- Security Group and NACLs Configuration: Developed understanding of AWS security layers by creating and configuring Security Groups and Network ACLs to manage inbound and outbound traffic rules.
- EC2 Instance Deployment: Acquired hands-on experience in launching and configuring EC2 instances within the VPC, practicing the assignment of security groups and key pairs.

### Tools Used

- AWS Management Console: Main interface for managing all AWS services including VPC, EC2, Internet Gateways, and more.
- AWS CLI: Used for scripting and automation of AWS service configurations.
Amazon EC2 Dashboard: Utilized for launching, managing, and monitoring EC2 instances.
- Network Management Tools: Employed for monitoring the setup and ensuring all components are correctly configured and communicating.
- Security Management Tools: Used for configuring and monitoring Security Groups and NACLs to ensure the security of network traffic.

## Steps
Create a VPC<img width="1470" alt="Screenshot 2024-05-11 at 8 16 04 PM" src="https://github.com/Hunter102002/Layered-Security-AWS-VPC/assets/98543129/ee39f91a-c519-43f0-9e31-19cd45f3b790">

Create Internet Gateway
<img width="1470" alt="Screenshot 2024-05-11 at 8 16 51 PM" src="https://github.com/Hunter102002/Layered-Security-AWS-VPC/assets/98543129/268081ed-8828-4518-afca-171dbb447af3">

Attach to VPC<img width="1430" alt="Screenshot 2024-05-13 at 2 35 33 PM" src="https://github.com/Hunter102002/Layered-Security-AWS-VPC/assets/98543129/2ce259ba-705a-4f8a-9ed8-3184e6360ef7">

Create 2 Subnets<img width="1428" alt="Screenshot 2024-05-13 at 2 37 05 PM" src="https://github.com/Hunter102002/Layered-Security-AWS-VPC/assets/98543129/57ddece7-c236-40e9-91d4-f1305a63f61c">

Create 2 route tables<img width="1431" alt="Screenshot 2024-05-13 at 2 38 12 PM" src="https://github.com/Hunter102002/Layered-Security-AWS-VPC/assets/98543129/a247e99e-50de-4536-b5bf-3fc542934513">

Create security group for EC2 Instance<img width="1470" alt="Screenshot 2024-05-11 at 8 26 32 PM" src="https://github.com/Hunter102002/Layered-Security-AWS-VPC/assets/98543129/7795a485-5305-4463-baf9-436abc5434ad">

Create Network ACL - Edit inbound and outbound rules<img width="1470" alt="Screenshot 2024-05-11 at 8 28 43 PM" src="https://github.com/Hunter102002/Layered-Security-AWS-VPC/assets/98543129/296351ca-5893-44e1-a93b-5d1c0ffe5148">

Launch EC2 instance<img width="1226" alt="Screenshot 2024-05-11 at 8 39 02 PM" src="https://github.com/Hunter102002/Layered-Security-AWS-VPC/assets/98543129/20055f76-fb46-462e-af9d-48f3265f6a08">

Test Instance<img width="582" alt="Screenshot 2024-05-13 at 2 44 36 PM" src="https://github.com/Hunter102002/Layered-Security-AWS-VPC/assets/98543129/8a39ee0b-fa17-43e8-8cf6-c456cbfac7fa">
