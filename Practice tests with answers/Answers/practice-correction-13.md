### 1
You launch an Amazon EC2 instance without an assigned AVVS identity and Access Management (IAM) role. Later, you decide that the instance should be running with an IAM role. Which action must you take in order to have a running Amazon EC2 instance with an IAM role assigned to it?

- [ ] Create an image of the instance, and register the image with an IAM role assigned and an Amazon EBS volume mapping.
- [ ] Create a new IAM role with the same permissions as an existing IAM role, and assign it to the running instance.
- [ ] Create an image of the instance, add a new IAM role with the same permissions as the desired IAM role, and deregister the image with the new role assigned.
- [x] Create an image of the instance, and use this image to launch a new instance with the desired Lam role assigned.

- - - - - -

### 2
Does AWS Direct Connect allow you access to all Availabilities Zones within a Region?

- [x] Depends on the type of connection.
- [ ] Yes.
- [ ] No.
- [ ] Only when there's just one Availability Zone in a region. If there are more than one, only one availability zone can be accessed directly.

- - - - - -

### 3
What is the durability of S3 RRS?

- [x] 99.99%.
- [ ] 99.95%.
- [ ] 99.995%.
- [ ] 99.999999999%.

- - - - - -

### 4
Your organization is in the business of architecting complex transactional databases. For a variety of reasons, this has been done on EBS. What is AWS's recommendation for customers who have architected databases using EBS for backups?

- [x] Backups to Amazon S3 be performed through the database management system.
- [ ] Backups to AWS Storage Gateway be performed through the database management system.
- [ ] If you take regular snapshots no further backups are required.
- [ ] Backups to Amazon Glacier be performed through the database management system.

- - - - - -

### 5
You need to create a load balancer in a VPC network that you are building. You can make your load balancer internal (private) or internet-facing (public). When you make your load balancer internal, a DNS name will be created, and it will contain the private IP address of the load balancer. An internal load balancer is not exposed to the internet. When you make your load balancer internet-facing, a DNS name will be created with the public IP address. If you want the Internet-facing load balancer to be connected to the Internet, where must this load balancer reside?

- [x] The load balancer must reside in a subnet that is connected to the internet using the internet gateway.
- [ ] The load balancer must reside in a subnet that is not connected to the internet.
- [ ] The load balancer must not reside in a subnet that is connected to the internet.
- [ ] The load balancer must be completely outside of your IP.

- - - - - -

### 6
In the Amazon CloudWatch, which metric should I be checking to ensure that your DB Instance has enough free storage space?

- [ ] Free Storage.
- [x] Free Storage Space.
- [ ] Free Storage Volume.
- [ ] Free DB Storage Space.

- - - - - -

### 7
A web-startup runs its very successful social news application on Amazon EC2 with an Elastic Load Balancer, an Auto-Scaling group of Java/Tomcat application-servers, and DynamoDB as data store. The main web-application best runs on m2 x large instances since it is highly memory- bound Each new deployment requires semi-automated creation and testing of a new AMI for the application servers which takes quite a while ana is therefore only done once per week. Recently, a new chat feature has been implemented in nodejs and wails to be integrated in the architecture. First tests show that the new component is CPU bound Because the company has some experience with using Chef, they decided to streamline the deployment process and use AWS OpsWorks as an application life cycle tool to simplify management of the application and reduce the deployment cycles. What configuration in AWS OpsWorks is necessary to integrate the new chat module in the most cost-efficient and flexible way?

- [ ] Create one AWS OpsWorks stack, create one AWS OpsWorks layer, create one custom recipe.
- [ ] Create one AWS OpsWorks stack create two AWS OpsWorks layers create one custom recipe.
- [x] Create two AWS OpsWorks stacks create two AWS OpsWorks layers create one custom recipe.
- [ ] Create two AWS OpsWorks stacks create two AWS OpsWorks layers create two custom recipe.

- - - - - -

### 8
A client needs you to import some existing infrastructure from a dedicated hosting provider to AWS to try and save on the cost of running his current website. He also needs an automated process that manages backups, software patching, automatic failure detection, and recovery. You are aware that his existing set up currently uses an Oracle database. Which of the following AWS databases would be best for accomplishing this task?

