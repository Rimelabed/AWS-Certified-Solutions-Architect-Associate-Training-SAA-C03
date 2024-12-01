### 1
A user is sending bulk emails using AWS SES. The emails are not reaching some of the targeted audience because they are not authorized by the ISPs. How can the user ensure that the emails are all delivered?

- [x] Send an email using DKIM with SE.
- [ ] Send an email using SMTP with SE.
- [ ] Open a ticket with AWS support to get it authorized with the IS.
- [ ] Authorize the ISP by sending emails from the development account.

- - - - - -

### 2
What's an ECU?

- [ ] Extended Cluster User.
- [ ] None of these.
- [ ] Elastic Computer Usage.
- [x] Elastic Compute Unit.

- - - - - -

### 3
You would like to create a mirror image of your production environment in another region for disaster recovery purposes. Which of the following AWS resources do not need to be recreated in the second region? (Choose 2 answers)

- [x] Route 53 Record Sets.
- [x] IAM Roles.
- [ ] Elastic IP Addresses (EIP).
- [ ] EC2 Key Pairs.
- [ ] Launch configurations.
- [ ] Security Groups.

- - - - - -

### 4
Which procedure for backing up a relational database on EC2 that is using a set of RAIDed EBS volumes for storage minimizes the time during which the database cannot be written to and results in a consistent backup?

- [x] 1. Detach EBS volumes, 2. Start EBS snapshot of volumes, 3. Re-attach EBS volumes.
- [ ] 1. Stop the EC2 Instance. 2. Snapshot the EBS volumes.
- [ ] 1. Suspend disk 1/0, 2. Create an image of the EC2 Instance, 3. Resume disk 1/0.
- [ ] 1. Suspend disk 1/0, 2. Start EBS snapshot of volumes, 3. Resume disk 1/0.
- [ ] 1. Suspend disk 1/0, 2. Start EBS snapshot of volumes, 3. Wait for snapshots to complete, 4. Resume disk 1/0.

- - - - - -

### 5
My Read Replica appears 'stuck' after a Multi-AZ failover and is unable to obtain or apply updates from the source DB Instance. What do I do?

- [x] You will need to delete the Read Replica and create a new one to rep lace it.
- [ ] You will need to disassociate the DB Engine and re associate it.
- [ ] The instance should be deployed to Single AZ and then moved to Multi-AZ once again.
- [ ] You will need to delete the DB Instance and create a new one to replace it.

- - - - - -

### 6
You are setting up some IAM user policies and have also become aware that some services support resource-based permissions, which let you attach policies to the service's resources instead of to IAM users or groups. Which of the below statements is true in regards to resource-level permissions?

- [ ] All services support resource-level permissions for all actions.
- [ ] Resource-level permissions are supported by Amazon CloudFront.
- [ ] All services support resource-level permissions only for some actions.
- [x] Some services support resource-level permissions only for some actions.

- - - - - -

### 7
You have some very sensitive data stored on AWS S3 and want to try every possible alternative to keeping it secure in regards to access control. What are the mechanisms available for access control on AWS S3?

- [x] (IAM) policies, Access Control Lists (ACLs), bucket policies, and query string authentication.
- [ ] (IAM) policies, Access Control Lists (ACLs) and bucket policies.
- [ ] Access Control Lists (ACLs), bucket policies, and query string authentication.
- [ ] (IAM) policies, Access Control Lists (ACLs), bucket policies, query string authentication and encryption.

- - - - - -

### 8
You are implementing AWS Direct Connect. You intend to use AWS public service end points such as Amazon S3, across the AWS Direct Connect link. You want other Internet traffic to use your existing link to an Internet Service Provider. What is the correct way to configure AWS Direct connect for access to services such as Amazon S3?

- [ ] Configure a public Interface on your AWS Direct Connect link. Configure a static route via your AWS Direct Connect link that points to Amazon S3 Advertise a default route to AWS using BGP.
- [ ] Create a private interface on your AWS Direct Connect link. Configure a static route via your AWS Direct connect link that points to Amazon S3 Configure specific routes to your network in your VPC.
- [x] Create a public interface on your AWS Direct Connect link. Redistribute BGP routes into your existing routing infrastructure; advertise specific routes for your network to AWS.
- [ ] Create a private interface on your AWS Direct connect link. Redistribute BGP routes into your existing routing infrastructure and advertise a default route to AWS.

- - - - - -

