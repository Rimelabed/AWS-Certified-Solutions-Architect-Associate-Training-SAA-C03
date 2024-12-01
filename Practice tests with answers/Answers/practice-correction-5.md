### 1
Changes to the backup window take effect [...].

- [ ] from the next billing cycle.
- [ ] after 30 minutes.
- [x] immediately.
- [ ] after 24 hours.

- - - - - -

### 2
Location of Instances are [...].

- [ ] regional.
- [x] based on Availability Zone.
- [ ] global.

- - - - - -

### 3
You log in to IAM on your AWS console and notice the following message. 'Delete your root access keys.' Why do you think IAM is requesting this?

- [ ] Because the root access keys will expire as soon as you log out.
- [ ] Because the root access keys expire after 1 week.
- [ ] Because the root access keys are the same for all users.
- [x] Because they provide unrestricted access to your AWS resources.

- - - - - -

### 4
What is the minimum charge for the data transferred between Amazon RDS and Amazon EC2 Instances in the same Availability Zone?

- [ ] USD 0.10 per GB.
- [x] No charge. It is free.
- [ ] USD 0.02 per GB
- [ ] USD 0.01 per GB.

- - - - - -

### 5
In DynamoDB, could you use IAM to grant access to Amazon DynamoDB resources and API actions?

- [ ] In DynamoDB there is no need to grant access.
- [ ] Depended to the type of access.
- [x] Yes.
- [ ] No.

- - - - - -

### 6
The common use cases for DynamoDB Fine-Grained Access Control (FGAC) are cases in which the end user wants [...].

- [ ] to change the hash keys of the table directly.
- [ ] to check if an IAM policy requires the hash keys of the tables directly.
- [ ] to read or modify any code commit key of the table directly, without a middle-tier service.
- [x] to read or modify the table directly, without a middle-tier service.

- - - - - -

### 7
What are the initial settings of an user created security group?

- [ ] Allow all inbound traffic and Allow no outbound traffic.
- [ ] Al low no inbound traffic and Al low no outbound traffic.
- [x] Al low no inbound traffic and Al low all outbound traffic.
- [ ] Allow all inbound traffic and Allow all outbound traffic.

- - - - - -

### 8
Which one of the following answers is not a possible state of Amazon CloudWatch Alarm?

- [ ] INSUFFICIENT_DATA.
- [ ] ALARM.
- [ ] OK.
- [x] STATUS_CHECK_FAILED.

- - - - - -

### 9
[...] let you categorize your EC2 resources in different ways, for example, by purpose, owner, or environment.

- [ ] wildcards.
- [ ] pointers.
- [x] tags.
- [ ] special filters.

- - - - - -

### 10
Which of the below mentioned options is not available when an instance is launched by Auto Scaling with EC2 Classic?

- [ ] Public IP.
- [x] Elastic IP.
- [ ] Private DNS.
- [ ] Private IP.

- - - - - -

### 11
You have a lot of data stored in the AWS Storage Gateway and your manager has come to you asking about how the billing is calculated, specifically the Virtual Tape Shelf usage. What would be a correct response to this?

- [ ] You are billed for the virtual tape data you store in Amazon Glacier and are billed for the size of the virtual tape.
- [x] You are billed for the virtual tape data you store in Amazon Glacier and billed for the portion of virtual tape capacity that you use, not for the size of the virtual tape.
- [ ] You are billed for the virtual tape data you store in Amazon S3 and billed for the portion of virtual tape capacity that you use, not for the size of the virtual tape.
- [ ] You are billed for the virtual tape data you store in Amazon S3 and are billed for the size of the virtual tape.

- - - - - -

### 12
True or False: The new DB Instance that is created when you promote a Read Replica retains the backup window period.

- [x] True.
- [ ] False.

- - - - - -

### 13
[...] is a fast, flexible, fully managed push messaging service.

- [x] Amazon SNS.
- [ ] Amazon SES.
- [ ] Amazon SQS.
- [ ] Amazon FPS.

- - - - - -

### 14
You are tasked with setting up a Linux bastion host for access to Amazon EC2 instances running in your VPC. Only clients connecting from the corporate external public IP address 72.34.51.100 should have SSH access to the host. Which option will meet the customer requirement?