- [x] Amazon RDS.
- [ ] Amazon Redshift.
- [ ] Amazon SimpleDB.
- [ ] Amazon ElastiCache.

- - - - - -

### 9
A user is currently building a website which will require a large number of instances in six months, when a demonstration of the new site will be given upon launch. Which of the below mentioned options allows the user to procure the resources beforehand so that they need not worry about infrastructure availability during the demonstration?

- [x] Procure all the instances as reserved instances beforehand.
- [ ] Launch all the instances as part of the cluster group to ensure resource availability.
- [ ] Pre-warm all the instances one month prior to ensure resource availability.
- [ ] Ask AWS now to procure the dedicated instances in 6 months.

- - - - - -

### 10
Amazon RDS creates an SSL certificate and installs the certificate on the DB Instance when Amazon RDS provisions the instance. These certificates are signed by a certificate authority. The [...] is stored at <https://rds.amazonaws.com/doc/rds-ssl-ca-cert.pem>.

- [x] private key.
- [ ] foreign key.
- [ ] public key.
- [ ] protected key.

- - - - - -

### 11
What happens to data on an ephemeral volume of an EBS-backed EC2 instance if it is terminated or if it fails?

- [ ] Data is automatically copied to another volume.
- [ ] The volume snapshot is saved in S3.
- [ ] Data persists.
- [x] Data is deleted.

- - - - - -

### 12
You manually launch a NAT AMI in a public subnet. The network is properly configured. Security groups and network access control lists are property configured. Instances in a private subnet can access the NAT. The NAT can access the Internet. However, private instances cannot access the Internet. What additional step is required to allow access from the private instances?

- [ ] Enable Source/Destination Check on the private Instances.
- [x] Enable Source/Destination Check on the NAT instance.
- [ ] Disable Source/Destination Check on the private instances.
- [ ] Disable Source/Destination Check on the NAT instance.

- - - - - -

### 13
You have just discovered that you can upload your objects to Amazon S3 using Multipart Upload API. You start to test it out but are unsure of the benefits that it would provide. Which of the following is not a benefit of using multipart uploads?

- [ ] You can begin an upload before you know the final object size.
- [ ] Quick recovery from any network issues.
- [ ] Pause and resume object uploads.
- [x] It's more secure than normal upload.

- - - - - -

### 14
To help you manage your Amazon EC2 instances, images, and other Amazon EC2 resources, you can assign your own metadata to each resource in the form of [...].

- [ ] special filters.
- [ ] functions.
- [x] tags.
- [ ] wildcards.

- - - - - -

### 15
Do the Amazon EBS volumes persist independently from the running life of an Amazon EC2 instance?

- [ ] No.
- [ ] Only if instructed to when created.
- [x] Yes.

- - - - - -

### 16
If I write the below command, what does it do? ec2-run ami-e3a5408a -n 20 -g appserver

- [x] Start twenty instances as members of appserver group.
- [ ] Creates 20 rules in the security group named appserver.
- [ ] Terminate twenty instances as members of appserver group.
- [ ] Start 20 security groups.

- - - - - -

### 17
A company is deploying a new two-tier web application in AWS. The company has limited staff and requires high availability, and the application requires complex queries and table joins. Which configuration provides the solution for the company's requirements?

- [ ] MySQL Installed on two Amazon EC2 Instances in a single Availability Zone.
- [x] Amazon RDS for MySQL with Multi-AZ.
- [ ] Amazon ElastiCache
- [ ] Amazon DynamoDB.

- - - - - -

### 18
In order to optimize performance for a compute cluster that requires low inter-node latency, which of the following feature should you use?

- [ ] Multiple Availability Zones.
- [ ] AWS Direct Connect.
- [ ] EC2 Dedicated Instances.
- [x] Placement Groups.
- [ ] VPC private subnets.

- - - - - -

### 19
Regarding the attaching of ENI to an instance, what does 'warm attach' refer to?

- [x] Attaching an ENI to an instance when it is stopped.
- [ ] This question doesn't make sense.
- [ ] Attaching an ENI to an instance when it is running.
- [ ] Attaching an ENI to an instance during the launch process.

