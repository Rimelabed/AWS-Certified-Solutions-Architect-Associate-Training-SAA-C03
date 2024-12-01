### 1
You have set up an Auto Scaling group. The cool down period for the Auto Scaling group is 7 minutes. The first instance is launched after 3 minutes, while the second instance is launched after 4 minutes. How many minutes after the first instance is launched will Auto Scaling accept another scaling activity request?

- [x] 11 minutes.
- [ ] 7 minutes.
- [ ] 10 minutes.
- [ ] 14 minutes.

- - - - - -

### 2
You are migrating a legacy client-server application to AWS. The application responds to a specific DNS domain (e.g. <www.example.com>) and has a 2-tier architecture, with multiple application servers and a database server. Remote clients use TCP to connect to the application servers. The application servers need to know the IP address of the clients in order to function properly and are currently taking that information from the TCP socket. A Multi-AZ RDS MySQL instance will be used for the database. During the migration you can change the application code, but you have to file a change request. How would you implement the architecture on AWS in order to maximize scalability and high availability?

- [ ] File a change request to implement Alias Resource support in the application. Use Route 53 Alias Resource Record to distribute load on two application servers in different AZs.
- [ ] File a change request to implement Latency Based Routing support in the application. Use Route 53 with Latency Based Routing enabled to distribute load on two application servers in different AZs.
- [ ] File a change request to implement Cross-Zone support in the application. Use an ELB with a TCP Listener and Cross-Zone Load Balancing enabled, two application servers in different AZs.
- [x] File a change request to implement Proxy Protocol support in the application. Use an ELB with a TCP Listener and Proxy Protocol enabled to distribute load on two application servers in different AZs.

- - - - - -

### 3
Can I test my DB Instance against a new version before upgrading?

- [x] Yes.
- [ ] No.
- [ ] Only in VPC.

- - - - - -

### 4
Your system recently experienced down time during the troubleshooting process. You found that a new administrator mistakenly terminated several production EC2 instances. Which of the following strategies will help prevent a similar situation in the future? The administrator still must be able to: Launch, start stop, and terminate development resources. Launch and start production instances.

- [ ] Create an IAM user, which is not allowed to terminate instances by leveraging production EC2 termination protection.
- [x] Leverage resource based tagging along with an IAM user, which can prevent specific users from terminating production EC2 resources.
- [ ] Leverage EC2 termination protection and multi-factor authentication, which together require users to authenticate before terminating EC2 instances.
- [ ] Create an IAM user and apply an IAM role which prevents users from terminating production EC2 instances.

- - - - - -

### 5
You have just set up a large site for a client which involved a huge database which you set up with Amazon RDS to run as a Multi-AZ deployment. You now start to worry about what will happen if the database instance fails. Which statement best describes how this database will function if there is a database failure?

- [x] Updates to your DB Instance are synchronously replicated across Availability Zones to the standby in order to keep both in sync and protect your latest database updates against DB Instance failure.
- [ ] Your database will not resume operation without manual administrative intervention.
- [ ] Updates to your DB Instance are asynchronously replicated across Availability Zones to the standby in order to keep both in sync and protect your latest database updates against DB Instance failure.
- [ ] Updates to your DB Instance are synchronously replicated across S3 to the standby in order to keep both in sync and protect your latest database updates against DB Instance failure.

- - - - - -

### 6
Your company has an on-premises multi-tier PHP web application, which recently experienced downtime due to a large burst in web traffic due to a company announcement Over the coming days, you are expecting similar announcements to drive similar unpredictable bursts, and are looking to find ways to quickly improve your infrastructures ability to handle unexpected increases in traffic. The application currently consists of 2 tiers a web tier which consists of a load balancer and several Linux Apache web servers as well as a database tier which hosts a Linux server hosting a MySQLdatabase. Which scenario below will provide full site functionality, while helping to improve the ability of your application in the short timeframe required?

