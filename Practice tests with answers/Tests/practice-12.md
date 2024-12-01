### 1
Is there any way to own a direct connection to Amazon Web Services?

- [ ] You can create an encrypted tunnel to VPC, but you don't own the connection.
- [ ] Yes, it's called Amazon Dedicated Connection.
- [ ] No, AWS only allows access from the public Internet.
- [ ] Yes, it's called Direct Connect.

- - - - - -

### 2
Which of the following strategies can be used to control access to your Amazon EC2 instances?

- [ ] DB security groups.
- [ ] IAM policies.
- [ ] None of these.
- [ ] EC2 security groups.

- - - - - -

### 3
A client of yours has a huge amount of data stored on Amazon S3, but is concerned about someone stealing it while it is in transit. You know that all data is encrypted in transit on AWS, but which of the following is wrong when describing server-side encryption on AWS?

- [ ] Amazon S3 server-side encryption employs strong multi-factor encryption.
- [ ] Amazon S3 server-side encryption uses one of the strongest block ciphers available, 256-bit Advanced Encryption Standard (AES-256), to encrypt your data.
- [ ] In server-side encryption, you manage encryption/decryption of your data, the encryption keys, and related tools.
- [ ] Server-side encryption is about data encryption at rest―that is, Amazon S3 encrypts your data as it writes it to disks.

- - - - - -

### 4
When you run a DB Instance as a Multi-AZ deployment, the [...] serves database writes and reads

- [ ] secondary.
- [ ] backup.
- [ ] stand by.
- [ ] primary.

- - - - - -

### 5
In Amazon EC2, how many Elastic IP addresses can you have by default?

- [ ] 10.
- [ ] 2.
- [ ] 5.
- [ ] 20.

- - - - - -

### 6
A user has created photo editing software and hosted it on EC2. The software accepts requests from the user about the photo format and resolution and sends a message to S3 to enhance the picture accordingly. Which of the below mentioned AWS services will help make a scalable software with the AWS infrastructure in this scenario?

- [ ] AWS Simple Notification Service.
- [ ] AWS Simple Queue Service.
- [ ] AWS Elastic Transcoder.
- [ ] AWS Glacier.

- - - - - -

### 7
Using Amazon CloudWatch's Free Tier, what is the frequency of metric updates which you receive?

- [ ] 5 minutes.
- [ ] 500 milliseconds.
- [ ] 30 seconds
- [ ] 1 minute.

- - - - - -

### 8
When you resize the Amazon RDS DB instance, Amazon RDS will perform the upgrade during the next maintenance window. If you want the upgrade to be performed now, rather than waiting for the maintenance window, specify the [...] option.

- [ ] Apply Now.
- [ ] Apply Soon.
- [ ] Apply This.
- [ ] Apply Immediately.

- - - - - -

### 9
A user is running a webserver on EC2. The user wants to receive the SMS when the EC2 instance utilization is above the threshold limit. Which AWS services should the user configure in this case?

- [ ] AWS CloudWatch + AWS SQS.
- [ ] AWS CloudWatch + AWS SNS.
- [ ] AWS CloudWatch + AWS SES.
- [ ] AWS EC2 + AWS Cloudwatch.

- - - - - -

### 10
You're running an application on-premises due to its dependency on non-x86 hardware and want to use AWS for data backup. Your backup application is only able to write to POSIX-compatible block based storage. You have 140TB of data and would like to mount it as a single folder on your file server Users must be able to access portions of this data while the backups are taking place. What backup solution would be most appropriate for this use case?

- [ ] Use Storage Gateway and configure it to use Gateway Cached volumes.
- [ ] Configure your backup software to use S3 as the target for your data backups.
- [ ] Configure your backup software to use Glacier as the target for your data backups.
- [ ] Use Storage Gateway and configure it to use Gateway Stored volumes.

- - - - - -

### 11
What happens to Amazon EBS root device volumes, by default, when an instance terminates?

- [ ] Amazon EBS root device volumes are moved to IA
- [ ] Amazon EBS root device volumes are copied into Amazon RD
- [ ] Amazon EBS root device volumes are automatically deleted.
- [ ] Amazon EBS root device volumes remain in the database until you delete them.

- - - - - -

### 12
You require the ability to analyze a customer's clickstream data on a website so they can do behavioral analysis. Your customer needs to know what sequence of pages and ads their customer clicked on. This data will be used in real time to modify the page layouts as customers click through the site to increase stickiness and advertising click-through. Which option meets the requirements for captioning and analyzing this data?

