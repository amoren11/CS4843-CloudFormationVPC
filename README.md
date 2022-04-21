# CS4843-CloudFormationVPC
Set up of VPC through yaml and json files in AWS

# Network Stack
In the network parameters and yaml file we set up the VPC along with all the public and
private subnets where we hold NAT Gateways, the Auto Scaling web servers, 
and the databases.

# Server Stack
In the server parameters and yaml file we set up the instances responsible for the load balancing and the web-app server. We also establish the security groups for the load balancer, the configuration of the web server, and the web server.

# Database Stack
In the database parameter and yaml file we set up two MySQL databased within the private subnets of the VPC. We set up two databases and each yaml template cooresponds to one of each of the databases.

# Diagram of Infrastructure

# Stack Fully Deployed
![alt text](https://github.com/amoren11/CS4843-CloudformationVPC/blob/main/AWS_CloudFormation_ScreenShot.png?raw=true)