- [ ] Failover environment: Create an S3 bucket and configure it for website hosting. Migrate your DNS to Route 53 using zone file import, and leverage Route 53 DNS failover to failover to the S3 hosted website.
- [ ] Hybrid environment: Create an AMI, which can be used to launch web servers in EC2. Create an Auto Scaling group, which uses the AMI to scale the web tier based on incoming traffic. LeverageElastic Load Balancing to balance traffic between on-premises web servers and those hosted in AWS.
- [x] Offload traffic from on-premises environment: Setup a CloudFront distribution, and configure CloudFront to cache objects from a custom origin. Choose to customize your object cache behavior, and select a TIL that objects should exist in cache.
- [ ] Migrate to AWS: Use VM Import/Export to quickly convert an on-premises web server to an AMI.
- [ ] Create an Auto Scaling group, which uses the imported AMI to scale the web tier based on incoming traffic. Create an RDS read replica and setup replication between the RDS instance and on-premises MySQL server to migrate the database.

- - - - - -

### 7
When using consolidated billing there are two account types. What are they?

- [x] Paying account and Linked account.
- [ ] Parent account and Child account.
- [ ] Main account and Sub account.
- [ ] Main account and Secondary account.

- - - - - -

### 8
You have a periodic Image analysis application that gets some files in Input analyzes them and tor each file writes some data in output to a ten file the number of files in input per day is high and concentrated in a few hours of the day. Currently you have a server on EC2 with a large EBS volume that hosts the input data and the results it takes almost 20 hours per day to complete the process What services could be used to reduce the elaboration time and improve the availability of the solution?

- [ ] Amazon S3 to store 1/0 files. SQS to distribute elaboration commands to a group of hosts working in parallel. Auto scaling to dynamically size the group of hosts depending on the length of the SQS queue.
- [ ] EBS with Provisioned IOPS (PIOPS) to store 1/0 files. SNS to distribute elaboration commands to a group of hosts working in parallel Auto Scaling to dynamically size the group of hosts depending on the number of SNS notifications.
- [ ] Amazon S3 to store 1/0 files, SNS to distribute evaporation commands to a group of hosts working in parallel. Auto scaling to dynamically size the group of hosts depending on the number of SNS notifications.
- [x] EBS with Provisioned IOPS (PIOPS) to store 1/0 files SOS to distribute elaboration commands to a group of hosts working in parallel Auto Scaling to dynamically size the group ot hosts depending on the length of the SQS queue.

- - - - - -

### 9
While controlling access to Amazon EC2 resources, which of the following acts as a firewall that controls the traffic allowed to reach one or more instances?

- [x] A security group.
- [ ] An instance type.
- [ ] A storage cluster.
- [ ] An object.

- - - - - -

### 10
The base URI for all requests for instance metadata is [...].

- [ ] <http://254.169.169.254/latest/>.
- [ ] <http://169.169.254.254/latest/>.
- [ ] <http://127.0.0.1/latest/>.
- [x] <http://169.254.169.254/latest/>.

- - - - - -

### 11
While using the EC2 GET requests as URLs, the [...] is the URL that serves as the entry point for the web service.

- [ ] token.
- [x] endpoint.
- [ ] action.
- [ ] None of these.

- - - - - -

### 12
A user is planning to launch a scalable web application. Which of the below mentioned options will not affect the latency of the application?

- [ ] Region.
- [x] Provisioned IOPS.
- [ ] Availability Zone.
- [ ] Instance size.

- - - - - -

### 13
Your firm has uploaded a large amount of aerial image data to S3 in the past, in your on-premises environment, you used a dedicated group of servers to oaten process this data and used Rabbit MQAnopen source messaging system to get job information to the servers. Once processed the data would go to tape and be shipped offsite. Your manager told you to stay with the current design, and leverage AWS archival storage and messaging services to minimize cost. Which is correct?

