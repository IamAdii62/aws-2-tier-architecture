# AWS 2-Tier Architecture Project

This project demonstrates a basic 2-tier architecture on AWS where the application and database are deployed on separate EC2 instances.

## Architecture
- VPC with Public and Private Subnets
- Internet Gateway and Routing
- Security Groups for access control
- WordPress deployed on Public EC2
- MySQL deployed on Private EC2

## What I Did
- Created custom VPC and networking setup
- Launched two EC2 instances
- Installed WordPress on application server
- Installed MySQL on database server
- Connected WordPress with MySQL using private IP

## Challenges Faced
- SSH access issues
- MySQL remote access configuration
- Database connectivity errors in WordPress

## Errors Debugged
- Host not allowed to connect
- Access denied for user
- Error establishing database connection

## Learnings
- Practical AWS networking
- Security groups and access control
- Application and database communication
- Troubleshooting real-world issues

## Next Steps
- Add Load Balancer
- Implement Auto Scaling
- Use managed database (RDS)

![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)
![alt text](image-4.png)
![alt text](image-5.png)
![alt text](image-6.png)
![alt text](image-7.png)
![alt text](image-8.png)
![alt text](image-9.png)
![alt text](image-10.png)
![alt text](image-11.png)
![alt text](image-12.png)
