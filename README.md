# Scalable Web App with ALB and Auto Scaling

## Project Overview

This project demonstrates how to build a scalable and highly available web application on AWS using:

* Amazon EC2
* Application Load Balancer (ALB)
* Auto Scaling Group (ASG)
* Security Groups

The architecture automatically distributes incoming traffic across multiple EC2 instances and scales resources based on demand.

## Architecture
<img width="1536" height="1024" alt="architecture-diagram png" src="https://github.com/user-attachments/assets/281ee16a-fe75-4e1f-aa0d-b13b85011109" />


Users → Application Load Balancer → Auto Scaling Group → EC2 Instances

## AWS Services Used

* Amazon EC2
* Application Load Balancer
* Auto Scaling Group
* Security Groups

## Features

* High Availability
* Automatic Scaling
* Load Balancing
* Fault Tolerance

## Screenshots

See the screenshots folder for deployment evidence.
##Security group
<img width="1341" height="523" alt="01_security group png" src="https://github.com/user-attachments/assets/e4183739-edd5-4a1a-9629-c8f9ececce4c" />
##Launch template
<img width="1361" height="554" alt="02_launch-template" src="https://github.com/user-attachments/assets/8a13adbf-63fe-4111-b687-05db66434a54" />
##Target group
<img width="1356" height="418" alt="03_target group" src="https://github.com/user-attachments/assets/08cfb2ca-3486-43fb-8dd3-5321d9db8059" />
##ALB created
<img width="1355" height="445" alt="04_alb-created" src="https://github.com/user-attachments/assets/2a1079f4-b9f0-411d-b042-8e354bf8c506" />
##Auto scaling group
<img width="1358" height="552" alt="auto-scaling-group" src="https://github.com/user-attachments/assets/bb04bf32-0951-407e-98fc-54949b3c15ad" />
##Healthy targets
<img width="1348" height="500" alt="healthy-targets" src="https://github.com/user-attachments/assets/ce1bd7b3-54fa-4f13-9ce5-182df4e4aaea" />
##Instances ruuning
<img width="1353" height="308" alt="instance running" src="https://github.com/user-attachments/assets/fd39ee07-6db0-442d-8aee-3f7064b8027b" />
##Web page output
<img width="1357" height="620" alt="webpage-output" src="https://github.com/user-attachments/assets/ac374d69-fc6f-40ac-ac75-d9974f7c3e10" />


## Result

The application was successfully deployed using an Application Load Balancer and Auto Scaling Group. Traffic is distributed automatically and the infrastructure can scale from 2 to 4 EC2 instances based on demand.