- - - - - -

### 20
Can I attach more than one policy to a particular entity?

- [x] Yes always.
- [ ] Only if within GovCloud.
- [ ] No.
- [ ] Only if within VPC.

- - - - - -

### 21
By default, when an EBS volume is attached to a Windows instance, it may show up as any drive letter on the instance. You can change the settings of the [...] Service to set the drive letters of the EBS volumes per your specifications.

- [ ] EBS Config Service.
- [ ] AMI Config Service.
- [x] EC2 Config Service.
- [ ] EC2-AMI Config Service.

- - - - - -

### 22
Select the correct set of steps for exposing the snapshot only to specific AWS accounts.

- [ ] Select public for all the accounts and check mark t hose accounts with whom you want to expose the snapshots and cl ick save.
- [ ] Select Private, enter the IDs of t hose AWS accounts, and click Save.
- [x] Select Public, enter the IDs of those AWS accounts, and click Save.
- [ ] Select Public, mark the IDs of those AWS accounts as private, and click Save.

- - - - - -

### 23
How can you apply more than 100 rules to an Amazon EC2-Classic?

- [ ] By adding more security groups.
- [ ] You need to create a default security group specifying your required rules if you need to use more than 100 rules per security group.
- [ ] By default the Amazon EC2 security groups support 500 rules.
- [x] You can't add more than 100 rules to security groups for an Amazon EC2 instance.

- - - - - -

### 24
A user has created an ELB with Auto Scaling. Which of the below mentioned offerings from ELB helps the user to stop sending new requests traffic from the load balancer to the EC2 instance when the instance is being deregistered while continuing in-flight requests?

- [ ] ELB sticky session.
- [ ] ELB deregistration check.
- [ ] ELB auto registration Off.
- [x] ELB connection draining.

- - - - - -

### 25
What can I access by visiting the URL: http://status.aws.amazon.com/?

- [ ] Amazon Cloud Watch.
- [ ] Status of the Amazon RDS DB.
- [x] AWS Service Health Dashboard.
- [ ] AWS Cloud Monitor.

- - - - - -

### 26
In Route 53, what does a Hosted Zone refer to?

- [ ] A hosted zone is a collection of geographical load balancing rules for Route 53.
- [x] A hosted zone is a collection of resource record sets hosted by Route 53.
- [ ] A hosted zone is a selection of specific resource record sets hosted by CloudFront for distribution to Route 53.
- [ ] A hosted zone is the Edge Location that hosts the Route 53 records for a user.

- - - - - -

### 27
A user is launching an EC2 instance in the US East region. Which of the below mentioned options is recommended by AWS with respect to the selection of the Availability Zone?

- [ ] Always select the AZ while launching an instance.
- [ ] Always select the US-East-1-a zone for HA.
- [x] Do not select the AZ; instead let AWS select the AZ.
- [ ] The user can never select the Availability Zone while launching an instance.

- - - - - -

### 28
ec2-revoke RevokeSecurityGroup Ingress

- [ ] Removes one or more security groups from a rule.
- [ ] Removes one or more security groups from an Amazon EC2 instance.
- [x] Removes one or more rules from a security group.
- [ ] Removes a security group from our account.

- - - - - -

### 29
Select the correct statement.

- [ ] You don't need not specify the resource identifier while stopping a resource.
- [ ] You can terminate, stop, or delete a resource based solely on its tags.
- [x] You can't terminate, stop, or delete a resource based solely on its tags.
- [ ] You don't need to specify the resource identifier while terminating a resource.

- - - - - -

### 30
What is the time period with which metric data is sent to CloudWatch when detailed monitoring is enabled on an Amazon EC2 instance?

- [ ] 15 minutes.
- [ ] 5 minutes.
- [x] 1 minute.
- [ ] 45 seconds.

- - - - - -

### 31
A large real -estate brokerage is exploring the option of adding a cost-effective location based alert to their existing mobile application The application backend infrastructure currently runs on AWS Users who opt in to this service will receive alerts on their mobile device regarding real-estate otters in proximity to their location. For the alerts to be relevant delivery time needs to be in the low minute count the existing mobile app has 5 million users across the us. Which one of the following architectural suggestions would you make to the customer?