- [x] Security Group Inbound Rule: Protocol – TCP. Port Range – 22, Source 72.34.51.100/32
- [ ] Port Range- 22, Source 72.34.51. 100/32.
- [ ] Security Group Inbound Rule: Protocol – UDP, Port Range- 22, Source 72.34.51.100/32.
- [ ] Network ACL Inbound Rule: Protocol – UDP, Port Range- 22, Source 72.34.51.100/32.
- [ ] Network ACL Inbound Rule: Protocol – TCP, Port Range-22, Source 72.34.51.100/0.

- - - - - -

### 15
How can you secure data at rest on an EBS volume?

- [ ] Attach the volume to an instance using EC2's SSL interface.
- [ ] Write the data randomly instead of sequentially.
- [ ] Encrypt the volume using the S3 server-side encryption service.
- [ ] Create an IAM policy that restricts read and write access to the volume.
- [x] Use an encrypted file system on top of the EBS volume.

- - - - - -

### 16
Is there a method in the IAM system to allow or deny access to a specific instance?

- [ ] Only for VPC based instances.
- [x] Yes.
- [ ] No.

- - - - - -

### 17
Using Amazon IAM, can I give permission based on organizational groups?

- [ ] Yes but only in certain cases.
- [x] Yes.
- [ ] No.

- - - - - -

### 18
Which services allow the customer to retain full administrative privileges of the underlying EC2 instances? (Choose 2 answers)

- [ ] Amazon Relational Database Service.
- [x] Amazon Elastic MapReduce.
- [ ] Amazon ElastiCache.
- [ ] Amazon DynamoDB.
- [x] AWS Elastic Beanstalk.

- - - - - -

### 19
While launching an RDS DB instance, on which page I can select the Availability Zone?

- [ ] REVIEW.
- [ ] DB INSTANCE DETAILS.
- [ ] MANAGEMENT OPTIONS.
- [x] ADDITIONAL CONFIGURATION.

- - - - - -

### 20
You are responsible for a legacy web application whose server environment is approaching end of life. You would like to migrate this application to AWS as quickly as possible, since the application environment currently has the following limitations. The VM's single 10GB VMDK is almost full Me virtual network interface still uses the 10Mbps driver, which leaves your 100Mbps WAN connection completely underutilized. It is currently running on a highly customized. Windows VM within a VMware environment: You do not have me installation media. This is a mission critical application with an RTO (Recovery Time Objective) of 8 hours. RPO (Recovery Point Objective) of 1 hour. How could you best migrate this application to AWS while meeting your business continuity requirements?

- [x] Use the EC2 VM Import Connector for vCenter to import the VM into EC2.
- [ ] Use Import/Export to import the VM as an ESS snapshot and attach to EC2.
- [ ] Use S3 to create a backup of the VM and restore the data into EC2.
- [ ] Use me ec2-bundle-instance API to Import an Image of the VM into EC2.

- - - - - -

### 21
You are setting up some EBS volumes for a customer who has requested a setup which includes a RAID (redundant array of inexpensive disks). AWS has some recommendations for RAID setups. Which RAID setup is not recommended for Amazon EBS?

- [ ] RAID 5 only.
- [x] RAID 5 and RAID 6.
- [ ] RAID 1 only.
- [ ] RAID 1 and RAID 6.

- - - - - -

### 22
Much of your company's data does not need to be accessed often, and can take several hours for retrieval time, so it's stored on Amazon Glacier. However someone within your organization has expressed concerns that his data is more sensitive than the other data, and is wondering whether the high level of encryption that he knows is on S3 is also used on the much cheaper Glacier service. Which of the following statements would be most applicable in regards to this concern?

- [ ] There is no encryption on Amazon Glacier, that's why it is cheaper.
- [ ] Amazon Glacier automatically encrypts the data using AES-128 a lesser encryption method than Amazon S3 but you can change it to AES-256 if you are willing to pay more.
- [x] Amazon Glacier automatically encrypts the data using AES-256, the same as Amazon S3.
- [ ] Amazon Glacier automatically encrypts the data using AES-128 a lesser encryption method than Amazon S3.

- - - - - -

### 23
Can I use Provisioned IOPS with VPC?

