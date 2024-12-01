### 1
A customer has a 10 GB AWS Direct Connect connection to an AWS region where they have a web application hosted on Amazon Elastic Computer Cloud (EC2). The application has dependencies on an on-premises mainframe database that uses a BASE (Basic Available. Sort stale Eventual consistency) rather than an ACID (Atomicity. Consistency isolation. Durability) consistency model. The application is exhibiting undesirable behavior because the database is not able to handle the volume of writes. How can you reduce the load on your on-premises database resources in the most cost-effective way?

- [x] Use an Amazon Elastic MapReduce (EMR) S3DistCp as a synchronization mechanism between the on-premises database and a Hadoop cluster on AWS.
- [ ] Modify the application to write to an Amazon SQS queue and develop a worker process to flush the queue to the on-premises database.
- [ ] Modify the application to use DynamoDB to feed an EMR cluster which uses a map function to write to the on-premises database.
- [ ] Provision an RDS read-replica database on AWS to handle the writes and synchronize the two databases using Data Pipeline.

- - - - - -

### 2
You are very concerned about security on your network because you have multiple programmers testing APIs and SDKs and you have no idea what is happening. You think CloudTrail may help but are not sure what it does. Which of the following statements best describes the AWS service CloudTrail?

- [x] With AWS CloudTrail you can get a history of AWS API calls and related events for your account.
- [ ] With AWS CloudTrail you can get a history of IAM users for your account.
- [ ] With AWS CloudTrail you can get a history of S3 logfiles for your account.
- [ ] With AWS CloudTrail you can get a history of CloudFormation JSON scripts used for your account.

- - - - - -

### 3
Every user you create in the IAM system starts with [...].

- [ ] partial permissions.
- [ ] full permissions.
- [x] no permissions.

- - - - - -

### 4
Amazon S3 allows you to set per-file permissions to grant read and/or write access. However you have decided that you want an entire bucket with 100 files already in it to be accessible to the public. You don't want to go through 100 files individually and set permissions. What would be the best way to do this?

- [ ] Move the bucket to a new region.
- [x] Add a bucket policy to the bucket.
- [ ] Move the files to a new bucket.
- [ ] Use Amazon EBS instead of S3.

- - - - - -

### 5
You are designing an SSUTLS solution that requires HTTPS clients to be authenticated by the Web server using client certificate authentication. The solution must be resilient. Which of the following options would you consider for configuring the web server infrastructure? (Choose 2 answers)

- [x] Configure ELB with TCP listeners on TCP/4d3. And place the Web servers behind it.
- [x] Configure your Web servers with EIPS Place the Web servers in a Route 53 Record Set and configure health checks against all Web servers.
- [ ] Configure ELB with HTTPS listeners, and place the Web servers behind it.
- [ ] Configure your web servers as the origins for a CloudFront distribution. Use custom SSL certificates on your CloudFront distribution.

- - - - - -

### 6
Which of the following are use cases for Amazon DynamoDB? (Choose 3 answers)

- [ ] Storing BLOB data.
- [ ] Managing web sessions.
- [x] Storing JSON documents.
- [ ] Storing metadata for Amazon S3 objects.
- [x] Running relational joins and complex updates.
- [x] Storing large amounts of infrequently accessed data.

- - - - - -

### 7
You have been asked to set up a database in AWS that will require frequent and granular updates. You know that you will require a reasonable amount of storage space but are not sure of the best option. What is the recommended storage option when you run a database on an instance with the above criteria?

- [ ] Amazon S3.
- [x] Amazon EBS.
- [ ] AWS Storage Gateway.
- [ ] Amazon Glacier.

- - - - - -

### 8
An application hosted at the EC2 instance receives an HTTP request from ELB. The same request has an X-Forwarded-For header, which has three IP addresses. Which system's IP will be a part of this header?

- [ ] Previous Request IP address.
- [ ] Client IP address.
- [x] All of the answers listed here.
- [ ] Load Balancer IP address.

- - - - - -

### 9
An organization has developed a mobile application which allows end users to capture a photo on their mobile device, and store it inside an application. The application internally uploads the data to AWS S3. The organization wants each user to be able to directly upload data to S3 using their Google ID. How will the mobile app allow this?

- [x] Use the AWS Web identity federation for mobile applications, and use it to generate temporary security credentials for each user.
- [ ] It is not possible to connect to AWS S3 with a Google I
- [ ] Create an IAM user every time a user registers with their Google ID and use IAM to upload files to S3.
- [ ] Create a bucket policy with a condition which allows everyone to upload if the login ID has a Google part to it.