- [x] The mobile application will submit its location to a web service endpoint utilizing Elastic Load Balancing and EC2 instances: DynamoDB will be used to store and retrieve relevant otters EC2 instances will communicate with mobile earners/device providers to push alerts back to mobile application.
- [ ] Use AWS DirectConnect or VPN to establish connectivity with mobile carriers EC2 instances will receive the mobile applications' location through carrier connection: ROS will be used to store and relevant relevant offers EC2 instances will communicate with mobile carriers to push alerts back to the mobile application.
- [ ] The mobile application will send device location using SQS.
- [ ] EC2 instances will retrieve the re levant others from DynamoDB AWS Mobile Push will be used to send offers to the mobile application to push alerts back to the mobile application.
- [ ] The mobile application will send device location using AWS Mobile Push EC2 instances will retrieve the relevant offers from DynamoDB EC2 instances will communicate with mobile carriers/device providers to push alerts back to the mobile application.

- - - - - -

### 32
You are running PostgreSQL on Amazon RDS and it seems to be all running smoothly deployed in one Availability Zone. A database administrator asks you if DB instances running PostgreSQL support Multi-AZ deployments. What would be a correct response to this question?

- [x] Yes.
- [ ] Yes but only for small db instances.
- [ ] No.
- [ ] Yes but you need to request the service from AWS.

- - - - - -

### 33
What is the data model of DynamoDB?

- [ ] Since DynamoDB is schema-less, there is no data model.
- [ ] 'Items', with Keys and one or more Attribute; and 'Attribute', with Name and Value.
- [x] 'Table', a collection of Items; 'Items', with Keys and one or more Attribute; and 'Attribute', with Name and Value.
- [ ] 'Database', which is a set of 'Tables', which is a set of 'Items', which is a set of 'Attributes'.

- - - - - -

### 34
What is a placement group in Amazon EC2?

- [x] It is a group of EC2 instances within a single Availability Zone.
- [ ] It the edge location of your web content.
- [ ] It is the AWS region where you run the EC2 instance of your web content.
- [ ] It is a group used to span multiple Availability Zones.

- - - - - -

### 35
A company is running an SMB file server in its data center. The file server stores large files that are accessed frequently for the first few days after the files are created. After 7 days the files are rarely accessed. The total data size is increasing and is close to the company's total storage capacity. A solutions architect must increase the company's available storage space without losing low-latency access to the most recently accessed files. The solutions architect must also provide file lifecycle management to avoid future storage issues.Which solution will meet these requirements?

- [ ] Use AWS DataSync to copy data that is older than 7 days from the SMB file server to AWS.
- [ ] Create an Amazon S3 File Gateway to extend the company's storage space. Create an S3 Lifecycle policy to transition the data to S3 Glacier Deep Archive after 7 days.
- [ ] Create an Amazon FSx for Windows File Server file system to extend the company's storage space.
- [x] Install a utility on each user's computer to access Amazon S3. Create an S3 Lifecycle policy to transition the data to S3 Glacier Flexible Retrieval after 7 days.

- - - - - -

### 36
A large company wants to provide its globally located developers separate, limited size, managed PostgreSQL databases for development purposes. The databases will be low volume. The developers need the databases only when they are actively working.Which solution will meet these requirements MOST cost-effectively?

- [ ] Give the developers the ability to launch separate Amazon Aurora instances. Set up a process to shut down Aurora instances at the end of the workday and to start Aurora instances at the beginning of the next workday.
- [ ] Develop an AWS Service Catalog product that enforces size restrictions for launching Amazon Aurora instances. Give the developers access to launch the product when they need a development database.
- [x] Create an Amazon Aurora Serverless cluster. Develop an AWS Service Catalog product to launch databases in the cluster with the default capacity settings. Grant the developers access to the product.
- [ ] Monitor AWS Trusted Advisor checks for idle Amazon RDS databases. Create a process to terminate identified idle RDS databases.

- - - - - -