- [ ] Log clicks in weblogs by URL store to Amazon S3, and then analyze with Elastic MapReduce.
- [ ] Push web clicks by session to Amazon Kinesis and analyze behavior using Kinesis workers.
- [ ] Write click events directly to Amazon Redshift and then analyze with SQL.
- [ ] Publish web clicks by session to an Amazon SQS queue men periodically drain these events to Amazon RDS and analyze with SQL.

- - - - - -

### 13
What happens when you create a topic on Amazon SNS?

- [ ] The topic is created, and it has the name you specified for it.
- [ ] An ARN (Amazon Resource Name) is created.
- [ ] You can create a topic on Amazon SQS, not on Amazon SNS.
- [ ] This question doesn't make sense.

- - - - - -

### 14
A company needs to deploy virtual desktops to its customers in a virtual private cloud, leveraging existing security controls. Which set of AWS services and features will meet the company's requirements?

- [ ] Virtual Private Network connection. AWS Directory Services, and Classic link.
- [ ] Virtual Private Network connection. AWS Di rectory Services, and Amazon Workspaces.
- [ ] AWS Directory Service, Amazon Workspaces, and AWS Identity and Access Management.
- [ ] Amazon Elastic Compute Cloud, and AWS Identity and Access Management.

- - - - - -

### 15
You are designing a multi-platform web application for AWS The application will run on EC2 instances and will be accessed from PCs. tablets and smart phones Supported accessing platforms are Windows, macOS, iOS and Android Separate sticky session and SSL certificate setups are required for different platform types which of the following describes the most cost effective and performance efficient architecture setup?

- [ ] Setup a hybrid architecture to handle session state and SSL certificates on-prem and separate EC2 Instance groups running web applications for different platform types running in a VPC.
- [ ] Set up one ELB for all platforms to distribute load among multiple instance under it Each EC2 instance implements ail functionality for a particular platform.
- [ ] Set up two ELBs The first ELB handles SSL certificates for all platforms and the second ELB handles session stickiness for all platforms for each ELB run separate EC2 instance groups to handle the web application for each platform.
- [ ] Assign multiple ELBS to an EC2 instance or group of EC2 instances running the common components of the web application, one ELB for each platform type Session stickiness and SSLtermination are done at the ELBs.

- - - - - -

### 16
A company is deploying a two-tier, highly available web application to AWS. Which service provides durable storage for static content while utilizing lower Overall CPU resources for the web tier?

- [ ] Amazon EBS volume.
- [ ] Amazon S3.
- [ ] Amazon EC2 instance store.
- [ ] Amazon RD5 instance.

- - - - - -

### 17
Select the incorrect statement.

- [ ] In Amazon EC2, the private IP addresses only returned to Amazon EC2 when the instance is stopped or terminated.
- [ ] In Amazon VPC, an instance retains its private IP addresses when the instance is stopped.
- [ ] In Amazon VPC, an instance does NOT retain its private IP addresses when the instance is stopped.
- [ ] In Amazon EC2, the private IP address is associated exclusive ly with the instance for its lifetime.

- - - - - -

### 18
An organization has a statutory requirement to protect the data at rest for data stored in EBS volumes. Which of the below mentioned options can the organization use to achieve data protection?

- [ ] Data replication.
- [ ] Data encryption.
- [ ] Data snapshot.
- [ ] All the options listed here.

- - - - - -

### 19
A web design company currently runs several FTP servers that their 250 customers use to upload and download large graphic files They wish to move this system to AWS to make it more scalable, butthey wish to maintain customer privacy and Keep costs to a minimum. What AWS architecture would you recommend?

- [ ] Ask their customers to use an S3 client instead of an FTP client. Create a single S3 bucket Create an IAM user for each customer Put the IAM Users in a Group that has an IAM policy that permits access to sub-directories within the bucket via use of the 'username' Policy variable.
- [ ] Create a single S3 bucket with Reduced Redundancy Storage turned on and ask their customers to use an S3 client instead of an FTP client Create a bucket for each customer with a Bucket Policy that permits access only to that one customer.
- [ ] Create an auto-scaling group of FTP servers with a scaling policy to automatically scale-in when minimum network traffic on the auto-scaling group is below a given threshold. Load a central list of ftp users from S3 as part of the user Data startup script on each Instance.
- [ ] Create a single S3 bucket with Requester Pays turned on and ask their customers to use an S3 client instead of an FTP client Create a bucket tor each customer with a Bucket Policy that permits access only to that one customer.

- - - - - -

### 20
Amazon RDS DB snapshots and automated backups are stored in:

- [ ] Amazon S3.
- [ ] Amazon ECS Volume.
- [ ] Amazon RDS.
- [ ] Amazon EMR.

- - - - - -

### 21
Can Amazon S3 uploads resume on failure or do they need to restart?

- [ ] Restart from beginning.
- [ ] You can resume them, if you flag the 'resume on fai lure' option before uploading.
- [ ] Resume on failure.
- [ ] Depends on the file size.

- - - - - -

### 22
Prior to the introduction of this function, the HA feature provided redundancy and performance, but required that a failed/lost group member be [...] reinstated.

- [ ] automatically.
- [ ] periodically.
- [ ] manually.
- [ ] continuously.

- - - - - -

### 23
A company has a workflow that sends video files from their on-premise system to AWS for transcoding. They use EC2 worker instances that pull transcoding jobs from SQS. Why is SQS an appropriate service for this scenario?

- [ ] SQS guarantees the order of the messages.
- [ ] SQS synchronously provides transcoding output.
- [ ] SQS checks the health of the worker instances.
- [ ] SQS helps to facilitate horizontal scaling of encoding tasks.

- - - - - -

### 24
Which statement below best describes what thresholds you can set to trigger a CloudWatch Alarm?

- [ ] Set a target value and choose whether the alarm will trigger when the value is greater than (>), greater than or equal to (>=), less than (<), or less than or equal to (<=) that value.
- [ ] Thresholds need to be set in IAM not CloudWatch.
- [ ] Only default thresholds can be set you can't choose your own thresholds.
- [ ] Set a target value and choose whether the alarm will trigger when the value hits this threshold.

- - - - - -

### 25
You are designing a web application that stores static assets in an Amazon Simple Storage Service (S3) bucket. You expect this bucket to immediately receive over 150 PUT requests per second. What should you do to ensure optimal performance?

- [ ] Use multi-part upload.
- [ ] Add a random prefix to the key names.
- [ ] Amazon S3 will automatically manage performance at this scale.
- [ ] Use a predictable naming scheme, such as sequential numbers or date time sequences, in the key names.

- - - - - -

### 26
What does Amazon EC2 provide?

- [ ] Virtual servers in the Cloud.
- [ ] A platform to run code (Java, PHP, Python), paying on an hourly basis.
- [ ] Computer Clusters in the Cloud.
- [ ] Physical servers, remotely managed by the customer.

- - - - - -

### 27
A customer has a single 3-TB volume on-premises that is used to hold a large repository of images and print layout files. This repository is growing at 500 GB a year and must be presented as a single logical volume. The customer is becoming increasingly constrained with their local storage capacity and wants an off-site backup of this data, while maintaining low-latency access to their frequently accessed data. Which AWS Storage Gateway configuration meets the customer requirements?

- [ ] Gateway-Cached volumes with snapshots scheduled to Amazon S3.
- [ ] Gateway-Stored volumes with snapshots scheduled to Amazon S3.
- [ ] Gateway-Virtual Tape Library with snapshots to Amazon S3.
- [ ] Gateway-Virtual Tape Library with snapshots to Amazon Glacier.

- - - - - -

### 28
You are architecting an auto-scalable batch processing system using video processing pipelines and Amazon Simple Queue Service (Amazon SQS) for a customer. You are unsure of the limitations of SQS and need to find out. What do you think is a correct statement about the limitations of Amazon SQS?

- [ ] It supports an unlimited number of queues but a limited number of messages per queue for each user but automatically deletes messages that have been in the queue for more than 4 weeks.
- [ ] It supports an unlimited number of queues and unlimited number of messages per queue for each user but automatically deletes messages that have been in the queue for more than 4 days.
- [ ] It supports an unlimited number of queues but a limited number of messages per queue for each user but automatically deletes messages that have been in the queue for more than 4 days.
- [ ] It supports an unlimited number of queues and unlimited number of messages per queue for each user but automatically deletes messages that have been in the queue for more than 4 weeks.

- - - - - -

### 29
Which Amazon service can I use to define a virtual network that closely resembles a traditional data center?

- [ ] Amazon VPC.
- [ ] Amazon Service Bus.
- [ ] Amazon EMR.
- [ ] Amazon RDS.

- - - - - -

### 30
Select the correct set of options. These are the initial settings for the default security group:

- [ ] Allow no inbound traffic, Allow all outbound traffic and Allow instances associated with this security group to talk to each other.
- [ ] Allow all inbound traffic, Allow no outbound traffic and Allow instances associated with this security group to talk to each other.
- [ ] Allow no inbound traffic, Allow all outbound traffic and Does NOT allow instances associated with this security group to talk to each other.
- [ ] Al low all inbound traffic, Allow all outbound traffic and Does NOT allow instances associated with this security group to talk to each other.