### 9
You are setting up your first Amazon Virtual Private Cloud (Amazon VPC) network so you decide you should probably use the AWS Management Console and the VPC Wizard. Which of the following is not an option for network architectures after launching the 'Start VPC Wizard' in Amazon VPC page on the AWS Management Console?

- [ ] VPC with a Single Public Subnet Only.
- [x] VPC with a Public Subnet Only and Hardware VPN Access.
- [ ] VPC with Public and Private Subnets and Hardware VPN Access.
- [ ] VPC with a Private Subnet Only and Hardware VPN Access.

- - - - - -

### 10
True or False: A VPC contains multiple subnets, where each subnet can span multiple Availability Zones.

- [ ] This is true only if requested during the set-up of VPC.
- [x] This is true.
- [ ] This is false.
- [ ] This is true only for US regions.

- - - - - -

### 11
Amazon RDS automated backups and DB Snapshots are currently supported for only the [...] storage engine.

- [x] InnoDB.
- [ ] MyISAM.

- - - - - -

### 12
While signing in REST/ Query requests, for additional security, you should transmit your requests using Secure Sockets Layer (SSL) by using [...].

- [ ] HTTP.
- [ ] Internet Protocol Security (IPsec).
- [ ] TLS (Transport Layer Security).
- [x] HTTPS.

- - - - - -

### 13
Out of the stripping options available for the EBS volumes, which one has the following disadvantage: 'Doubles the amount of 1/0 required from the instance to EBS compared to RAID 0, because you're mirroring all writes to a pair of volumes, limiting how much you can stripe.'?

- [ ] Raid 0.
- [x] RAID 1+0 (RAID 10).
- [ ] Raid 1.
- [ ] Raid.

- - - - - -

### 14
Can I encrypt connections between my application and my DB Instance using SSL?

- [x] Yes.
- [ ] Only in VPC.
- [ ] Only in certain regions.

- - - - - -

### 15
Which of the following items are required to allow an application deployed on an EC2 instance to write data to a DynamoDB table? Assume that no security keys are allowed to be stored on the EC2 instance. (Choose 3 answers)

- [x] Create an IAM Role that allows write access to the DynamoDB table.
- [x] Add an IAM Role to a running EC2 instance.
- [ ] Create an IAM User that al lows write access to the Dynamo DB table.
- [ ] Add an IAM User to a running EC2 instance.
- [x] Launch an EC2 Instance with the IAM Role included in the launch configuration.

- - - - - -

### 16
Identify a true statement about the On-Demand instances purchasing option provided by Amazon EC2.

- [x] Pay for the instances that you use by the hour, with no long-term commitments or up-front payments.
- [ ] Make a low, one-time, up-front payment for an instance, reserve it for a one- or three-year term, and pay a significantly lower hourly rate for these instances.
- [ ] Pay for the instances that you use by the hour, with long-term commitments or up-front payments.
- [ ] Make a high, one-time, all-front payment for an instance, reserve it for a one- or three-year term, and pay a significantly higher hourly rate for these instances.

- - - - - -

### 17
When will you incur costs with an Elastic IP address (EIP)?

- [ ] When an EIP is allocated.
- [ ] When it is allocated and associated with a running instance.
- [ ] When it is allocated and associated with a stopped instance.
- [x] Costs are incurred regardless of whether the ElP is associated with a running instance.

- - - - - -

### 18
IAM provides several policy templates you can use to automatically assign permissions to the groups you create. The [...] policy template gives the Admins group permission to access all account resources, except your AWS account information.

- [ ] Read Only Access.
- [ ] Power User Access.
- [ ] AWS Cloud Formation Read Only Access.
- [x] Administrator Access.

- - - - - -

### 19
What does RRS stand for when talking about S3?

- [ ] Redundancy Removal System.
- [ ] Relational Rights Storage.
- [ ] Regional Rights Standard.
- [x] Reduced Redundancy Storage.

- - - - - -

### 20
Can I change the EC2 security groups after an instance is launched in EC2-Classic?

- [ ] Yes, you can change security groups after you launch an instance in EC2-Classic.
- [x] No, you cannot change security groups after you launch an instance in EC2-Classic.
- [ ] Yes, you can only when you remove rules from a security group.
- [ ] Yes, you can only when you add rules to a security group.

- - - - - -

### 21
Please select the Amazon EC2 resource which cannot be tagged.