- [ ] Use SQS for passing job messages use Cloud Watch alarms to terminate EC2 worker instances when they become idle. Once data is processed, change the storage class of the S3 objects to Reduced Redundancy Storage.
- [ ] Setup Auto-Scaled workers triggered by queue depth that use spot instances to process messages in SOS Once data is processed,
- [ ] Change the storage class of the S3 objects to Reduced Redundancy Storage. Setup Auto-Scaled workers triggered by queue depth that use spot instances to process messages in SQS Once data is processed, change the storage class of the S3 objects to Glacier.
- [x] Use SNS to pass job messages use Cloud Watch alarms to terminate spot worker instances when they become idle. Once data is processed, change the storage class of the S3 object to Glacier.

- - - - - -

### 14
A user has launched 10 EC2 instances inside a placement group. Which of the below mentioned statements is true with respect to the placement group?

- [x] All instances must be in the same AZ.
- [ ] All instances can be across multiple regions.
- [ ] The placement group cannot have more than 5 instances.
- [ ] All instances must be in the same region.

- - - - - -

### 15
A user has created a CloudFormation stack. The stack creates AWS services, such as EC2 instances, ELB, AutoScaling, and RDS. While creating the stack it created EC2, ELB and AutoScaling but failed to create RDS. What will CloudFormation do in this scenario?

- [x] Rollback all the changes and terminate all the created services.
- [ ] It will wait for the user's input about the error and correct the mistake after the input.
- [ ] CloudFormation can never throw an error after launching a few services since it verifies all the steps before launching.
- [ ] It will warn the user about the error and ask the user to manually create RDS.

- - - - - -

### 16
You have been asked to design the storage layer for an application. The application requires disk performance of at least 100,000 IOPS. In addition, the storage layer must be able to survive the loss of an individual disk, EC2 instance, or Availability Zone without any data loss. The volume you provide must have a capacity of at least 3 TB. Which of the following designs will meet these objectives?

- [ ] Instantiate a c3.8xlarge instance in us-east-1. Provision 4x1TB EBS volumes, attach them to the instance, and configure them as a single RAID 5 volume. Ensure that EBS snapshots are performed every 15 minutes.
- [ ] Instantiate a c3.8xlarge instance in us-east-1. Provision 3xlTB EBS volumes, attach them to the Instance, and configure them as a single RAID 0 volume. Ensure that EBS snapshots are performed every 15 minutes.
- [ ] Instantiate an i2.8xlarge instance in us-east-1a. Create a RAID 0 volume using the four 800GB SSD ephemeral disks provided with the instance. Provision 3x1TB EBS volumes, attach them to the instance, and configure them as a second RAID 0 volume. Configure synchronous, block-level replication from the ephemeral-backed volume to the EBS-backed volume.
- [ ] Instantiate a c3.8xlarge instance in us-east-1. Provision an AWS Storage Gateway and configure it for 3 TB of storage and 100,000 IOPS. Attach the volume to the instance.
- [x] Instantiate an i2.8xlarge instance in us-east-1a. Create a RAID 0 volume using the four 800GB SSD ephemeral disks provided with the instance. Configure synchronous, block-level replication to an identically configured instance in us-east-1b.

- - - - - -

### 17
A company is preparing to give AWS Management Console access to developers Company policy mandates identity federation and role-based access control. Roles are currently assigned using groups in the corporate Active Directory. What combination of the following will give developers access to the AWS console? (Choose 2 answers)

- [x] AWS Directory Service AD Connector.
- [ ] AWS Directory Service Simple AD.
- [ ] AWS Identity and Access Management groups.
- [x] AWS identity and Access Management roles.
- [ ] AWS identity and Access Management users.

- - - - - -

### 18
Your startup wants to implement an order fulfillment process for selling a personalized gadget that needs an average of 3-4 days to produce with some orders taking up to 6 months you expect 10orders per day on your first day. 1000 orders per day after 6 months and 10,000 orders after 12 months. Orders coming in are checked for consistency men dispatched to your manufacturing plant for production quality control packaging shipment and payment processing If the product does not meet the quality standards at any stage of the process employees may force the process to repeat a step Customers are notified via email about order status and any critical issues with their orders such as payment failure. Your case architecture includes AWS Elastic Beanstalk for your website with an RDS MySQL instance for customer data and orders. How can you implement the order fulfillment process while making sure that the emails are delivered reliably?

