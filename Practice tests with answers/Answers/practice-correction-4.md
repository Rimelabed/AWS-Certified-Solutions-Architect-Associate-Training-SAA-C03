### 1
Is there a limit to the number of groups you can have?

- [ ] Yes for all users except root.
- [ ] No.
- [ ] Yes unless special permission granted.
- [x] Yes for all users.

- - - - - -

### 2
True or False: Automated backups are enabled by default for a new DB Instance

- [x] True.
- [ ] False.

- - - - - -

### 3
What is one key difference between an Amazon EBS-backed and an instance-store backed instance?

- [x] Amazon EBS-backed instances can be stopped and restarted.
- [ ] Instance-store backed instances can be stopped and restarted.
- [ ] Auto scaling requires using Amazon EBS-backed instances.
- [ ] Virtual Private Cloud requires EBS backed instances.

- - - - - -

### 4
A major customer has asked you to set up his AWS infrastructure so that it will be easy to recover in the case of a disaster of some sort. Which of the following statements is true of Amazon EC2 security groups?

- [ ] Create and maintain AMIs of key servers where fast recovery is required.
- [ ] Regularly run your servers, test them, and apply any software updates and configuration changes.
- [ ] Ensure that you have all supporting custom software packages available in AWS.
- [x] All items listed here are important when thinking about disaster recovery.

- - - - - -

### 5
Select a true statement about Amazon EC2 Security Groups (EC2-Classic).

- [x] After you launch an instance in EC2-Classic, you can't change its security groups.
- [ ] After you launch an instance in EC2-Classic, you can change its security groups only once.
- [ ] After you launch an instance in EC2-Classic, you can only add rules to a security group.
- [ ] After you launch an instance in EC2-Classic, you cannot add or remove rules from a security group.

- - - - - -

### 6
To view information about an Amazon EBS volume, open the Amazon EC2 console at <https://console.aws.amazon.com/ec2/>, click in the Navigation panel.

- [ ] EBS.
- [ ] Describe.
- [ ] Details.
- [x] Volumes.

- - - - - -

### 7
True or False: Provisioned IOPS Costs - you are charged for the IOPS and storage whether or not you use them in a given month.

- [x] True.
- [ ] False.

- - - - - -

### 8
You have an EC2 Security Group with several running EC2 instances. You change the Security Group rules to allow inbound traffic on a new port and protocol, and launch several new instances in the same Security Group. The new rules apply:

- [x] Immediately to all instances in the security group.
- [ ] Immediately to the new instances only.
- [ ] Immediately to the new instances, but old instances must be stopped and restarted before the new rules apply.
- [ ] To all instances, but it may take several minutes for old instances to see the changes.

- - - - - -

### 9
An edge location refers to which Amazon Web Service?

- [ ] An edge location is referred to the network configured within a Zone or Region.
- [ ] An edge location is an AWS Region.
- [x] An edge location is the location of the data center used for Amazon CloudFront.
- [ ] An edge location is a Zone within an AWS Region.

- - - - - -

### 10
If I want to run a database in an Amazon instance, which is the most recommended Amazon storage option?

- [ ] Amazon Instance Storage.
- [x] Amazon EBS.
- [ ] You can't run a database inside an Amazon instance.
- [ ] Amazon S3.

- - - - - -

### 11
A customer is leveraging Amazon Simple Storage Service in eu-west-1 to store static content for a web-based property. The customer is storing objects using the Standard Storage class. Where are the customers objects replicated?

- [ ] A single facility in eu-west-1 and a single facility in eu-central-1.
- [ ] A single facility in eu-west-1 and a single facility in us-east-1.
- [x] Multiple facilities in eu-west-1.
- [ ] A single facility in eu-west-1.

- - - - - -

### 12
You have set up an S3 bucket with a number of images in it and you have decided that you want anybody to be able to access these images, even anonymous users. To accomplish this you create a bucket policy. You will need to use an Amazon S3 bucket policy that specifies a [...] in the principal element, which means anyone can access the bucket.