- - - - - -

### 10
You must increase storage size in increments of at least [...].

- [ ] 40.
- [ ] 20.
- [ ] 50.
- [x] 10.

- - - - - -

### 11
You need to set up a security certificate for a client's e-commerce website as it will use the HTTPS protocol. Which of the below AWS services do you need to access to manage your SSL server certificate?

- [ ] AWS Directory Service.
- [x] AWS Identity & Access Management.
- [ ] AWS CloudFormation.
- [ ] Amazon Route 53.

- - - - - -

### 12
After setting up a Virtual Private Cloud (VPC) network, a more experienced cloud engineer suggests that to achieve low network latency and high network throughput you should look into setting up a placement group. You know nothing about this, but begin to do some research about it and are especially curious about its limitations. Which of the below statements is wrong in describing the limitations of a placement group?

- [ ] Although launching multiple instance types into a placement group is possible, this reduces the likelihood that the required capacity will be available for your launch to succeed.
- [x] A placement group can span multiple Availability Zones.
- [ ] You can't move an existing instance into a placement group.
- [ ] A placement group can span peered VPCs.

- - - - - -

### 13
True or False: When you perform a restore operation to a point in time or from a DB Snapshot, a new DB Instance is created with a new endpoint.

- [x] True.
- [ ] False.

- - - - - -

### 14
What is the Reduced Redundancy option in Amazon S3?

- [x] Less redundancy for a lower cost.
- [ ] It doesn't exist in Amazon S3, but in Amazon EBS.
- [ ] It allows you to destroy any copy of your files outside a specific jurisdiction.
- [ ] It doesn't exist at all.

- - - - - -

### 15
You are setting up your first Amazon Virtual Private Cloud (Amazon VPC) so you decide to use the VPC wizard in the AWS console to help make it easier for you. Which of the following statements is correct regarding instances that you launch into a default subnet via the VPC wizard?

- [ ] Instances that you launch into a default subnet receive a public IP address and 10 private IP addresses.
- [x] Instances that you launch into a default subnet receive both a public IP address and a private IP address.
- [ ] Instances that you launch into a default subnet don't receive any ip addresses and you need to define them manually.
- [ ] Instances that you launch into a default subnet receive a public IP address and 5 private IP addresses.

- - - - - -

### 16
For which of the following use cases are Simple Workflow Service (SWF) and Amazon EC2 an appropriate solution? (Choose 2 answers)

- [ ] Using as an endpoint to collect thousands of data points per hour from a distributed fleet of sensors.
- [x] Managing a multi-step and multi-decision checkout process of an e-commerce website.
- [x] Orchestrating the execution of distributed and auditable business processes.
- [ ] Using as an SNS (Simple Notification Service) endpoint to trigger execution of video transcoding jobs.
- [ ] Using as a distributed session store for your web application.

- - - - - -

### 17
Which of the following instance types are available as Amazon EBS-backed only? (Choose 2 answers)

- [x] General purpose T2.
- [ ] General purpose M3.
- [ ] Compute-optimized C4.
- [x] Compute-optimized C3.
- [ ] Storage-optimized 12.

- - - - - -

### 18
True or False: Without IAM, you cannot control the tasks a particular user or system can do and what AWS resources they might use.

- [ ] True.
- [x] False.

- - - - - -

### 19
What does Amazon ELB stand for?

- [ ] Elastic Linux Box.
- [ ] Encrypted Linux Box.
- [ ] Encrypted Load Balancing.
- [x] Elastic Load Balancing.

- - - - - -

### 20
A read only news reporting site with a combined web and application tier and a database tier that receives large and unpredictable traffic demands must be able to respond to these traffic fluctuations automatically. What AWS services should be used meet these requirements?

- [x] Stateless instances for the web and application tier synchronized using Elasticache Memcached in an autoscaimg group monitored with CloudWatch. And RDSwith read replicas.
- [ ] Stateful instances for the web and application tier in an autoscaling group monitored with CloudWatch and RDS with read replicas.
- [ ] Stateful instances for the web and application tier in an autoscaling group monitored with CloudWatch and multi-AZ RDS.
- [ ] Stateless instances for the web and application tier synchronized using ElastiCache Memcached in an autoscaling group monitored with CloudWatch and multi-AZ RDS.

- - - - - -

### 21
In Amazon AWS, which of the following statements is true of key pairs?

- [ ] Key pairs are used only for Amazon SDKs.
- [x] Key pairs are used only for Amazon EC2 and Amazon CloudFront.
- [ ] Key pairs are used only for Elastic Load Balancing and AWS IA.
- [ ] Key pairs are used for all Amazon services.

