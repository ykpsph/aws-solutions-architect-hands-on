# 03-ELB-and-ASG

## Prepare EC2 instances

Create two EC2 instances to use as targets behind a load balancer.

![Two EC2 instances created](images/28-%20CREATED%202%20Instances.png)

## Application Load Balancer

Create an Application Load Balancer, select the Availability Zones, configure its security group, and create a target group.

![Create an Application Load Balancer](images/29-CREATE-ALB-1.png)

![Select Availability Zones and configure the security group](images/29-CREATE-ALB-2-SELECT%20AZs%20-%20CREATE%20SG.png)

![Create a target group](images/29-CREATE-ALB-3-create-target-group.png)

Access the application through the load balancer.

![Access the application through the ALB](images/30-access-through-ALB.png)

Update the EC2 security group so that inbound application traffic is allowed only from the ALB security group.

![Restrict inbound traffic to the ALB](images/31-edit-inbound-rules-to-allow-traffic-only-coming-from-ALB.png)

## Auto Scaling Group

Create an Auto Scaling Group and observe it launch EC2 instances based on its configuration.

![Auto Scaling Group launches EC2 instances](images/32-ASG-CREATING-EC2-BY-ITSELF.png)

![Create an Auto Scaling Group](images/33-CREATE%20AN%20ASG.png)

Configure scaling policies to adjust the desired capacity based on defined conditions.

![Auto Scaling policies](images/34-SCALING%20POLICIES%20CAN%20BE%20CREATED%20HERE.png)

## Amazon RDS

Create an RDS database and connect to it using SQL Electron.

![Create and connect to an RDS database](images/35-CREATE-RDS-DB-AND-CONNECT-VIA-SQLELECTRON.png)

---