- [ ] Add a business process management application to your Elastic Beanstalk app servers and re-use the ROS database for tracking order status use one of the Elastic Beanstalk instances to send emails to customers.
- [ ] Use SWF with an Auto Scaling group of activity workers and a decider instance in another Auto Scaling group with min/max=l Use the decider instance to send emails to customers.
- [x] Use SWF with an Auto Scaling group of activity workers and a decider instance in another Auto Scaling group with min/max=l use SES to send emails to customers.
- [ ] Use an SQS queue to manage all process tasks Use an Auto Scaling group of EC2 Instances that poll the tasks and execute them. Use SES to send emails to customers.

- - - - - -

### 19
A, [...] is an individual, system, or application that interacts with AWS programmatically.

- [x] user.
- [ ] AWS Account.
- [ ] group.
- [ ] role.

- - - - - -

### 20
A user is accessing an EC2 instance on the SSH port for IP 10.20.30.40. Which one is a secure way to configure that the instance can be accessed only from this IP?

- [ ] In the security group, open port 22 for IP 10.20.30.40.
- [x] In the security group, open port 22 for IP 10.20.30.40/32.
- [ ] In the security group, open port 22 for IP 10.20.30.40/24.
- [ ] In the security group, open port 22 for IP 10.20.30.40/0.

- - - - - -

### 21
Read Replicas require a transactional storage engine and are only supported for the [...] storage engine.

- [ ] OracleISAM.
- [ ] MSSQLDB.
- [x] InnoDB.
- [ ] MyISAM.

- - - - - -

### 22
What is Amazon Glacier?

- [ ] You mean Amazon 'Iceberg': it's a low-cost storage service.
- [ ] A security tool that allows to 'freeze' an EBS volume and perform computer forensics on it.
- [x] A low-cost storage service that provides secure and durable storage for data archiving and backup.
- [ ] It's a security tool that allows to 'freeze' an EC2 instance and perform computer forensics on it.

- - - - - -

### 23
You have a content management system running on an Amazon EC2 instance that is approaching 100% CPU utilization. Which option will reduce load on the Amazon EC2 instance?

- [ ] Create a load balancer, and register the Amazon EC2 instance with it.
- [x] Create a CloudFront distribution, and configure the Amazon EC2 instance as the origin.
- [ ] Create an Auto Scaling group from the instance using the Create AutoScaling Group action.
- [ ] Create a launch configuration from the instance using the Create launch Configuration action.

- - - - - -

### 24
Can I initiate a 'forced failover' for my MySQL Multi-AZ DB Instance deployment?

- [x] Only in certain regions.
- [ ] Only in VPC.
- [ ] Yes.
- [ ] No.

- - - - - -

### 25
When controlling access to Amazon EC2 resources, each Amazon EBS Snapshot has a [...] attribute that controls which AWS accounts can use the snapshot.

- [x] createVolumePermission.
- [ ] LaunchPermission.
- [ ] SharePermission.
- [ ] RequestPermission.

- - - - - -

### 26
You have decided to change the instance type for instances running in your application tier that is using Auto Scaling. In which area below would you change the instance type definition?

- [ ] Auto Scaling policy.
- [ ] Auto Scaling group.
- [ ] Auto Scaling tags.
- [x] Auto Scaling launch configuration.

- - - - - -

### 27
Which of the following statements is true of creating a launch configuration using an EC2 instance?

- [ ] The launch configuration can be created only using the Query APIs.
- [x] Auto Scaling automatically creates a launch configuration directly from an EC2 instance.
- [ ] A user should manually create a launch configuration before creating an Auto Scaling group.
- [ ] The launch configuration should be created manually from the AWS CL.

- - - - - -

### 28
Your company has multiple IT departments, each with their own VPC. Some VPCs are located within the same AWS account, and others in a different AWS account. You want to peer together all VPCs to enable the IT departments to have full access to each others' resources. There are certain limitations placed on VPC peering. Which of the following statements is incorrect in relation to VPC peering?