- [ ] Only Oracle based RDS.
- [ ] No.
- [ ] Only with MSSQL based RDS.
- [x] Yes for all RDS instances.

- - - - - -

### 24
To ensure failover capabilities, consider using a [...] for incoming traffic on a network interface.

- [ ] primary public IP.
- [x] secondary private IP.
- [ ] secondary public IP.
- [ ] add on secondary IP.

- - - - - -

### 25
By default, EBS volumes that are created and attached to an instance at launch are deleted when that instance is terminated. You can modify this behavior by changing the value of the flag [...] to false when you launch the instance.

- [x] Delete On Termination.
- [ ] Remove On Deletion.
- [ ] Remove On Termination.
- [ ] Terminate On Deletion.

- - - - - -

### 26
Which AWS service helps this functionality?

- [x] AWS Simple Queue Service.
- [ ] AWS Simple Notification Service.
- [ ] AWS Simple Workflow Service.
- [ ] AWS Simple Email Service.

- - - - - -

### 27
Which of the below statements would be an incorrect response to your customers enquiry?

- [ ] Amazon EMR customers can choose to send data to Amazon S3 using the HTTPS protocol for secure transmission.
- [ ] Amazon S3 provides authentication mechanisms to ensure that stored data is secured against unauthorized access.
- [x] Every packet sent in the AWS network uses Internet Protocol Security (IPsec).
- [ ] Customers may encrypt the input data before they upload it to Amazon S3.

- - - - - -

### 28
The one-time payment for Reserved Instances is [...] refundable if the reservation is cancelled.

- [ ] always.
- [ ] in some circumstances.
- [x] never.

- - - - - -

### 29
Is it possible to get a history of all EC2 API calls made on your account for security analysis and operational troubleshooting purposes?

- [ ] Yes, by default, the history of your API calls is logged.
- [x] Yes, you should turn on the CloudTrail in the AWS console.
- [ ] No, you can only get a history of VPC API calls.
- [ ] No, you cannot store history of EC2 API calls on Amazon.

- - - - - -

### 30
The Trusted Advisor service provides insight regarding which four categories of an AWS account?

- [ ] Security, fault tolerance, high availability, and connectivity.
- [ ] Security, access control, high availability, and performance.
- [x] Performance, cost optimization, security, and fault tolerance.
- [ ] Performance, cost optimization, access control, and connectivity.

- - - - - -

### 31
An AWS customer runs a public blogging website. The site users upload two million blog entries a month. The average blog entry size is 200 KB. The access rate to blog entries drops to negligible 6 months after publication and users rarely access a blog entry 1 year after publication. Additionally, blog entries have a high update rate during the first 3 months following publication, this drops to no updates after 6 months. The customer wants to use CloudFront to improve his user's load times. Which of the following recommendations would you make to the customer?

- [ ] Duplicate entries into two different buckets and create two separate CloudFront distributions where S3 access is restricted only to CloudFront identity.
- [ ] Create a CloudFront distribution with 'US' Europe price class for US/ Europe users and a different CloudFront distribution with Al l Edge Locations' for the remaining users.
- [x] Create a CloudFront distribution with S3 access restricted only to the CloudFront identity and partition the blog entry's location in S3 according to the month it was uploaded to be used withCloudFront behaviors.
- [ ] Create a CloudFronl distribution with Restrict Viewer Access Forward Query string set to true and minimum TTL of 0.

- - - - - -

### 32
Your supervisor has asked you to build a simple file synchronization service for your department. He doesn't want to spend too much money and he wants to be notified of any changes to files by email. What do you think would be the best Amazon service to use for the email solution?

- [x] Amazon SES.
- [ ] Amazon CloudSearch.
- [ ] Amazon SWF.
- [ ] Amazon AppStream.

- - - - - -

### 33
What are the Amazon EC2 API tools?

- [ ] They don't exist. The Amazon EC2 AMI tools, instead, are used to manage permissions.
- [x] Command-line tools to the Amazon EC2 web service.
- [ ] They are a set of graphical tools to manage EC2 instances.
- [ ] They don't exist. The Amazon API tools are a client interface to Amazon Web Services.

- - - - - -