### 37
A company is building a web application that serves a content management system. The content management system runs on Amazon EC2 instances behind an Application Load Balancer (ALB). The EC2 instances run in an Auto Scaling group across multiple Availability Zones. Users are constantly adding and updating files, blogs, and other website assets in the content management system. A solutions architect must implement a solution in which all the EC2 instances share up-to-date website content with the least possible lag time. Which solution meets these requirements?

- [ ] Update the EC2 user data in the Auto Scaling group lifecycle policy to copy the website assets from the EC2 instance that was launched most recently. Configure the ALB to make changes to the website assets only in the newest EC2 instance.
- [x] Copy the website assets to an Amazon Elastic File System (Amazon EFS) file system. Configure each EC2 instance to mount the EFS file system locally. Configure the website hosting application to reference the website assets that are stored in the EFS file system.
- [ ] Copy the website assets to an Amazon S3 bucket. Ensure that each EC2 instance downloads the website assets from the S3 bucket to the attached Amazon Elastic Block Store (Amazon EBS) volume. Run the S3 sync command once each hour to keep files up to date.
- [ ] Restore an Amazon Elastic Block Store (Amazon EBS) snapshot with the website assets. Attach the EBS snapshot as a secondary EBS volume when a new EC2 instance is launched. Configure the website hosting application to reference the website assets that are stored in the secondary EBS volume.

- - - - - -

### 38
A company's web application consists of multiple Amazon EC2 instances that run behind an Application Load Balancer in a VPC. An Amazon RDS for MySQL DB instance contains the data. The company needs the ability to automatically detect and respond to suspicious or unexpected behavior in its AWS environment. The company already has added AWS WAF to its architecture. What should a solutions architect do next to protect against threats?

- [x] Use Amazon GuardDuty to perform threat detection. Configure Amazon EventBridge (Amazon CloudWatch Events) to filter for GuardDuty findings and to invoke an AWS Lambda function to adjust the AWS WAF rules.
- [ ] Use AWS Firewall Manager to perform threat detection. Configure Amazon EventBridge (Amazon CloudWatch Events) to filter for Firewall Manager findings and to invoke an AWS Lambda function to adjust the AWS WAF web ACL.
- [ ] Use Amazon Inspector to perform threat detection and to update the AWS WAF rules. Create a VPC network ACL to limit access to the web application.
- [ ] Use Amazon Macie to perform threat detection and to update the AWS WAF rules. Create a VPC network ACL to limit access to the web application.

- - - - - -

### 39
A company is planning to run a group of Amazon EC2 instances that connect to an Amazon Aurora database. The company has built an AWS CloudFormation template to deploy the EC2 instances and the Aurora DB cluster. The company wants to allow the instances to authenticate to the database in a secure way. The company does not want to maintain static database credentials. Which solution meets these requirements with the LEAST operational effort?

- [ ] Create a database user with a user name and password. Add parameters for the database user name and password to the CloudFormation template. Pass the parameters to the EC2 instances when the instances are launched.
- [ ] Create a database user with a user name and password. Store the user name and password in AWS Systems Manager Parameter Store. Configure the EC2 instances to retrieve the database credentials from Parameter Store.
- [x] Configure the DB cluster to use IAM database authentication. Create a database user to use with IAM authentication. Associate a role with the EC2 instances to allow applications on the instances to access the database.
- [ ] Configure the DB cluster to use IAM database authentication with an IAM user. Create a database user that has a name that matches the IAM user. Associate the IAM user with the EC2 instances to allow applications on the instances to access the database.

- - - - - -

### 40
A company wants to configure its Amazon CloudFront distribution to use SSL/TLS certificates. The company does not want to use the default domain name for the distribution. Instead, the company wants to use a different domain name for the distribution. Which solution will deploy the certificate without incurring any additional costs?

- [ ] Request an Amazon issued private certificate from AWS Certificate Manager (ACM) in the us-east-1 Region.
- [ ] Request an Amazon issued private certificate from AWS Certificate Manager (ACM) in the us-west-1 Region.
- [x] Request an Amazon issued public certificate from AWS Certificate Manager (ACM) in the us-east-1 Region.
- [ ] Request an Amazon issued public certificate from AWS Certificate Manager (ACM) in the us-west-1 Region.

- - - - - -

