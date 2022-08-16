# Cloud-DevOps---Deploy-a-high-availability-web-app-using-CloudFormation
This is the second project in the Udacity Advanced Cloud DevOps Nanodegree (Deploy a High Availability Web App using AWS CloudFormation).


- Diagram for infrastructure:
<img src="Omar - Udacity Project 2 - Cloud DevOps.png" >

- This establishes a Virtual Private Cloud using two availability zones and two public and private subnets. 
 -   On the public subnets, an Internet Gateway is installed and given a default route. 
 -   The default routes for the private subnets refer to the two NAT Gateways that have been installed in different AZs.
 <br>
 - Then we will deploy an Application Load Balancer, a Listener, Security Group rules, and an AutoScaling 
    Group of t3.medium EC2 instances with a minimum of 4 instances and a maximum of 8 instances, 
    along with associated Launch Configurations that download the Web Application code from an S3 Bucket.


### Server works well, check it from this [link](http://omar-webse-fylupg2dp171-1416431508.us-east-1.elb.amazonaws.com/)