### 34
Your customer wishes to deploy an enterprise application to AWS which will consist of several web servers, several application servers and a small (50GB) Oracle database information is stored, both in the database and the file systems of the various servers. The backup system must support database recovery whole server and whole disk restores, and individual file restores with a recovery time of no more than two hours. They have chosen to use RDS Oracle as the database. Which backup architecture will meet these requirements?

- [x] Backup RDS using automated daily DB backups Backup the EC2 instances using AMIs and supplement with file-level backup to S3 using traditional enterprise backup software to provide file level restore.
- [ ] Backup RDS using a Multi-AZ Deployment Backup the EC2 instances using Amis, and supplement by copying file system data to S3 to provide file-level restore.
- [ ] Backup RDS using automated daily DB backups Backup the EC2 instances using EBS snapshots and supplement with file-level backups to Amazon Glacier using traditional enterprise backup software to provide file-level restore.
- [ ] Backup RDS database to S3 using Oracle RMAN Backup the EC2 instances using Amis, and supplement with EBS snapshots for individual volume restore.

- - - - - -

### 35
You are architecting a highly-scalable and reliable web application which will have a huge amount of content. You have decided to use Cloudfront as you know it will speed up distribution of your static and dynamic web content and know that Amazon CloudFront integrates with Amazon CloudWatch metrics so that you can monitor your web application. Because you live in Sydney you have chosen the the Asia Pacific (Sydney) region in the AWS console. However you have set up this up but no CloudFront metrics seem to be appearing in the CloudWatch console. What is the most likely reason from the possible choices below for this?

- [ ] Metrics for CloudWatch are available only when you choose the same region as the application you are monitoring.
- [ ] You need to pay for CloudWatch for it to become active.
- [x] Metrics for CloudWatch are available only when you choose the US East (Virginia).
- [ ] Metrics for CloudWatch are not available for the Asia Pacific region as yet.

- - - - - -

### 36
Is the SQL Server Audit feature supported in the Amazon RDS SQL Server engine?

- [ ] Yes.
- [x] No.

- - - - - -

### 37
What is the command line instruction for running the remote desktop client in Windows?

- [ ] desk.cpl.
- [x] mstsc.

- - - - - -

### 38
Which of the following cannot be used in Amazon EC2 to control who has access to specific Amazon EC2 instances?

- [ ] Security Groups.
- [x] IAM System.
- [ ] SSH keys.
- [ ] Windows passwords.

- - - - - -

### 39
What is the charge for the data transfer incurred in replicating data between your primary and standby?

- [ ] Same as the standard data transfer charge.
- [ ] Double the standard data transfer charge.
- [x] No charge. It is free.
- [ ] Half of the standard data transfer charge.

- - - - - -

### 40
You have a load balancer configured for VPC, and all back-end Amazon EC2 instances are in service. However, your web browser times out when connecting to the load balancer's DNS name. Which options are probable causes of this behavior? (Choose 2 answers)

- [x] The load balancer was not configured to use a public subnet with an Internet gateway configured.
- [ ] The Amazon EC2 instances do not have a dynamically allocated private IP address.
- [x] The security groups or network ACLs are not property configured for web traffic.
- [ ] The load balancer is not configured in a private subnet with a NAT instance.
- [ ] The VPC does not have a VGW configured.

- - - - - -

### 41
Resources that are created in AWS are identified by a unique identifier called an

- [ ] Amazon Resource Number.
- [ ] Amazon Resource Nametag.
- [x] Amazon Resource Name.
- [ ] Amazon Resource Namespace.

- - - - - -

### 42
What are the two types of licensing options available for using Amazon RDS for Oracle?

- [ ] BYOL and Enterprise License.
- [x] BYOL and License Included.
- [ ] Enterprise License and License Included.
- [ ] Role based License and License Included.

- - - - - -

### 43
In AWS, which security aspects are the customer's responsibility? (Choose 4 answers)

- [x] Security Group and ACL (Access Control List) settings.
- [ ] Decommissioning storage devices.
- [x] Patch management on the EC2 instance's operating system.
- [x] Life-cycle management of IAM credentials.
- [ ] Controlling physical access to compute resources.
- [x] Encryption of EBS (Elastic Block Storage) volumes.

- - - - - -