### 41
A company creates operations data and stores the data in an Amazon S3 bucket. For the company's annual audit, an external consultant needs to access an annual report that is stored in the S3 bucket. The external consultant needs to access the report for 7 days. The company must implement a solution to allow the external consultant access to only the report. Which solution will meet these requirements with the MOST operational efficiency?

- [ ] Create a new S3 bucket that is configured to host a public static website. Migrate the operations data to the new S3 bucket. Share the S3 website URL with the external consultant.
- [ ] Enable public access to the S3 bucket for 7 days. Remove access to the S3 bucket when the external consultant completes the audit.
- [ ] Create a new IAM user that has access to the report in the S3 bucket. Provide the access keys to the external consultant. Revoke the access keys after 7 days.
- [x] Generate a presigned URL that has the required access to the location of the report on the S3 bucket. Share the presigned URL with the external consultant.

- - - - - -

### 42
A company plans to run a high performance computing (HPC) workload on Amazon EC2 Instances. The workload requires low-latency network performance and high network throughput with tightly coupled node-to-node communication. Which solution will meet these requirements?

- [x] Configure the EC2 instances to be part of a cluster placement group.
- [ ] Launch the EC2 instances with Dedicated Instance tenancy.
- [ ] Launch the EC2 instances as Spot Instances.
- [ ] Configure an On-Demand Capacity Reservation when the EC2 instances are launched.

- - - - - -

### 43
A company has primary and secondary data centers that are 500 miles (804.7 km) apart and interconnected with high-speed fiber-optic cable. The company needs a highly available and secure network connection between its data centers and a VPC on AWS for a mission-critical workload. A solutions architect must choose a connection solution that provides maximum resiliency. Which solution meets these requirements?

- [ ] Two AWS Direct Connect connections from the primary data center terminating at two Direct Connect locations on two separate devices.
- [ ] A single AWS Direct Connect connection from each of the primary and secondary data centers terminating at one Direct Connect location on the same device.
- [x] Two AWS Direct Connect connections from each of the primary and secondary data centers terminating at two Direct Connect locations on two separate devices.
- [ ] A single AWS Direct Connect connection from each of the primary and secondary data centers terminating at one Direct Connect location on two separate devices.

- - - - - -

### 44
A company runs several Amazon RDS for Oracle On-Demand DB instances that have high utilization. The RDS DB instances run in member accounts that are in an organization in AWS Organizations. The company's finance team has access to the organization's management account and member accounts. The finance team wants to find ways to optimize costs by using AWS Trusted Advisor. Which combination of steps will meet these requirements? (Choose two.)

- [x] Use the Trusted Advisor recommendations in the management account.
- [ ] Use the Trusted Advisor recommendations in the member accounts where the RDS DB instances are running.
- [x] Review the Trusted Advisor checks for Amazon RDS Reserved Instance Optimization.
- [ ] Review the Trusted Advisor checks for Amazon RDS Idle DB Instances.
- [ ] Review the Trusted Advisor checks for compute optimization. Crosscheck the results by using AWS Compute Optimizer.

- - - - - -

### 45
A solutions architect is creating an application. The application will run on Amazon EC2 instances in private subnets across multiple Availability Zones in a VPC. The EC2 instances will frequently access large files that contain confidential information. These files are stored in Amazon S3 buckets for processing. The solutions architect must optimize the network architecture to minimize data transfer costs. What should the solutions architect do to meet these requirements?

- [x] Create a gateway endpoint for Amazon S3 in the VPC. In the route tables for the private subnets, add an entry for the gateway endpoint.
- [ ] Create a single NAT gateway in a public subnet. In the route tables for the private subnets, add a default route that points to the NAT gateway.
- [ ] Create an AWS PrivateLink interface endpoint for Amazon S3 in the VPC. In the route tables for the private subnets, add an entry for the interface endpoint.
- [ ] Create one NAT gateway for each Availability Zone in public subnets. In each of the route tables for the private subnets, add a default route that points to the NAT gateway in the same Availability Zone.

- - - - - -

### 46
A company wants to relocate its on-premises MySQL database to AWS. The database accepts regular imports from a client-facing application, which causes a high volume of write operations. The company is concerned that the amount of traffic might be causing performance issues within the application. How should a solutions architect design the architecture on AWS?