- - - - - -

### 22
What does Amazon ElastiCache provide?

- [ ] A service by this name doesn't exist. Perhaps you mean Amazon CloudCache.
- [ ] A virtual server with a huge amount of memory.
- [x] A managed In-memory cache service.
- [ ] An Amazon EC2 instance with the Memcached software already pre-installed.

- - - - - -

### 23
What are the two permission types used by AWS?

- [ ] Resource-based and Product-based.
- [ ] Product-based and Service-based.
- [ ] Service-based.
- [x] User-based and Resource-based.

- - - - - -

### 24
In AWS CloudHSM, in addition to the AWS recommendation that you use two or more HSM appliances in a high-availability configuration to prevent the loss of keys and data, you can also perform a remote backup/restore of a Luna SA partition if you have purchased a:

- [ ] Luna Restore HS.
- [x] Luna Backup HS.
- [ ] Luna HS.
- [ ] Luna SA HS.

- - - - - -

### 25
An organization has a statutory requirement to protect the data at rest for the S3 objects. Which of the below mentioned options need not be enabled by the organization to achieve data security?

- [ ] MFA delete for S3 objects.
- [ ] Client side encryption.
- [ ] Bucket versioning.
- [x] Data replication.

- - - - - -

### 26
Your company is in the process of developing a next generation pet collar that collects biometric information to assist families with promoting healthy lifestyles for their pets Each collar will push 30kb of biometric data in JSON format every 2 seconds to a collection platform that will process and analyze the data providing health trending information back to the pet owners and veterinarians via a web portal Management has tasked you to architect the collection platform ensuring the following requirements are met. Provide the ability for real-time analytics of the inbound biometric data. Ensure processing of the biometric data is highly durable. Elastic and parallel. The results of the analytic processing should be persisted for data mining. Which architecture outlined below win meet the initial requirements for the collection platform?

- [ ] Utilize S3 to collect the inbound sensor data analyze the data from S3 with a daily scheduled Data Pipeline and save the results to a Redshift Cluster.
- [x] Utilize Amazon Kinesis to collect the inbound sensor data, analyze the data with Kinesis clients and save the results to a Red shift cluster using EMR.
- [ ] Utilize SQS to collect the inbound sensor data analyze the data from SQS with Amazon Kinesis and save the results to a Microsoft SQL Server RDS instance.
- [ ] Utilize EMR to collect the inbound sensor data, analyze the data from EUR with Amazon Kinesis and save me results to Dynamo DB.

- - - - - -

### 27
Which of the following approaches provides the lowest cost for Amazon Elastic Block Store snapshots while giving you the ability to fully restore data?

- [x] Maintain two snapshots: the original snapshot and the latest incremental snapshot.
- [ ] Maintain a volume snapshot; subsequent snapshots will overwrite one another
- [ ] Maintain a single snapshot the latest snapshot is both Incremental and complete.
- [ ] Maintain the most current snapshot, archive the original and incremental to Amazon Glacier.

- - - - - -

### 28
You have a video transcoding application running on Amazon EC2. Each instance pol ls a queue to find out which video should be transcoded, and then runs a transcoding process. If this process is interrupted, the video will be transcoded by another instance based on the queuing system. You have a large backlog of videos which need to be transcoded and would like to reduce this backlog by adding more instances. You will need these instances only until the backlog is reduced. Which type of Amazon EC2 instances should you use to reduce the backlog in the most cost efficient way?

- [ ] Reserved instances.
- [x] Spot instances.
- [ ] Dedicated instances.
- [ ] On-demand instances.

- - - - - -

### 29
What does the AWS Storage Gateway provide?

- [x] It allows to integrate on-premises IT environments with Cloud Storage.
- [ ] A direct encrypted connection to Amazon S3.
- [ ] It's a backup solution that provides an on-premises Cloud storage.
- [ ] It provides an encrypted SSL endpoint for backups in the Cloud.

- - - - - -

### 30
You have recently joined a startup company building sensors to measure street noise and air quality in urban areas. The company has been running a pilot deployment of around 100 sensors for 3 months each sensor uploads 1KB of sensor data every minute to a backend hosted on AWS. During the pilot, you measured a peak or 10 IOPS on the database, and you stored an average of 3GB of sensor data per month in the database. The current deployment consists of a load-balanced auto scaled Ingestion layer using EC2 instances and a PostgreSQL RDS database with 500GB standard storage. The pilot is considered a success and your CEO has managed to get the attention or some potential investors. The business plan requires a deployment of at least lOOK sensors which needs to be supported by the backend. You also need to store sensor data for at least two years to be able to compare year over year Improvements. To secure funding, you have to make sure that the platform meets these requirements and leaves room for further scaling. Which setup win meet the requirements?