### 44
You have a web application running on six Amazon EC2 instances, consuming about 45% of resources on each instance. You are using auto-scaling to make sure that six instances are running at all times. The number of requests this application processes is consistent and does not experience spikes. The application is critical to your business and you want high availability at all times. You want the load to be distributed evenly between all instances. You also want to use the same Amazon Machine Image (AMI) for all instances. Which of the following architectural choices should you make?

- [ ] Deploy 6 EC2 instances in one Availability Zone and use Amazon Elastic Load Balancer.
- [ ] Deploy 3 EC2 instances in one region and 3 in another region and use Amazon Elastic Load Balancer.
- [x] Deploy 3 EC2 instances in one Availability Zone and 3 in another Availability Zone and use Amazon Elastic Load Balancer.
- [ ] Deploy 2 EC2 instances in three regions and use Amazon Elastic Load Balancer.

- - - - - -

### 45
An ERP application is deployed across multiple AZs in a single region. in the event of failure, the Recovery Time Objective (RTO) must be less than 3 hours, and the Recovery Point Objective (RPO) must be 15 minutes the customer realizes that data corruption occurred roughly 1.5 hours ago. What DR strategy could be used to achieve this RTO and RPO in the event of this kind of failure?

- [x] Take hourly DB backups to S3, with transaction logs stored in S3 every 5 minutes.
- [ ] Use synchronous database master-slave replication between two Availability Zones.
- [ ] Take hourly DB backups to EC2 Instance store volumes with transaction logs stored in S3 every 5 minutes.
- [ ] Take 15 minute DB backups stored in Glacier with transaction logs stored in S3 every 5 minutes.

- - - - - -

### 46
You have been setting up an Amazon Virtual Private Cloud (Amazon VPC) for your company, including setting up subnets. Security is a concern, and you are not sure which is the best security practice for securing subnets in your VPC. Which statement below is correct in describing the protection of AWS resources in each subnet?

- [x] You can use multiple layers of security, including security groups and network access control lists (ACL).
- [ ] You can only use access control lists (ACL).
- [ ] You don't need any security in subnets.
- [ ] You can use multiple layers of security, including security groups, network access control lists (ACL) and CloudHS.

- - - - - -

### 47
Amazon EC2 provides a repository of public data sets that can be seamlessly integrated into AWS cloud-based applications. What is the monthly charge for using the public data sets?

- [ ] A 1 time charge of 10$ for all the datasets.
- [ ] 1$ per dataset per month.
- [ ] 10$ per month for all the datasets.
- [x] There is no charge for using the public data sets.

- - - - - -

### 48
[...] embodies the 'share-nothing' architecture and essentially involves breaking a large database into several smaller databases. Common ways to split a database include: 1. Splitting tables that are not joined in the same query onto different hosts or 2. Duplicating a table across multiple hosts and then using a hashing algorithm to determine which host receives a given update.

- [x] $harding.
- [ ] Fai lure recovery.
- [ ] Federation.
- [ ] DOL operations.

- - - - - -

### 49
After deploying a new website for a client on AWS, he asks if you can set it up so that if it fails it can be automatically redirected to a backup website that he has stored on a dedicated server elsewhere. You are wondering whether Amazon Route 53 can do this. Which statement below is correct in regards to Amazon Route 53?

- [ ] Amazon Route 53 can't help detect an outage. You need to use another service.
- [x] Amazon Route 53 can help detect an outage of your website and redirect your end users to alternate locations.
- [ ] Amazon Route 53 can help detect an outage of your website but can't redirect your end users to alternate locations.
- [ ] Amazon Route 53 can't help detect an outage of your website, but can redirect your end users to alternate locations.

- - - - - -

### 50
Your company plans to host a large donation website on Amazon Web Services (AWS). You anticipate a large and undetermined amount of traffic that will create many database writes. To be certain that you do not drop any writes to a database hosted on AWS. Which service should you use?

- [ ] Amazon RDS with provisioned IOPS up to the anticipated peak write throughput.
- [x] Amazon Simple Queue Service (SOS) for capturing the writes and draining the queue to write to the database.
- [ ] Amazon ElastiCache to store the writes until the writes are committed to the database.
- [ ] Amazon DynamoDB with provisioned write throughput up to the anticipated peak write throughput.

- - - - - -