- [ ] Images (AMIs, kernels, RAM disks).
- [ ] Amazon EBS volumes.
- [x] Elastic IP addresses.
- [ ] VPCs.

- - - - - -

### 22
Does Route 53 support MX Records?

- [x] Yes.
- [ ] It supports CNAME records, but not MX records.
- [ ] No.
- [ ] Only Primary MX records. Secondary MX records are not supported.

- - - - - -

### 23
Which of the following notification endpoints or clients are supported by Amazon Simple Notification Service? (Choose 2 answers)

- [x] Email.
- [ ] CloudFront distribution.
- [ ] File Transfer Protocol.
- [x] Short Message Service.
- [ ] Simple Network Management Protocol.

- - - - - -

### 24
AWS Identity and Access Management is a web service that enables Amazon Web Services (AWS) customers to manage users and user permissions in AWS. In addition to supporting IAM user policies, some services support resource-based permissions. Which of the following services are supported by resource-based permissions?

- [ ] Amazon SNS, and Amazon SQS and AWS Direct Connect.
- [ ] Amazon S3 and Amazon SQS and Amazon ElastiCache.
- [x] Amazon S3, Amazon SNS, Amazon SQS, Amazon Glacier and Amazon EB
- [ ] Amazon Glacier, Amazon SNS, and Amazon CloudWatch.

- - - - - -

### 25
What does the following policy for Amazon EC2 do? { 'Statement':[{ 'Effect': 'Allow', 'Action':'ec2: Describe*', 'Resource':'*' }] }

- [x] Allow users to use actions that start with 'Describe' over all the EC2 resources.
- [ ] Share an AMI with a partner.
- [ ] Share an AMI within the account.
- [ ] Allow a group to only be able to describe, run, stop, start, and terminate instances.

- - - - - -

### 26
Which IAM role do you use to grant AWS Lambda permission to access a DynamoDB Stream?

- [ ] Dynamic role.
- [ ] Invocation role.
- [x] Execution role.
- [ ] Event Source role.

- - - - - -

### 27
Can resource record sets in a hosted zone have a different domain suffix (for example, <www.blog>. acme.com and <www.acme.ca>)?

- [ ] Yes, it can have for a maximum of three different TLDs.
- [ ] Yes.
- [x] Yes, it can have depending on the TL.
- [ ] No.

- - - - - -

### 28
In Amazon Elastic Compute Cloud, which of the following is used for communication between instances in the same network (EC2-Classic or a VPC)?

- [x] Private IP addresses.
- [ ] Elastic IP addresses.
- [ ] Static IP addresses.
- [ ] Public IP addresses.

- - - - - -

### 29
A user is planning to host a mobile game on EC2 which sends notifications to active users on either high score or the addition of new features. The user should get this notification when he is online on his mobile device. Which of the below mentioned AWS services can help achieve this functionality?

- [x] AWS Simple Notification Service.
- [ ] AWS Simple Email Service.
- [ ] AWS Mobile Communication Service.
- [ ] AWS Simple Queue Service.

- - - - - -

### 30
You need to create an Amazon Machine Image (AMI) for a customer for an application which does not appear to be part of the standard AWS AMI template that you can see in the AWS console. What are the alternative possibilities for creating an AMI on AWS?

- [ ] You can purchase an AMIs from a third party but cannot create your own AMI.
- [x] You can purchase an AMIs from a third party or can create your own AMI.
- [ ] Only AWS can create AMIs and you need to wait till it becomes available.
- [ ] Only AWS can create AMIs and you need to request them to create one for you.

- - - - - -

### 31
Will I be charged if the DB instance is idle?

- [x] Yes.
- [ ] Only is running in GovCloud.
- [ ] Only if running in VPC.

- - - - - -

### 32
Your company has been storing a lot of data in Amazon Glacier and has asked for an inventory of what is in there exactly. So you have decided that you need to download a vault inventory. Which of the following statements is incorrect in relation to Vault Operations in Amazon Glacier?

- [ ] You can use Amazon Simple Notification Service (Amazon SNS) notifications to notify you when the job completes.
- [ ] A vault inventory refers to the list of archives in a vault.
- [x] You can use Amazon Simple Queue Service (Amazon SQS) notifications to notify you when the job completes.
- [ ] Downloading a vault inventory is an asynchronous operation.

- - - - - -