- [ ] Private DNS values cannot be resolved between instances in peered VPCs.
- [x] You can have up to 3 VPC peering connections between the same two VPCs at the same time.
- [ ] You cannot create a VPC peering connection between VPCs in different regions.
- [ ] You have a limit on the number active and pending VPC peering connections that you can have per VP.

- - - - - -

### 29
A gaming company comes to you and asks you to build them infrastructure for their site. They are not sure how big they will be as with all start ups they have limited money and big ideas. What they do tell you is that if the game becomes successful, like one of their previous games, it may rapidly grow to millions of users and generate tens (or even hundreds) of thousands of writes and reads per second. After considering all of this, you decide that they need a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability. Which of the following databases do you think would best fit their needs?

- [x] Amazon DynamoDB.
- [ ] Amazon Redshift.
- [ ] Any non-relational database.
- [ ] Amazon SimpleDB.

- - - - - -

### 30
A/An [...] acts as a firewall that controls the traffic allowed to reach one or more instances.

- [x] security group.
- [ ] ACL.
- [ ] IAM.
- [ ] private IP Addresses.

- - - - - -

### 31
Your manager has just given you access to multiple VPN connections that someone else has recently set up between all your company's offices. She needs you to make sure that the communication between the VPNs is secure. Which of the following services would be best for providing a low-cost hub-and-spoke model for primary or backup connectivity between these remote offices?

- [ ] Amazon CloudFront.
- [ ] AWS Direct Connect.
- [ ] AWS CloudHSM.
- [x] AWS VPN CloudHub.

- - - - - -

### 32
You need to create a management network using network interfaces for a virtual private cloud (VPC) network. Which of the following statements is incorrect pertaining to Best Practices for ConfiguringNetwork Interfaces.

- [ ] You can detach secondary (ethN) network interfaces when the instance is running or stopped. However, you can't detach the primary (eth0) interface.
- [ ] Launching an instance with multiple network interfaces automatically configures interfaces, private IP addresses, and route tables on the operating system of the instance.
- [ ] You can attach a network interface in one subnet to an instance in another subnet in the same VPC, however, both the network interface and the instance must reside in the same Availability Zone.
- [x] Attaching another network interface to an instance is a valid method to increase or double the network bandwidth to or from the dual-homed instance.

- - - - - -

### 33
A user has launched 10 EC2 instances inside a placement group. Which of the following statements is true in regards to what ability launching your instances into a VPC instead of EC2-Classic gives you?

- [x] All of the things listed here.
- [ ] Change security group membership for your instances while they're running.
- [ ] Assign static private IP addresses to your instances that persist across starts and stops.
- [ ] Define network interfaces, and attach one or more network interfaces to your instances.

- - - - - -

### 34
In the HQ region you run an hourly batch process reading data from every region to compute cross regional reports that are sent by email to all offices this batch process must be completed as fast as possible to quickly optimize logistics how do you build the database architecture in order to meet the requirements'?

- [x] For each regional deployment, use RDS MySQL with a master in the region and a read replica in the HQ region.
- [ ] For each regional deployment, use MySQL on EC2 with a master in the region and send hourly EBS snapshots to the HQ region.
- [ ] For each regional deployment, use RDS MySQL with a master in the region and send hourly RDS snapshots to the HQ region.
- [ ] For each regional deployment, use MySQL on EC2 with a master in the region and use S3 to copy data files hourly to the HQ region.
- [ ] Use Direct Connect to connect all regional MySQL deployments to the HQ region and reduce network latency for the batch process.

- - - - - -

### 35
What is the average IOPS that the user will get for most of the year as per EC2 SLA if the instance is attached to the EBS optimized instance?

- [ ] 950.
- [ ] 990.
- [ ] 1000.
- [x] 900.

- - - - - -

### 36
You are working with a customer who has 10 TB of archival data that they want to migrate to Amazon Glacier. The customer has a 1-Mbps connection to the Internet. Which service or feature provides the fastest method of getting the data into Amazon Glacier?