- [ ] Add an SQS queue to the ingestion layer to buffer writes to the RDS instance.
- [ ] Ingest data into a DynamoDB table and move old data to a Redshift cluster.
- [x] Replace the RDS instance with a 6 node Redshift cluster with 96TB of storage.
- [ ] Keep the current architecture but upgrade RDS storage to 3TB and lOK provisioned IOPS.

- - - - - -

### 31
After a major security breach your manager has requested a report of all users and their credentials in AWS. You discover that in IAM you can generate and download a credential report that lists all users in your account and the status of their various credentials, including passwords, access keys, MFA devices, and signing certificates. Which following statement is incorrect in regards to the use of credential reports?

- [x] Credential reports are downloaded XML files.
- [ ] You can get a credential report using the AWS Management Console, the AWS CLI, or the IAM API.
- [ ] You can use the report to audit the effects of credential lifecycle requirements, such as password rotation.
- [ ] You can generate a credential report as often as once every four hours.

- - - - - -

### 32
What is the maximum response time for a Business level Premium Support case?

- [ ] 30 minutes.
- [x] 1 hour.
- [ ] 12 hours.
- [ ] 10 minutes.

- - - - - -

### 33
Per the AWS Acceptable Use Policy, penetration testing of EC2 instances

- [ ] May be performed by AWS, and will be performed by AWS upon customer request.
- [x] May be performed by AWS, and is periodically performed by AWS.
- [ ] Are expressly prohibited under all circumstances.
- [ ] May be performed by the customer on their own instances with prior authorization from AWS.
- [ ] May be performed by the customer on their own instances, only if performed from EC2 instances.

- - - - - -

### 34
Which of the following features are provided by Amazon EC2?

- [ ] Exadata Database Machine, Optimized Storage Management, Flashback Technology, and Data Warehousing.
- [x] Instances, Amazon Machine Images (AMIs), Key Pairs, Amazon EBS Volumes, Firewall, Elastic IP address, Tags, and Virtual Private Clouds (VPCs).
- [ ] Real Application Clusters (RAC), Elasticache Machine Images (EMIs), Data Warehousing, Flashback Technology, Dynamic IP address.
- [ ] Exadata Database Machine, Real Application Clusters (RAC), Data Guard, Table and Index Partitioning, and Data Pump Compression.

- - - - - -

### 35
True or False: If you add a tag that has the same key as an existing tag on a DB Instance, the new value overwrites the old value.

- [x] True.
- [ ] False.

- - - - - -

### 36
You decide that you need to create a number of Auto Scaling groups to try and save some money as you have noticed that at certain times most of your EC2 instances are not being used. By default, what is the maximum number of Auto Scaling groups that AWS will allow you to create?

- [ ] 12.
- [ ] Unlimited.
- [x] 20.
- [ ] 2.

- - - - - -

### 37
After moving an E-Commerce website for a client from a dedicated server to AWS you have also set up auto scaling to perform health checks on the instances in your group and replace instances that fail these checks. Your client has come to you with his own health check system that he wants you to use as it has proved to be very useful prior to his site running on AWS. What do you think would be an appropriate response to this given all that you know about auto scaling?

- [ ] It is not possible to implement your own health check system. You need to use AWSs health check system.
- [ ] It is not possible to implement your own health check system due to compatibility issues.
- [x] It is possible to implement your own health check system and then send the instance's health information directly from your system to Cloud Watch.
- [ ] It is possible to implement your own health check system and then send the instance's health information directly from your system to Cloud Watch but only in the US East (Virginia) region.

- - - - - -

### 38
You've been brought in as solutions architect to assist an enterprise customer with their migration of an e-commerce platform to Amazon Virtual Private Cloud (VPC) The previous architect has already deployed a 3-tier VPC, The configuration is as follows. VPC: vpc-2f8bc447. IGW: igw-2d8bc445. NACL: ad-208bc448. 5ubnets and Route Tables: Web servers: subnet-258bc44d. Application servers: subnet-248bc44c. Database servers: subnet-9189c6f9. Route Tables: rrb-218bc449, rtb-238bc44b. Associations: subnet-258bc44d: rtb-218bc449, subnet-248bc44c: rtb-238bc44b, subnet-9189c6f9: rtb-238bc44b. You are now ready to begin deploying EC2 instances into the VPC Web servers must have direct access to the internet Application and database servers cannot have direct access to the internet. Which configuration below will allow you the ability to remotely administer your application and database servers, as well as allow these servers to retrieve updates from the Internet?