- [x] Provision an Amazon RDS for MySQL DB instance with Provisioned IOPS SSD storage. Monitor write operation metrics by using Amazon CloudWatch. Adjust the provisioned IOPS if necessary.
- [ ] Provision an Amazon RDS for MySQL DB instance with General Purpose SSD storage. Place an Amazon ElastiCache cluster in front of the DB instance. Configure the application to query ElastiCache instead.
- [ ] Provision an Amazon DocumentDB (with MongoDB compatibility) instance with a memory optimized instance type. Monitor Amazon CloudWatch for performance-related issues. Change the instance class if necessary.
- [ ] Provision an Amazon Elastic File System (Amazon EFS) file system in General Purpose performance mode. Monitor Amazon CloudWatch for IOPS bottlenecks. Change to Provisioned Throughput performance mode if necessary.

- - - - - -

### 47
A company runs an application in the AWS Cloud that generates sensitive archival data files. The company wants to rearchitect the application's data storage. The company wants to encrypt the data files and to ensure that third parties do not have access to the data before the data is encrypted and sent to AWS. The company has already created an Amazon S3 bucket. Which solution will meet these requirements?

- [ ] Configure the S3 bucket to use client-side encryption with an Amazon S3 managed encryption key. Configure the application to use the S3 bucket to store the archival files.
- [ ] Configure the S3 bucket to use server-side encryption with AWS KMS keys (SSE-KMS). Configure the application to use the S3 bucket to store the archival files.
- [ ] Configure the S3 bucket to use dual-layer server-side encryption with AWS KMS keys (SSE-KMS). Configure the application to use the S3 bucket to store the archival files.
- [x] Configure the application to use client-side encryption with a key stored in AWS Key Management Service (AWS KMS). Configure the application to store the archival files in the S3 bucket.

- - - - - -

### 48
A company uses Amazon RDS with default backup settings for its database tier. The company needs to make a daily backup of the database to meet regulatory requirements. The company must retain the backups for 30 days. Which solution will meet these requirements with the LEAST operational overhead?

- [ ] Write an AWS Lambda function to create an RDS snapshot every day.
- [x] Modify the RDS database to have a retention period of 30 days for automated backups.
- [ ] Use AWS Systems Manager Maintenance Windows to modify the RDS backup retention period.
- [ ] Create a manual snapshot every day by using the AWS CLI. Modify the RDS backup retention period.

- - - - - -

### 49
A company is running a multi-tier web application on AWS. The application runs its database tier on Amazon Aurora MySQL. The application and database tiers are in the us-east-1 Region. A database administrator who regularly monitors the Aurora DB cluster finds that an intermittent increase in read traffic is creating high CPUutilization on the read replica and causing increased read latency of the application. What should a solutions architect do to improve read scalability?

- [ ] Reboot the Aurora DB cluster.
- [ ] Create a cross-Region read replica
- [ ] Increase the instance class of the read replica.
- [x] Configure Aurora Auto Scaling for the read replica.

- - - - - -

### 50
A company that runs its application on AWS uses an Amazon Aurora DB cluster as its database. During peak usage hours when multiple users access and read the data, the monitoring system shoes degradation of database performancefor write queries. The company wants to increase the scalability of the application to meet peak usage demands. Which solution will meet these requirements MOST cost effectively?

- [ ] Create a second Aurora DB cluster. Configure a copy job to replicate the users' data to the new database. Update the application to use the second database to read the data.
- [ ] Create an Amazon DynamoDB Accelerator (DAX) cluster in front of the existing Aurora DB cluster. Update the application to use the DAX cluster for read-only queries. Write data directly to the Aurora DB cluster.
- [x] Create an Aurora read replica in the existing Aurora DB clu ster. Update tyhe applicatio nto uyser the replica endpoint for read only queries and to use the cluster endpoint for write queries.
- [ ] Create an Amazon Redshift cluster. Copy the users' data to the Redshift cluster. Update the application to connect to the Redshift cluster and to perform read-only queries on the Redshift cluster.

- - - - - -

