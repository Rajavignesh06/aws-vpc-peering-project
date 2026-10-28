AWS VPC Peering Project

Overview
This project demonstrates private network communication between two AWS VPCs using a VPC Peering connection.

Services Used
1.AWS VPC
2.Amazon EC2
3.VPC Peering
4.Route Tables
5.Security Groups
6.Internet Gateway
7.SSH

Architecture
VPC-A: 10.10.0.0/16
VPC-B: 10.20.0.0/16
Bastion Host: 10.10.1.125
App-A: 10.10.2.60
App-B: 10.20.210.77

Implementation
1.Created two VPCs with non-overlapping CIDR blocks.
2.Configured public and private subnets.
3.Launched three EC2 instances.
4.Created and activated a VPC Peering connection.
5.Configured route tables and security groups.
6.Connected to the Bastion host using SSH.
7.Tested connectivity using private IP addresses.

Test Results
Bastion → App-A: Successful
Bastion → App-B: Successful
Packet loss: 0% for both tests

Conclusion
Successfully established and tested private network connectivity between two AWS VPCs using VPC Peering.

Technologies
AWS | EC2 | VPC | VPC Peering | Networking | Linux | SSH

Kindly check the project results screenshots in the pdf which I attached "EWB-Courses-AWS-VPC-Peering-Project.pdf".

Project Implemented by-
Rajavignesh.SA