- [x] Amazon Glacier multipart upload.
- [ ] AWS Storage Gateway.
- [ ] VM Import/Export.
- [ ] AWS Import/Export.

- - - - - -

### 37
Your manager has asked you to set up a public subnet with instances that can send and receive internet traffic, and a private subnet that can't receive traffic directly from the internet, but can initiate traffic to the internet (and receive responses) through a NAT instance in the public subnet. Hence, the following 3 rules need to be allowed: Inbound SSH traffic. Web servers in the public subnet to read and write to MS SQL servers in the private subnet. Inbound RDP traffic from the Microsoft Terminal Services gateway in the public private subnet. What are the respective ports that need to be opened for this?

- [x] Ports 22, 1433, 3389.
- [ ] Ports 21, 1433, 3389.
- [ ] Ports 25, 1433, 3389.
- [ ] Ports 22, 1343, 3999.

- - - - - -

### 38
An EC2 instance is connected to an ENI (Elastic Network Interface) in one subnet. What happens to the data on an instance if the instance reboots (intentionally or unintentionally)?

- [ ] Data will be lost.
- [x] Data persists.

- - - - - -

### 39
Please select the Amazon EC2 resource which can be tagged.

- [ ] Key pairs.
- [ ] Elastic IP addresses.
- [x] Placement groups.
- [ ] Amazon EBS snapshots.

- - - - - -

### 40
Without [...] you must either create multiple AWS accounts-each with its own billing and subscriptions to AWS products-or your employees must share the security credentials of a single AWS account.

- [ ] Amazon RDS.
- [ ] Amazon Glacier.
- [ ] Amazon EMR.
- [x] Amazon IAM.

- - - - - -

### 41
An EC2 instance is connected to an ENI (Elastic Network Interface) in one subnet. What happens when you attach an ENI of a different subnet to this EC2 instance?

- [ ] The EC2 instance follows the rules of the older subnet.
- [x] The EC2 instance follows the rules of both the subnets.
- [ ] Not possible, cannot be connected to 2 ENIs.
- [ ] The EC2 instance follows the rules of the newer subnet.

- - - - - -

### 42
You have deployed a three-tier web application in a VPC with a CIDR block of 10.0.0.0/28. You initially deploy two web servers, two application servers, two database servers and one NAT instance tor a total of seven EC2 instances. The web, application and database servers are deployed across two Availability Zones (AZs). You also deploy an ELB in front of the two web servers, and use Route 53 for DNS Web. Raffle gradually increases in the first few days following the deployment, so you attempt to double the number of instances in each tier of the application to handle the new load unfortunately some of these new instances fail to launch.Which of the following could be the root caused? (Choose 2 answers)

- [ ] AWS reserves the first and the last private IP address in each subnet's CIDR block so you do not have enough addresses left to launch all of the new EC2 instances.
- [ ] The Internet Gateway (IGW) of your VPC has scaled-up, adding more instances to handle the traffic spike, reducing the number of available private IP addresses for new instance launches.
- [x] The ELB has scaled-up, adding more instances to handle the traffic spike, reducing the number of available private IP addresses for new instance launches.
- [ ] AWS reserves one IP address in each subnet's CIDR block for Route 53 so you do not have enough addresses left to launch all of the new EC2 instances.
- [x] AWS reserves the first four and the last IP address in each subnet's CIDR block so you do not have enough addresses left to launch all of the new EC2 instances.

- - - - - -

### 43
Which of the following will cause an immediate DB instance reboot to occur?

- [x] You change storage type from standard to PIOPS, and Apply Immediately is set to true.
- [ ] You change the DB instance class, and Apply Immediately is set to false.
- [ ] You change a static parameter in a DB parameter group.
- [ ] You change the backup retention period for a DB instance from 0 to a nonzero value or from a nonzero value to 0, and Apply Immediately is set to false.

- - - - - -

### 44
EBS Snapshots occur [...].