### 33
Your fortune 500 company has under taken a TCO analysis evaluating the use of Amazon S3 versus acquiring more hardware The outcome was that ail employees would be granted access to use Amazon S3 for storage of their personal documents. Which of the following will you need to consider so you can set up a solution that incorporates single sign-on from your corporate AD or LDAP directory and restricts access for each user to a designated user folder in a bucket? (Choose 3 answers)

- [x] Setting up a federation proxy or identity provider.
- [x] Using AWS Security Token Service to generate temporary tokens.
- [ ] Tagging each folder in the bucket.
- [x] Configuring IAM role.
- [ ] Setting up a matching IAM user for every user in your corporate directory that needs access to a folder in the bucket.

- - - - - -

### 34
Your company policies require encryption of sensitive data at rest. You are considering the possible options for protecting data while storing it at rest on an EBS data volume, attached to an EC2 instance. Which of these options would allow you to encrypt your data at rest? (Choose 3 answers)

- [x] Implement third party volume encryption tools.
- [ ] Do nothing as EBS volumes are encrypted by default.
- [x] Encrypt data inside your applications before storing it on EBS.
- [x] Encrypt data using native data encryption drivers at the file system level.
- [ ] Implement SSL/TLS for all services running on the server.

- - - - - -

### 35
A scope has been handed to you to set up a super fast gaming server and you decide that you will use Amazon DynamoDB as your database. For efficient access to data in a table, Amazon DynamoDB creates and maintains indexes for the primary key attributes. A secondary index is a data structure that contains a subset of attributes from a table, along with an alternate key to support Query operations. How many types of secondary indexes does DynamoDB support?

- [x] 2.
- [ ] 16.
- [ ] 4.
- [ ] As many as you need.

- - - - - -

### 36
True or False: in Amazon Route 53, you can create a hosted zone for a top-level domain (TLD).

- [x] False.
- [ ] False, Amazon Route 53 automatically creates it for you.
- [ ] True, only if you send an XML document with a CreateHostedZoneRequest element for TLD.
- [ ] True.

- - - - - -

### 37
You want to use AWS Import/Export to send data from your S3 bucket to several of your branch offices. What should you do if you want to send 10 storage units to AWS?

- [ ] Make sure your disks are encrypted prior to shipping.
- [ ] Make sure you format your disks prior to shipping.
- [ ] Make sure your disks are 1TB or more.
- [x] Make sure you submit a separate job request for each device.

- - - - - -

### 38
You are deploying an application to track GPS coordinates of delivery trucks in the United States. Coordinates are transmitted from each delivery t ruck once every three seconds. You need to design an architecture that will enable real-time processing of these coordinates from multiple consumers. Which service should you use to implement data ingestion?

- [x] Amazon Kinesis.
- [ ] AWS Data Pipeline.
- [ ] Amazon AppStream.
- [ ] Amazon Simple Queue Service.

- - - - - -

### 39
While performing the volume status checks, if the status is insufficient-data, what does it mean?

- [x] The checks may still be in progress on the volume.
- [ ] The check has passed.
- [ ] The check has failed.

- - - - - -

### 40
Can you create IAM security credentials for existing users?

- [x] Yes, existing users can have security credentials associated with their account.
- [ ] No, IAM requires that all users who have credentials set up are not existing users.
- [ ] No, security credentials are created within GROUPS, and then users are associated to GROUPS at a later time.
- [ ] Yes, but only IAM credentials, not ordinary security credentials.

- - - - - -

### 41
Can I move a Reserved Instance from one Region to another?

- [x] No.
- [ ] Only if they are moving into GovCloud.
- [ ] Yes.
- [ ] Only if they are moving to US East from another region.

- - - - - -

### 42
A user has created an ELB with the Availability Zone US-East-1A. The user wants to add more zones to ELB to achieve High Availability. How can the user add more zones to the existing ELB?

- [ ] The user should stop the ELB and add zones and instances as required.
- [ ] The only option is to launch instances in different zones and add to ELB.
- [ ] It is not possible to add more zones to the existing ELB.
- [x] The user can add zones on the fly from the AWS console.

- - - - - -

### 43
Amazon SWF is designed to help users …

- [ ] Design graphical user interface interactions.
- [ ] Manage user identification and authorization.
- [ ] Store Web content.
- [x] Coordinate synchronous and asynchronous tasks which are distributed and fault tolerant.

- - - - - -

### 44
Which technique can be used to integrate AWS IAM (Identity and Access Management) with an on-premise LDAP (Lightweight Directory Access Protocol) directory service?

