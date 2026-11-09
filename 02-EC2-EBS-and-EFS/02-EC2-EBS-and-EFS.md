
# 02-EC2-EBS-and-EFS

## Launch an EC2 instance

Create a key pair for secure access to the instance.

![Create a key pair](images/10-CREATE%20KEY%20PAIR.png)

Configure and launch an EC2 instance.

![Create an EC2 instance](images/10-%20create%20an%20ec2%20instance.png)

![EC2 instance configuration](images/11-%20create%20an%20ec2%20instance.png)

## EC2 user data

Use user data to run commands or a startup script when the instance launches.

![Configure EC2 user data](images/12-%20create%20an%20ec2%20instance%20user%20data.png)

![Instance is running](images/13-%20instance%20is%20up.png)

## Attach an IAM role to EC2

Attach an IAM role to the instance so applications running on it can access permitted AWS services without storing long-term credentials.

![Attach an IAM role](images/14-%20attach%20IAM%20role%20to%20EC2%20instance.png)

![View the attached IAM role](images/15-%20view%20the%20attached%20IAM%20role%20to%20EC2%20instance.png)

## EC2 placement groups

Create a placement group and select it when launching an EC2 instance.

![Create placement groups](images/16-%20CREATE%20PLACEMENT%20GROUPS.png)

![Select a placement group](images/17-%20select%20placement%20group%20when%20creating%20an%20ec2%20instance.png)

## EBS volumes and snapshots

Create an EBS volume and attach it to an EC2 instance. An EBS volume is Availability Zone-specific, so it must be in the same Availability Zone as the instance to attach it.

![Create an EBS volume](images/18-%20CREATE%20EBS%20VOLUME.png)

![Attach an EBS volume](images/19-ATTACH%20EBS%20VOLUME.png)

![EBS volume attachment](images/20-ATTACH%20EBS%20VOLUME.png)

Create a snapshot of the volume. Snapshots can be copied to another Region or used to create new EBS volumes.

![Create an EBS snapshot](images/21-CREATE%20A%20SNAPSHOT%20FROM%20THE%20EBS%20VOLUME.png)

## EBS snapshot retention

Create a retention rule to manage the lifecycle of snapshots.

![Create a retention rule](images/22-%20Create%20a%20RetentionRule.png)

## AMIs

Launch an instance to use in the AMI exercise, create an image from it, and launch another instance using that AMI.

![Create an instance for the AMI exercise](images/23-%20CREATE%20a%20new%20instance%20for%20AMI.png)

![Create an image from the instance](images/24-%20create%20a%20new%20image%20from%20the%20AMI.png)

![Launch an instance from an AMI](images/25-LAUNCH%20A%20NEW%20INSTANCE%20FROM%20AN%20AMI.png)

![Access the new instance](images/26-%20access%20it.png)

## Amazon EFS

Create an EFS file system for shared file storage.

![Create an EFS file system](images/27-Create%20EFS.png)

---