- [x] Asynchronously.
- [ ] Synchronously.

- - - - - -

### 45
You are tasked with moving a legacy application from a virtual machine running Inside your datacenter to an Amazon VPC Unfortunately this app requires access to a number of on-premises services and no one who configured the app still works for your company. Even worse there's no documentation for it. What will allow the application running inside the VPC to reach back and access its internal dependencies without being reconfigured? (Choose 3 answers)

- [x] An AWS Direct Connect link between the VPC and the network housing the internal services.
- [ ] An Internet Gateway to allow a VPN connection.
- [ ] An Elastic IP address on the VPC instance.
- [x] An IP address space that does not conflict with the one on-premises.
- [ ] Entries in Amazon Route 53 that allow the Instance to resolve its dependencies' IP addresses.
- [x] A VM Import of the current virtual machine.

- - - - - -

### 46
A company needs to deploy services to an AWS region which they have not previously used. The company currently has an AWS identity and Access Management (IAM) role for the Amazon EC2 instances, which permits the instance to have access to Amazon DynamoDB. The company wants their EC2 instances in the new region to have the same privileges. How should the company achieve this?

- [ ] Create a new IAM role and associated policies within the new region.
- [x] Assign the existing IAM role to the Amazon EC2 instances in the new region.
- [ ] Copy the IAM role and associated policies to the new region and attach it to the instances.
- [ ] Create an Amazon Machine Image (AMI) of the instance and copy it to the desired region using the AMI Copy feature.

- - - - - -

### 47
If you want to launch Amazon Elastic Compute Cloud (EC2) instances and assign each instance a predetermined private IP address you should:

- [ ] Launch the instance from a private Amazon Machine Image (AMI).
- [x] Assign a group of sequential Elastic IP address to the instances.
- [ ] Launch the instances in the Amazon Virtual Private Cloud (VPC).
- [ ] Launch the instances in a Placement Group.
- [ ] Use standard EC2 instances since each instance gets a private Domain Name Service (DNS) already.

- - - - - -

### 48
When automatic failover occurs, Amazon RDS will emit a DB Instance event to inform you that automatic failover occurred. You can use the [...] to return information about events related to your DB Instance.

- [ ] FetchFailure.
- [ ] DescriveFailure.
- [x] DescribeEvents.
- [ ] FetchEvents.

- - - - - -

### 49
You have a Business support plan with AWS. One of your EC2 instances is running Microsoft Windows Server 2008 R2 and you are having problems with the software. Can you receive support from AWS for this software?

- [x] Yes.
- [ ] No, AWS does not support any third-party software.
- [ ] No, Microsoft Windows Server 2008 R2 is not supported.
- [ ] No, you need to be on the enterprise support plan.

- - - - - -

### 50
A newspaper organization has a on-premises application which allows the public to search its back catalogue and retrieve individual newspaper pages via a website written in Java They have scanned the old newspapers into JPEGs (approx 17TB) and used Optical Character Recognition (OCR) to populate a commercial search product. The hosting platform and software are now end of life and the organization wants to migrate Its archive to AWS and produce a cost efficient architecture and still be designed for availability and durability. Which is the most appropriate?

- [ ] Use S3 with reduced redundancy to store and serve the scanned files, install the commercial search application on EC2 Instances and configure with auto-scaling and an Elastic Load Balancer.
- [ ] Model the environment using CloudFormation use an EC2 instance running Apache webserver and an open source search application, stripe multiple standard EB5 volumes together to store the JPEGs and search index.
- [x] Use S3 with standard redundancy to store and serve the scanned files, use Cloud5earch for query processing, and use Elastic Beanstalk to host the website across multiple Availability Zones.
- [ ] Use a single-AZ RD5 My5QL instance to store the search index 33d the JPEG images use an EC2 instance to serve the website and translate user queries into 5Q
- [ ] Use a CloudFront download distribution to serve the JPEGs to the end users and Install the current commercial search product, along with a Java Container Tor the website on EC2 instances and use Route 53 with DNS round-robin.

- - - - - -