- - - - - -

### 31
You need to migrate a large amount of data into the cloud that you have stored on a hard disk and you decide that the best way to accomplish this is with AWS Import/Export and you mail the hard disk to AWS. Which of the following statements is incorrect in regards to AWS Import/Export?

- [ ] It can export from Amazon S3.
- [ ] It can Import to Amazon Glacier.
- [ ] It can export from Amazon Glacier.
- [ ] It can Import to Amazon EBS.

- - - - - -

### 32
Can I control if and when MySQL based RDS Instance is upgraded to new supported versions?

- [ ] No.
- [ ] Only in VPC.
- [ ] Yes.

- - - - - -

### 33
If I have multiple Read Replicas for my master DB Instance and I promote one of them, what happens to the rest of the Read Replicas?

- [ ] The remaining Read Replicas will still replicate from the older master DB Instance.
- [ ] The remaining Read Replicas will be deleted.
- [ ] The remaining Read Replicas will be combined to one read replica.

- - - - - -

### 34
A user is running a batch process which runs for 1 hour every day. Which of the below mentioned options is the right instance type and costing model in this case if the user performs the same task for the whole year?

- [ ] EBS backed instance with on-demand instance pricing.
- [ ] EBS backed instance with heavy utilized reserved instance pricing.
- [ ] EBS backed instance with low utilized reserved instance pricing.
- [ ] Instance store backed instance with spot instance pricing.

- - - - - -

### 35
You are in the process of building an online gaming site for a client and one of the requirements is that it must be able to process vast amounts of data easily. Which AWS Service would be very helpful in processing all this data?

- [ ] Amazon S3.
- [ ] AWS Data Pipeline.
- [ ] AWS Direct Connect.
- [ ] Amazon EMR.

- - - - - -

### 36
Your team has a tomcat-based Java application you need to deploy into development, test and production environments. After some research, you opt to use Elastic Beanstalk due to its tight integration with your developer tools and RDS due to its ease of management. Your QA team lead points out that you need to roll a sanitized set of production data into your environment on a nightly basis. Similarly, other software teams in your org want access to that same restored data via their EC2 instances in your VPC. The optimal setup for persistence and security that meets the above requirements would be the following:

- [ ] Create your RDS instance as part of your Elastic Beanstalk definition and alter its security group to allow access to it from hosts in your application subnets.
- [ ] Create your RDS instance separately and add its IP address to your application's DB connection strings in your code Alter its security group to allow access to it from hosts within your VPC's IPaddress block.
- [ ] Create your RDS instance separately and pass its DNS name to your app's DB connection string as an environment variable. Create a security group for client machines and add it as a valid source for DB traffic to the security group of the RDS instance itself.
- [ ] Create your RDS instance separately and pass its DNS name to your's DB connection string as an environment variable Alter its security group to allow access to It from hosts in your application subnets.

- - - - - -

### 37
What are characteristics of Amazon S3? (Choose 2 answers)

- [ ] Amazon S3 allows you to store objects of virtually unlimited size.
- [ ] Amazon S3 offers Provisioned IOP.
- [ ] Amazon S3 allows you to store unlimited amounts of data.
- [ ] Amazon S3 should be used to host a relational database.
- [ ] Objects are directly accessible via a URL.

- - - - - -

### 38
You need to set up a complex network infrastructure for your organization that will be reasonably easy to deploy, replicate, control, and track changes on. Which AWS service would be best to use to help you accomplish this?

- [ ] AWS Import/Export.
- [ ] AWS CloudFormation.
- [ ] Amazon Route 53.
- [ ] Amazon CloudWatch.

- - - - - -

### 39
How should the application use AWS credentials to access the S3 bucket securely?

- [ ] Use the AWS account access Keys the application retrieves the credentials from the source code of the application.
- [ ] Create an IAM user for the application with permissions that allow list access to the S3 bucket launch the instance as the IAM user and retrieve the IAM user's credentials from the EC2 instance user data.
- [ ] Create an IAM role for EC2 that allows list access to objects in the S3 bucket. Launch the instance with the role, and retrieve the role's credentials from the EC2 Instance metadata.
- [ ] Create an IAM user for the application with permissions that allow list access to the S3 bucket. The application retrieves the IAM user credentials from a temporary directory with permissions that allow read access only to the application user.

- - - - - -

