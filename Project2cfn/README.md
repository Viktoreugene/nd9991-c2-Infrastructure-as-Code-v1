Project 2 - Infrastructure as Code

This folder contains the necessary AWS CLI scripts required for successful deployment of cloudfrormation network
infrastructure.

The script describes how to setup and deploy the networking components, followed by servers, security roles and 
software inside a webserver that resides on an EC2 instance found in either of the two private subnets and the 
routing rules for accessing the internal servers without exposing their IP addresses through NAT Gateways.

The script also describes how internal and external traffic to and from the public and private subnets moves 
across the entire infrastructure.

Also included is a infrastructure diagram developed from www.lucidchart.com depicting the entire infrastructure 
dscribed by the above script.

Additionally, there is a snapshot of the website endpoint URL with a 'http://' prefix appended to it.

Website URL: http://project-alb-1uxmy9wfu23c9-363705655.us-east-1.elb.amazonaws.com/

LoadBalancer DNS Name: Project-ALB-1UXMY9WFU23C9-363705655.us-east-1.elb.amazonaws.com