- [ ] hash tag (#).
- [ ] anonymous user.
- [x] wildcard (*).
- [ ] S3 user.

- - - - - -

### 13
You try to connect via SSH to a newly created Amazon EC2 instance and get one of the following error messages: 'Network error: Connection timed out' or 'Error connecting to [instance], reason: -> Connection timed out: connect,' You have confirmed that the network and security group rules are configured correctly and the instance is passing status checks. What steps should you take to identify the source of the behavior? (Choose 2 answers)

- [x] Verify that the private key file corresponds to the Amazon EC2 key pair assigned at launch.
- [ ] Verify that your IAM user policy has permission to launch Amazon EC2 instances.
- [x] Verify that you are connecting with the appropriate user name for your AMI.
- [ ] Verify that the Amazon EC2 Instance was launched with the proper IAM role.
- [ ] Verify that your federation trust to AWS has been established.

- - - - - -

### 14
An Auto-Scaling group spans 3 AZs and currently has 4 running EC2 instances. When Auto Scaling needs to terminate an EC2 instance by default, AutoScaling will: (Choose 2 answers)

- [ ] Allow at least five minutes for Windows/Linux shutdown scripts to complete, before terminating the instance.
- [ ] Terminate the instance with the least active network connections. If multiple instances meet this criterion, one will be randomly selected.
- [x] Send an SNS notification, if configured to do so.
- [x] Terminate an instance in the AZ which currently has 2 running EC2 instances.
- [ ] Randomly select one of the 3 AZs, and then terminate an instance in that A.

- - - - - -

### 15
A photo-sharing service stores pictures in Amazon Simple Storage Service (S3) and allows application sign-in using an OpenID Connect-compatible identity provider. Which AWS Security Token Service approach to temporary access should you use for the Amazon S3 operations?

- [ ] SAML-based Identity Federation.
- [ ] Cross-Account Access.
- [ ] AWS Identity and Access Management roles.
- [x] Web Identity Federation.

- - - - - -

### 16
What is the maximum key length of a tag?

- [ ] 512 Unicode characters.
- [ ] 64 Unicode characters.
- [ ] 256 Unicode characters.
- [x] 128 Unicode characters.

- - - - - -

### 17
Does Amazon RDS allow direct host access via Telnet, Secure Shell (SSH), or Windows Remote Desktop Connection?

- [ ] Yes.
- [x] No.

- - - - - -

### 18
A user wants to achieve High Availability with PostgreSQL DB. Which of the below mentioned functionalities helps achieve HA?

- [x] Multi-AZ.
- [ ] Read Replica.
- [ ] Multi region.
- [ ] PostgreSQL does not support HA.

- - - - - -

### 19
Are penetration tests allowed as long as they are limited to the customer's instances?

- [ ] Yes, they are allowed but only for selected regions.
- [ ] No, they are never allowed.
- [ ] Yes, they are allowed without any permission.
- [x] Yes, they are allowed but only with approval.

- - - - - -

### 20
You are building a system to distribute confidential documents to employees. Using CloudFront, what method could be used to serve content that is stored in S3, but not publically accessible from S3 directly?

- [ ] Add the CloudFront account security group 'amazon-cf/amazon-cf-sg' to the appropriate S3 bucket policy.
- [ ] Create a S3 bucket policy that lists the CloudFront distribution ID as the Principal and the target bucket as the Amazon Resource Name (ARN).
- [ ] Create an Identity and Access Management (IAM) User for CloudFront and grant access to the objects in your S3 bucket to that IAM User.
- [x] Create an Origin Access Identity (OAI) for CloudFront and grant access to the objects in your S3 bucket to that OA.

- - - - - -

### 21
You require the ability to analyze a large amount of data, which is stored on Amazon S3 using Amazon Elastic MapReduce. You are using the cc2 8x large Instance type, whose CPUs are mostly idle during processing. Which of the below would be the most cost efficient way to reduce the runtime of the job?

- [ ] Create more smaller flies on Amazon S3.
- [ ] Add additional cc2 8x large instances by introducing a task group.
- [x] Use smaller instances that have higher aggregate 1/0 performance.
- [ ] Create fewer, larger fi les on Amazon S3.

- - - - - -

### 22
What is the name of licensing model in which I can use your existing Oracle Database licenses to run Oracle deployments on Amazon RDS?

- [x] Bring Your Own License.
- [ ] Role Bases License.
- [ ] Enterprise License.
- [ ] License Included.

- - - - - -

### 23
Which of the following statements are true about Amazon Route 53 resource records? (Choose 2 answers)

- [x] An Alias record can map one DNS name to another Amazon Route 53 DNS name.
- [ ] A CNAME record can be created for your zone apex.
- [x] An Amazon Route 53 CNAME record can point to any DNS record hosted anywhere.
- [ ] TIL can be set for an Alias record in Amazon Route 53.
- [ ] An Amazon Route 53 Alias record can point to any DNS record hosted anywhere.

- - - - - -

### 24
Do you need to shutdown your EC2 instance when you create a snapshot of EBS volumes that serve as root devices?

- [ ] No, you only need to shutdown an instance before deleting it.
- [x] Yes.
- [ ] No, the snapshot would turn off your instance automatically.
- [ ] No.

- - - - - -

### 25
Can I initiate a 'forced failover' for my Oracle Multi-AZ DB Instance deployment?

- [x] Yes.
- [ ] Only in certain regions.
- [ ] Only in VPC.
- [ ] No.

- - - - - -

### 26
Amazon RDS provides high availability and failover support for DB instances using [...].

- [ ] customized deployments.
- [ ] AppStream customizations.
- [ ] log events.
- [x] Multi-AZ deployments.

- - - - - -

### 27
True or False: Amazon EC2 has no Amazon Resource Names (ARNs) because you can't specify a particular Amazon EC2 resource in an IAM policy.

- [x] True.
- [ ] False.

- - - - - -

### 28
A major client who has been spending a lot of money on his internet service provider asks you to set up an AWS Direct Connection to try and save him some money. You know he needs high-speed connectivity. Which connection port speeds are available on AWS Direct Connect?

- [ ] 500Mbps and 1Gbps.
- [x] 1Gbps and 10Gbps.
- [ ] 100Mbps and 1Gbps.
- [ ] 1Gbps.

- - - - - -

### 29
What will be the state of the alarm at the end of 90 minutes, if the CPU utilization is constant at 80%?

- [ ] ALERT.
- [x] ALARM.
- [ ] OK.
- [ ] INSUFFICIENT_DATA.

- - - - - -

### 30
A 3-tier e-commerce web application is current deployed on-premises and will be migrated to AWS for greater scalability and elasticity The web server currently shares read-only data using a network distributed file system The app server tier uses a clustering mechanism for discovery and shared session state that depends on I P multicast The database tier uses shared-storage clustering to provide database fail over capability, and uses several read slaves for scaling Data on all servers and the distributed file system directory is backed up weekly to off-site tapes. Which AWS storage and database architecture meets the requirements of the application?

- [ ] Web servers: store read-only data in S3, and copy from S3 to root volume at boot time. App servers: share state using a combination of DynamoDB and IP unicast. Database: use RDS with multi-AZdeployment and one or more read replicas. Backup: web servers, app servers, and database backed up weekly to Glacier using snapshots.
- [ ] Web servers: store read-only data in an EC2 NFS server, mount to each web server at boot time. App servers: share state using a combination of DynamoDB and IP multicast. Database: use RDS with multi-AZ deployment and one or more Read Replicas. Backup: web and app servers backed up weekly via AMIs, database backed up via DB snapshots.
- [x] Web servers: store read-only data in S3, and copy from S3 to root volume at boot time. App servers: share state using a combination of DynamoDB and IP unicast. Database: use RDS with multi-AZ deployment and one or more Read Replicas. Backup: web and app servers backed up weekly via AMIs, database backed up via DB snapshots.
- [ ] Web servers: store read-only data in S3, and copy from S3 to root volume at boot time. App servers: share state using a combination of DynamoDB and IP unicast. Database: use RDS with multi-AZdeployment. Backup: web and app servers backed up weekly via AMIs, database backed up via DB snapshots.

- - - - - -

### 31
What are the four levels of AWS Premium Support?

- [x] Basic, Developer, Business, Enterprise.
- [ ] Basic, Startup, Business, Enterprise.
- [ ] Free, Bronze, Silver, Gold.
- [ ] All support is free.

- - - - - -

### 32
What is the default maximum number of Access Keys per user?

- [ ] 10.
- [ ] 15.
- [x] 2.
- [ ] 20.

- - - - - -

### 33
In the most recent company meeting, your CEO focused on the fact that everyone in the organization needs to make sure that all of the infrastructure that is built is truly scalable. Which of the following statements is incorrect in reference to scalable architecture?

- [ ] A scalable service is capable of handling heterogeneity.
- [ ] A scalable service is resilient.
- [x] A scalable architecture won't be cost effective as it grows.
- [ ] Increasing resources results in a proportional increase in performance.

- - - - - -

### 34
What does Amazon S3 stand for?

- [ ] Simple Storage Solution.
- [ ] Storage Storage Storage (triple redundancy Storage).
- [ ] Storage Server Solution.
- [x] Simple Storage Service.

- - - - - -

### 35
A company needs to monitor the read and write IOPs metrics for their AWS MySQL RDS instance and send real-time alerts to their operations team. Which AWS services can accomplish this? (Choose 2 answers)

- [ ] Amazon Simple Email Service.
- [x] Amazon CloudWatch.
- [ ] Amazon Simple Queue Service.
- [ ] Amazon Route 53.
- [x] Amazon Simple Notification Service.

- - - - - -

### 36
A user has configured ELB with two EBS backed EC2 instances. The user is trying to understand the DNS access and IP support for ELB. Which of the below mentioned statements may not help the user understand the IP mechanism supported by ELB?

- [ ] The client can connect over IPV4 or IPV6 using Dualstack.
- [ ] Communication between the load balancer and back-end instances is always through IPV4.
- [ ] ELB DNS supports both IPV4 and IPV6.
- [x] The ELB supports either IPV4 or IPV6 but not both.

- - - - - -

### 37
What is Oracle SQL Developer?

- [ ] An AWS developer who is an expert in Amazon RDS using both the Oracle and SQL Server DB engines.
- [x] A graphical Java tool distributed without cost by Oracle.
- [ ] It is a variant of the SQL Server Management Studio designed by Microsoft to support Oracle DBMS functionalities.
- [ ] A different DBMS released by Microsoft free of cost.

- - - - - -

### 38
You can use [...] to help secure the instances in your VPC.

- [ ] security groups and multi-factor authentication.
- [ ] security groups and 2-Factor authentication.
- [ ] security groups and biometric authentication.
- [x] security groups and network ACLs.

- - - - - -

### 39
What is the type of monitoring data (for Amazon EBS volumes) which is available automatically in 5- minute periods at no charge called?

- [x] Basic.
- [ ] Primary.
- [ ] Detailed.
- [ ] Local.

- - - - - -

### 40
A user comes to you and wants access to Amazon CloudWatch but only wants to monitor a specific LoadBalancer. Is it possible to give him access to a specific set of instances or a specific LoadBalancer?

- [x] No because you can't use IAM to control access to CloudWatch data for specific resources.
- [ ] Yes. You can use IAM to control access to CloudWatch data for specific resources.
- [ ] No because you need to be Sysadmin to access CloudWatch data.
- [ ] Yes. Any user can see all CloudWatch data and needs no access rights.

- - - - - -

### 41
Which Amazon Elastic Compute Cloud feature can you query from within the instance to access instance properties?

- [ ] Instance user data.
- [ ] Resource tags.
- [x] Instance metadata.
- [ ] Amazon Machine Image.

- - - - - -

### 42
Making your snapshot public shares all snapshot data with everyone. Can the snapshots with AWS Market place product codes be made public?

- [x] Yes.
- [ ] No.

- - - - - -

### 43
Which service enables AWS customers to manage users and permissions in AWS?

- [ ] AWS Access Control Service (ACS).
- [x] AWS Identity and Access Management (IAM).

- - - - - -

### 44
You have launched an EC2 instance with four (4) 500 GB EBS Provisioned IOPS volumes attached. The EC2 instance is EBS-Optimized and supports 500 Mbps throughput between EC2 and EBS. The four EBS volumes are configured as a single RAID 0 device, and each Provisioned IOPS volume is provisioned with 4,000IOPS (4,000 16KB reads or writes), for a total of 16,000 random IOPS on the instance. The EC2 instance initially delivers the expected 16,000 IOPS random read and write performance. Sometime later, in order to increase the total random I/O performance of the instance, you add an additional two 500 GB EBS Provisioned IOPS volumes to the RAID. Each volume is provisioned to 4,000 IOPs like the original four, for a total of 24,000 IOPS on the EC2 instance. Monitoring shows that the EC2 instance CPU utilization increased from 50% to 70%, but the total random IOPS measured at the instance level does not increase at all. What is the problem and a valid solution?

- [ ] Larger storage volumes support higher Provisioned IOPS rates; increase the provisioned volume storage of each of the 6 EBS volumes to 1TB.
- [x] The EBS-Optimized throughput limits the total IOPS that can be utilized; use an EBS Optimized instance that provides larger throughput. Mo
- [ ] Small block sizes cause performance degradation, limiting the I/O throughput; configure the instance device driver and filesystem to use 64KB blocks to increase throughput.
- [ ] The standard EBS Instance root volume limits the total IOPS rate; change the instance root volume to also be a 500GB 4,000 Provisioned IOPS volume.
- [ ] RAID 0 only scales linearly to about 4 devices; use RAID 0 with 4 EBS Provisioned IOPS volumes, but increase each Provisioned IOPS EBS volume to 6,000 IOPS.

- - - - - -

### 45
A user has configured a website and launched it using the Apache web server on port 80. The user is using ELB with the EC2 instances for Load Balancing. What should the user do to ensure that the EC2 instances accept requests only from ELB?

- [x] Configure the security group of EC2, which allows access to the ELB source security group.
- [ ] Configure the EC2 instance so that it only listens on the ELB port.
- [ ] Open the port for an ELB static IP in the EC2 security group.
- [ ] Configure the security group of EC2, which allows access only to the ELB listener.

- - - - - -

### 46
You're trying to delete an SSL certificate from the IAM certificate store, and you're getting the message 'Certificate: <certificate< span=''>-id> is being used by CloudFront.' Which of the following statements is probably the reason why you are getting this error?

- [x] Before you can delete an SSL certificate, you need to either rotate SSL certificates or revert from using a custom SSL certificate to using the default CloudFront certificate.
- [ ] You can't delete SSL certificates. You need to request it from AWS.
- [ ] Before you can delete an SSL certificate, you need to set up the appropriate access level in IAM. Before you can delete an SSL certificate you need to set up https on your server.
- [ ] Before you can delete an SSL certificate you need to set up https on your server.

- - - - - -

### 47
A government client needs you to set up secure cryptographic key storage for some of their extremely confidential data. You decide that the AWS CloudHSM is the best service for this. However, there seem to be a few pre-requisites before this can happen, one of those being a security group that has certain ports open. Which of the following is correct in regards to those security groups?

- [x] A security group that has port 22 (for SSH) or port 3389 (for RDP) open to your network.
- [ ] A security group that has no ports open to your network.
- [ ] A security group that has only port 3389 (for RDP) open to your network.
- [ ] A security group that has only port 22 (for SSH) open to your network.

- - - - - -

### 48
A web company is looking to implement an intrusion detection and prevention system into their deployed VPC. This platform should have the ability to scale to thousands of instances running inside of the VPC. How should they architect their solution to achieve these goals?

- [ ] Configure an instance with monitoring software and the elastic network interface (ENI) set to promiscuous mode packet sniffing to see an traffic across the VPC. Configure servers running in the VPC using the host-based 'route' commands to send all traffic through the platform to a scalable virtualized IDS/IP.
- [ ] Create a second VPC and route all traffic from the primary application VPC through the second VPC where the scalable virtualized IDS/IPS platform resides.
- [x] Configure servers running in the VPC using the host-based 'route' commands to send all traffic through the platform to a scalable virtualized IDS/IP.
- [ ] Configure each host with an agent that collects all network traffic and sends that traffic to the IDS/IPS platform for inspection.

- - - - - -

### 49
You run an ad-supported photo sharing website using Amazon S3 to serve photos to visitors of your site. At some point you find out that other sites have been linking to the photos on your site, causing loss to your business. What is an effective method to mitigate this?

- [x] Remove public read access and use signed URLs with expiry dates.
- [ ] Use CloudFront distributions for static content.
- [ ] Block the IPs of the offending websites in Security Groups.
- [ ] Store photos on an EBS volume of the web server.

- - - - - -

### 50
Which of the following is not a true statement relating to the performance of your EBS volumes?

- [x] Frequent snapshots provide a higher level of data durability and they will not degrade the performance of your application while the snapshot is in progress.
- [ ] General Purpose (SSD) and Provisioned IOPS (SSD) volumes have a throughput limit of 128 MB/s per volume.
- [ ] There is a relationship between the maximum performance of your EBS volumes, the amount of I/O you are driving to them, and the amount of time it takes for each transaction to complete.
- [ ] There is a 5 to 50 percent reduction in IOPS when you first access each block of data on a newly created or restored EBS volume.

- - - - - -