- [ ] Use an IAM policy that references the LDAP account identifiers and the AWS credentials.
- [x] Use SAML (Security Assertion Markup Language) to enable single sign-on between AWS and LDAP.
- [ ] Use AWS Security Token Service from an identity broker to issue short-lived AWS credentials.
- [ ] Use IAM roles to automatically rotate the IAM credentials when LDAP credentials are updated.
- [ ] Use the LDAP credentials to restrict a group of users from launching specific EC2 instance types.

- - - - - -

### 45
You are building a solution for a customer to extend their on-premises data center to AWS. The customer requires a 50-Mbps dedicated and private connection to their VPC. Which AWS product or feature satisfies this requirement?

- [ ] Amazon VPC peering.
- [ ] Elastic IP Addresses.
- [x] AWS Direct Connect.
- [ ] Amazon VPC virtual private gateway.

- - - - - -

### 46
A customer wants to leverage Amazon Simple Storage Service (S3) and Amazon Glacier as part of their backup and archive infrastructure. The customer plans to use third-party software to support this integration. Which approach will limit the access of the third party software to only the Amazon S3 bucket named 'company-backup'?

- [ ] A custom bucket policy limited to the Amazon S3 API in the Amazon Glacier archive 'company backup'.
- [ ] A custom bucket policy limited to the Amazon S3 API in 'company-backup'.
- [ ] A custom IAM user policy limited to the Amazon S3 API for the Amazon Glacier archive 'company backup'.
- [x] A custom IAM user policy limited to the Amazon S3 API in 'company-backup'.

- - - - - -

### 47
A user needs to run a batch process which runs for 10 minutes. This will only be run once, or at maximum twice, in the next month, so the processes will be temporary only. The process needs 15 X-Large instances. The process downloads the code from S3 on each instance when it is launched, and then generates a temporary log file. Once the instance is terminated, all the data will be lost. Which of the below mentioned pricing models should the user choose in this case?

- [x] Spot instance.
- [ ] Reserved instance.
- [ ] On-demand instance.
- [ ] EBS optimized instance.

- - - - - -

### 48
You have been doing a lot of testing of your VPC Network by deliberately failing EC2 instances to test whether instances are failing over properly. Your customer who will be paying the AWS bill for all this asks you if he being charged for all these instances. You try to explain to him how the billing works on EC2 instances to the best of your knowledge. What would be an appropriate response to give to the customer in regards to this?

- [ ] Billing commences when Amazon EC2 AMI instance is completely up and billing ends as soon as the instance starts to shutdown.
- [ ] Billing only commences only after 1 hour of uptime and billing ends when the instance terminates.
- [x] Billing commences when Amazon EC2 initiates the boot sequence of an AMI instance and billing ends when the instance shuts down.
- [ ] Billing commences when Amazon EC2 initiates the boot sequence of an AMI instance and billing ends as soon as the instance starts to shutdown.

- - - - - -

### 49
Refer to the architecture diagram above of a batch processing solution using Simple Queue Service (SQS) to set up a message queue between EC2 instances which are used as batch processors Cloud Watch monitors the number of Job requests (queued messages) and an Auto Scaling group adds or deletes batch servers automatically based on parameters set in Cloud Watch alarms. You can use this architecture to implement which of the following features in a cost effective and efficient manner?

![Question 563](images/question563.jpg)

- [ ] Reduce the overall lime for executing jobs through parallel processing by allowing a busy EC2 instance that receives a message to pass it to the next instance in a daisy-chain setup.
- [ ] Implement fault tolerance against EC2 instance failure since messages would remain in SQS and worn can continue with recovery of EC2 instances implement fault tolerance against SQS failure by backing up messages to S3.
- [x] Implement message passing between EC2 instances within a batch by exchanging messages through SQS.
- [ ] Coordinate number of EC2 instances with number of job requests automatically thus Improving cost effectiveness.
- [ ] Handle high priority jobs before lower priority jobs by assigning a priority metadata fie ld to SQS messages.

- - - - - -

### 50
You are migrating an internal server on your DC to an EC2 instance with EBS volume. Your server disk usage is around 500GB so you just copied all your data to a 2TB disk to be used with AWS Import/Export. Where will the data be imported once it arrives at Amazon?

- [ ] To a 2TB EBS volume.
- [x] To an S3 bucket with 2 objects of 1TB.
- [ ] To an 500GB EBS volume.
- [ ] To an S3 bucket as a 2TB snapshot.

- - - - - -