- [x] Create a bastion and NAT instance in subnet-258bc44d, and add a route from rtb- 238bc44b to the NAT instance.
- [ ] Add a route from rtb-238bc44b to igw-2d8bc445 and add a bastion and NAT instance within subnet-248bc44c.
- [ ] Create a bastion and NAT instance in subnet-248bc44c, and add a route from rtb- 238bc44b to subnet-258bc44d.
- [ ] Create a bastion and NAT instance in subnet-258bc44d, add a route from rtb-238bc44b to lgw- 2d8bc445, and a new NACL that allows access between subnet-258bc44d and subnet -248bc44c.

- - - - - -

### 39
After deciding that EMR will be useful in analysing vast amounts of data for a gaming website that you are architecting you have just deployed an Amazon EMR Cluster and wish to monitor the cluster performance. Which of the following tools cannot be used to monitor the cluster performance?

- [x] Kinesis.
- [ ] Ganglia.
- [ ] CloudWatch Metrics.
- [ ] Hadoop Web Interfaces.

- - - - - -

### 40
A/An [...] is the concept of allowing (or disallowing) an entity such as a user, group, or role some type of access to one or more resources.

- [ ] user.
- [x] AWS Account.
- [ ] resource.
- [ ] permission.

- - - - - -

### 41
You are running a successful multitier web application on AWS and your marketing department has asked you to add a reporting tier to the application. The reporting tier will aggregate and publish status reports every 30 minutes from user-generated information that is being stored in your web application s database. You are currently running a Multi-AZ RDS MySQL instance for the database tier. You also have implemented Elasticache as a database caching layer between the application tier and database tier. Please select the answer that will allow you to successful ly implement the reporting tier with as little impact as possible to your database.

- [ ] Continually send transaction logs from your master database to an S3 bucket and generate the reports off the S3 bucket using S3 byte range requests.
- [ ] Generate the reports by querying the synchronously replicated standby RDS MySQL instance maintained through Multi-AZ.
- [x] Launch a RDS Read Replica connected to your Multi-AZ master database and generate reports by querying the Read Replica.
- [ ] Generate the reports by querying the ElastiCache database caching tier.

- - - - - -

### 42
Can I delete a snapshot of the root device of an EBS volume used by a registered AMI?

- [ ] Only via API.
- [ ] Only via Console.
- [x] Yes.
- [ ] No.

- - - - - -

### 43
MySQL installations default to port [...].

- [x] 3306.
- [ ] 443.
- [ ] 80.
- [ ] 1158.

- - - - - -

### 44
In the 'Detailed ' monitoring data available for your Amazon EBS volumes, Provisioned IOPS volumes automatically send [...] minute metrics to Amazon CloudWatch.

- [ ] 5.
- [ ] 2.
- [x] 1.
- [ ] 3.

- - - - - -

### 45
A user has deployed an application on his private cloud. The user is using his own monitoring tool. He wants to configure it so that whenever there is an error, the monitoring tool will notify him via SMS. Which of the below mentioned AWS services will help in this scenario?

- [ ] AWS SES.
- [x] AWS SNS.
- [ ] None because the user infrastructure is in the private cloud.
- [ ] AWS SMS.

- - - - - -

### 46
What does Amazon Route 53 provide?

- [ ] A global Content Delivery Network.
- [ ] None of these.
- [x] A scalable Domain Name System.
- [ ] An SSH endpoint for Amazon EC2.

- - - - - -

### 47
The AWS CloudHSM service defines a resource known as a high-availability (HA) [...], which is a virtual partition that represents a group of partitions, typically distributed between several physical HSMs for high-availability.

- [ ] proxy group.
- [x] partition group.
- [ ] functional group.
- [ ] relational group.

- - - - - -

### 48
In Amazon EC2, partial instance-hours are billed [...].

- [ ] per second used in the hour.
- [ ] per minute used.
- [ ] by combining partial segments into full hours.
- [x] as full hours.

- - - - - -

### 49
In Amazon EC2, what is the limit of Reserved Instances per Availability Zone each month?

- [ ] 5.
- [x] 20.
- [ ] 50.
- [ ] 10.

- - - - - -

### 50
True or False: When using IAM to control access to your RDS resources, the key names that can be used are case sensitive. For example, aws: CurrentTime is NOT equivalent to AWS: currenttime.

- [x] True.
- [ ] False.

- - - - - -