### 40
You are setting up a VPC and you need to set up a public subnet within that VPC. Which following requirement must be met for this subnet to be considered a public subnet?

- [ ] Subnet's traffic is not routed to an internet gateway but has its traffic routed to a virtual private gateway.
- [ ] Subnet's traffic is routed to an internet gateway.
- [ ] Subnet's traffic is not routed to an internet gateway.
- [ ] None of these answers can be considered a public subnet.

- - - - - -

### 41
Is it possible to access your EBS snapshots?

- [ ] Yes, through the Amazon S3 APIs.
- [ ] Yes, through the Amazon EC2 APIs.
- [ ] No, EBS snapshots cannot be accessed; they can only be used to create a new EBS volume.
- [ ] EBS doesn't provide snapshots.

- - - - - -

### 42
How many types of block devices does Amazon EC2 support?

- [ ] 4.
- [ ] 5.
- [ ] 2.
- [ ] 1.

- - - - - -

### 43
SQL Server [...] store log ins and passwords in the master database.

- [ ] can be configured to but by default does not.
- [ ] doesn't.
- [ ] does.

- - - - - -

### 44
You are using an m1.small EC2 Instance with one 300GB EBS volume to host a relational database. You determined that write throughput to the database needs to be increased. Which of the following approaches can help achieve this? (Choose 2 answers)

- [ ] Use an array of EBS volumes.
- [ ] Enable Multi-AZ mode.
- [ ] Place the instance in an Auto Scaling Groups.
- [ ] Add an EBS volume and place into RAID 5.
- [ ] Increase the size of the EC2 Instance.
- [ ] Put the database behind an Elastic Load Balancer.

- - - - - -

### 45
A user is hosting a website in the US West-1 region. The website has the highest client base from the Asia-Pacific (Singapore / Japan) region. The application is accessing data from S3 before serving it to client. Which of the below mentioned regions gives a better performance for S3 objects?

- [ ] Japan.
- [ ] Singapore.
- [ ] US East.
- [ ] US West-1.

- - - - - -

### 46
You need to set up security for your VPC and you know that Amazon VPC provides two features that you can use to increase security for your VPC: Security groups and network access control lists (ACLs). You start to look into security groups first. Which statement below is incorrect in relation to security groups?

- [ ] Are stateful: Return traffic is automatically allowed, regardless of any rules.
- [ ] Evaluate all rules before deciding whether to allow traffic.
- [ ] Support allow rules and deny rules.
- [ ] Operate at the instance level (first layer of defense).

- - - - - -

### 47
Can a single EBS volume be attached to multiple EC2 instances at the same time?

- [ ] Yes.
- [ ] No.
- [ ] Only for high-performance EBS volumes.
- [ ] Only when the instances are located in the US regions.

- - - - - -

### 48
You are planning and configuring some EBS volumes for an application. in order to get the most performance out of your EBS volumes, you should attach them to an instance with enough [...] to support your volumes.

- [ ] redundancy.
- [ ] storage.
- [ ] bandwidth.
- [ ] memory.

- - - - - -

### 49
An organization has three separate AWS accounts, one each for development, testing, and production. The organization wants the testing team to have access to certain AWS resources in the production account. How can the organization achieve this?

- [ ] It is not possible to access resources of one account with another account.
- [ ] Create the IAM roles with cross account access.
- [ ] Create the IAM user in a test account, and allow it access to the production environment with the IAM policy.
- [ ] Create the IAM users with cross account access.

- - - - - -

### 50
A benefits enrollment company is hosting a 3-tier web application running in a VPC on AWS which includes a NAT (Network Address Translation) instance in the public Web tier. There is enough provisioned capacity for the expected workload tor the new fiscal year benefit enrollment period plus some extra overhead Enrollment proceeds nicely for two days and then the web tier becomes unresponsive, upon investigation using CloudWatch and other monitoring tools it is discovered that there is an extremely large and unanticipated amount of inbound traffic coming from a set of 15specific IP addresses over port 80 from a country where the benefits company has no customers. The web tier instances are so overloaded that benefit enrollment administrators cannot even SSH into them. Which activity would be useful in defending against this attack?

- [ ] Create a custom route table associated with the web tier and block the attacking IP addresses from the IGW (Internet Gateway).
- [ ] Change the EIP (Elastic IP Address) of the NAT instance in the web tier subnet and update the Main Route Table with the new EIP.
- [ ] Create 15 Security Group rules to block the attacking IP addresses over port 80.
- [ ] Create an inbound NACL (Network Access control list) associated with the web tier subnet with deny rules to block the attacking IP addresses.

- - - - - -

