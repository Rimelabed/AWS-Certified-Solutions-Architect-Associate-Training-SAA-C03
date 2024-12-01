### 1
In regards to IAM you can edit user properties later, but you cannot use the console to change the [...].

- [x] user name.
- [ ] password.
- [ ] default group.

- - - - - -

### 2
In Amazon EC2 Container Service, are other container types supported?

- [ ] Yes, EC2 Container Service supports any container service you need.
- [ ] Yes, EC2 Container Service also supports Microsoft container service.
- [x] No, Docker is the only container platform supported by EC2 Container Service presently.
- [ ] Yes, EC2 Container Service supports Microsoft container service and Openstack.

- - - - - -

### 3
Content and Media Server is the latest requirement that you need to meet for a client. The client has been very specific about his requirements such as low latency, high availability, durability, and access control. Potentially there will be millions of views on this server and because of 'spiky' usage patterns, operations teams will need to provision static hardware, network, and management resources to support the maximum expected need. The Customer base will be initially low but is expected to grow and become more geographically distributed. Which of the following would be a good solution for content distribution?

- [ ] Amazon S3 as both the origin server and for caching.
- [ ] AWS Storage Gateway as the origin server and Amazon EC2 for caching.
- [ ] AWS CloudFront as both the origin server and for caching.
- [x] Amazon S3 as the origin server and Amazon CloudFront for caching.

- - - - - -

### 4
Name the disk storage supported by Amazon Elastic Compute Cloud (EC2)

- [ ] None of these.
- [ ] Amazon AppStream store.
- [ ] Amazon SNS store.
- [x] Amazon Instance Store.

- - - - - -

### 5
After an Amazon VPC instance is launched, can I change the VPC security groups it belongs to?

- [ ] Only if the tag 'VPC_Change_Group' is true.
- [x] Yes. You can.
- [ ] No. You cannot.
- [ ] Only if the tag 'VPC Change Group' is true.

- - - - - -

### 6
If I want an instance to have a public IP address, which IP address should I use?

- [x] Elastic IP Address.
- [ ] Class B IP Address.
- [ ] Class A IP Address.
- [ ] Dynamic IP Address.

- - - - - -

### 7
Amazon RDS supports SOAP only through [...].

- [ ] HTTP or HTTPS.
- [ ] TCP/IP.
- [ ] HTTP.
- [x] HTTPS.

- - - - - -

### 8
Which of the following services natively encrypts data at rest within an AWS region? (Choose 2 answers)

- [x] AWS Storage Gateway.
- [ ] Amazon DynamoDB.
- [ ] Amazon CloudFront.
- [x] Amazon Glacier.
- [ ] Amazon Simple Queue Service.

- - - - - -

### 9
Which one of the following can't be used as an origin server with Amazon CloudFront?

- [ ] A web server running in your infrastructure.
- [ ] Amazon S3.
- [x] Amazon Glacier.
- [ ] A web server running on Amazon EC2 instances.

- - - - - -

### 10
Select the most correct The device name /dev/sdal (within Amazon EC2) is [...].

- [ ] possible for EBS volumes.
- [x] reserved for the root device.
- [ ] recommended for EBS volumes.
- [ ] recommended for instance store volumes.

- - - - - -

### 11
How can I change the security group membership for interfaces owned by other AWS, such as Elastic Load Balancing?

- [x] By using the service specific console or APICLI commands.
- [ ] None of these.
- [ ] Using Amazon EC2 API/CLI.
- [ ] Using all these methods.

- - - - - -

### 12
You have created a Route 53 latency record set from your domain to a machine in Northern Virginia and a similar record to a machine in Sydney. When a user located in US visits your domain he will be routed to

- [x] Northern Virginia.
- [ ] Sydney.
- [ ] Both, Northern Virginia and Sydney.
- [ ] Depends on the Weighted Resource Record Sets.

- - - - - -

### 13
In the context of MySQL, version numbers are organized as MySQL version = X.Y.Z. What does X denote here?

- [ ] Release level.
- [ ] Minor version.
- [ ] Version number.
- [x] Major version.

- - - - - -

### 14
Which one of the below doesn't affect Amazon CloudFront billing?

- [x] Distribution Type.
- [ ] Data Transfer Out.
- [ ] Dedicated IP SSL Certificates.
- [ ] Requests.

- - - - - -

### 15
Just when you thought you knew every possible storage option on AWS you hear someone mention Reduced Redundancy Storage (RRS) within Amazon S3. What is the ideal scenario to use Reduced Redundancy Storage (RRS)?

- [ ] Huge volumes of data.
- [ ] Sensitive data.
- [x] Non-critical or reproducible data.
- [ ] Critical data.

- - - - - -

### 16
$ aws sqs receive-message –queue-url <https://queue.amazonaws.com/546419318123/Test>

- [x] 3.
- [ ] 4.
- [ ] 2.
- [ ] 1.

- - - - - -

### 17
When running my DB Instance as a Multi-AZ deployment, can I use the standby for read or write operations?

- [ ] Yes.
- [ ] Only with MSSQL based RDS.
- [ ] Only for Oracle RDS instances.
- [x] No.

- - - - - -

### 18
In the Launch Db Instance Wizard, where can I select the backup and maintenance options?

- [ ] Under DB INSTANCE DETAILS.
- [ ] Under REVI EW.
- [x] Under MANAGEMENT OPTIONS.
- [ ] Under ENGINE SELECTION.

- - - - - -

### 19
What is the network performance offered by the c4.8xlarge instance in Amazon EC2?

- [ ] 20 Gigabit.
- [x] 10 Gigabit.
- [ ] Very High but variable.
- [ ] 5 Gigabit.

- - - - - -

### 20
In Amazon EC2, if your EBS volume stays in the detaching state, you can force the detachment by clicking [...].

- [x] Force Detach.
- [ ] Detach Instance.
- [ ] AttachVolume.
- [ ] AttachInstance.

- - - - - -

### 21
What does Amazon DynamoDB provide?

- [ ] A predictable and scalable MySQL database.
- [ ] A fast and reliable PL/SQL database cluster.
- [ ] A standalone Cassandra database, managed by Amazon Web Services.
- [x] A fast, highly scalable managed NoSQL database service.

- - - - - -

### 22
Security groups act like a firewall at the instance level, whereas [...] are an additional layer of security that act at the subnet level.

- [ ] DB Security Groups.
- [ ] VPC Security Groups.
- [x] network ACLs.

- - - - - -

### 23
You have been asked to tighten up the password policies in your organization after a serious security breach, so you need to consider every possible security measure. Which of the following is not an account password policy for IAM Users that can be set?

- [ ] Force IAM users to contact an account administrator when the user has allowed his or her password to expire.
- [ ] A minimum password length.
- [x] Force IAM users to contact an account administrator when the user has entered his password incorrectly.
- [ ] Prevent IAM users from reusing previous passwords.

- - - - - -

### 24
Multi-AZ deployment [...] supported for Microsoft SQL Server DB Instances.

- [x] is not currently.
- [ ] is as of 2013.
- [ ] is planned to be in 2014.
- [ ] will never be.

- - - - - -

### 25
What does Amazon Elastic Beanstalk provide?

- [ ] A scalable storage appliance on top of Amazon Web Services.
- [x] An application container on top of Amazon Web Services.
- [ ] A service by this name doesn't exist.
- [ ] A scalable cluster of EC2 instances.

- - - - - -

### 26
You need to quickly set up an email-sending service because a client needs to start using it in the next hour. Amazon Simple Email Service (Amazon SES) seems to be the logical choice but there are several options available to set it up. Which of the following options to set up SES would best meet the needs of the client?

- [x] Amazon SES console.
- [ ] AWS CloudFormation.
- [ ] SMTP Interface.
- [ ] AWS Elastic Beanstalk.

- - - - - -

### 27
A user is observing the EC2 CPU utilization metric on CloudWatch. The user has observed some interesting patterns while filtering over the 1 week period for a particular hour. The user wants to zoom that data point to a more granular period. How can the user do that easily with CloudWatch?

- [x] The user can zoom a particular period by selecting that period with the mouse and then releasing the mouse.
- [ ] The user can zoom a particular period by specifying the aggregation data for that period.
- [ ] The user can zoom a particular period by double clicking on that period with the mouse.
- [ ] The user can zoom a particular period by specifying the period in the Time Range.

- - - - - -

### 28
A company is running a batch analysis every hour on their main transactional DB. running on an RDS MySQL instance to populate their central Data Warehouse running on Redshift During the execution of the batch their transactional applications are very slow When the batch completes they need to update the top management dashboard with the new data The dashboard is produced by another system running on-premises that is currently started when a manually-sent email notifies that an update is required The on-premises system cannot be modified because is managed by another team. How would you optimize this scenario to solve performance issues and automate the process as much as possible? How would you optimize this scenario to solve performance issues and automate the process as much as possible?

- [x] Replace RDS with Redshift for the batch analysis and SNS to notify the on-premises system to update the dashboard.
- [ ] Replace ROS with Redshift for the oaten analysis and SQS to send a message to the on-premises system to update the dashboard.
- [ ] Create an RDS Read Replica for the batch analysis and SNS to notify me on-premises system to update the dashboard.
- [ ] Create an RDS Read Replica for the batch analysis and SQS to send a message to the on-premises system to update the dashboard.

- - - - - -

### 29
You are configuring a new VPC for one of your clients for a cloud migration project, and only a public VPN will be in place. After you created your VPC, you created a new subnet, a new internet gateway, and attached your internet gateway to your VPC. When you launched your first instance into your VPC, you realized that you aren't able to connect to the instance, even if it is configured with an elastic IP. What should be done to access the instance?

- [x] A route should be created as 0.0.0.0/0 and your internet gateway as target.
- [ ] Attach another ENI to the instance and connect via new EN.
- [ ] A NAT instance should be created and all traffic should be forwarded to NAT instance.
- [ ] A NACL should be created that allows all outbound traffic.

- - - - - -

### 30
You have been asked to build a database warehouse using Amazon Redshift. You know a little about it, including that it is a SQL data warehouse solution, and uses industry standard ODBC and JDBCconnections and PostgreSQL drivers. However you are not sure about what sort of storage it uses for database tables. What sort of storage does Amazon Redshift use for database tables?

- [ ] InnoDB Tables.
- [ ] NDB data storage.
- [x] Columnar data storage.
- [ ] NDB CLUSTER Storage.

- - - - - -

### 31
A user has attached 1 EBS volume to a VPC instance. The user wants to achieve the best fault tolerance of data possible. Which of the below mentioned options can help achieve fault tolerance?

- [x] Attach one more volume with RAID 1 configuration.
- [ ] Attach one more volume with RAID 0 configuration.
- [ ] Connect multiple volumes and stripe them with RAI.
- [ ] Use the EBS volume as a root device.

- - - - - -

### 32
Which features can be used to restrict access to data in S3? (Choose 2 answers)

- [x] Set an S3 ACL on the bucket or the object.
- [ ] Create a CloudFront distribution for the bucket.
- [x] Set an S3 bucket policy.
- [ ] Enable IAM Identity Federation.
- [ ] Use S3 Virtual l Hosting.

- - - - - -

### 33
You are in the process of creating a Route 53 DNS failover to direct traffic to two EC2 zones. Obviously, if one fails, you would like Route 53 to direct traffic to the other region. Each region has an ELB with some instances being distributed. What is the best way for you to configure the Route 53 health check?

- [ ] Route 53 doesn't support ELB with an internal health check.You need to create your own Route 53 health check of the ELB.
- [ ] Route 53 natively supports ELB with an internal health check. Turn 'Evaluate target health' off and 'Associate with Health Check' on and R53 will use the ELB's internal health check.
- [ ] Route 53 doesn't support ELB with an internal health check. You need to associate your resource record set for the ELB with your own health check.
- [x] Route 53 natively supports ELB with an internal health check. Turn 'Evaluate target health' on and 'Associate with Health Check' off and R53 will use the ELB's internal health check.

- - - - - -

### 34
For each DB Instance class, what is the maximum size of associated storage capacity?

- [ ] 5GB.
- [x] 1TB.
- [ ] 2TB.
- [ ] 500GB.

- - - - - -

### 35
A user is planning a highly available application deployment with EC2. Which of the below mentioned options will not help to achieve HA?

- [ ] Elastic IP address.
- [x] PIOPS.
- [ ] AMI.
- [ ] Availability Zones.

- - - - - -

### 36
What does specifying the mapping /dev/sdc=none when launching an instance do?

- [ ] Prevents /dev/sdc from creating the instance.
- [ ] Prevents /dev/sdc from deleting the instance.
- [ ] Set the value of /dev/sdc to 'zero'.
- [x] Prevents /dev/sdc from attaching to the instance.

- - - - - -

### 37
Which of the following statements is true of tagging an Amazon EC2 resource?

- [ ] You don't need to specify the resource identifier while terminating a resource.
- [ ] You can terminate, stop, or delete a resource based solely on its tags.
- [x] You can't terminate, stop, or delete a resource based solely on its tags.
- [ ] You don't need to specify the resource identifier while stopping a resource.

- - - - - -

### 38
You are deploying an application to collect votes for a very popular television show. Millions of users will submit votes using mobile devices. The votes must be collected into a durable, scalable, and highly available data store for real-time public tabulation. Which service should you use?

- [ ] Amazon DynamoDB.
- [ ] Amazon Redshift.
- [x] Amazon Kinesis.
- [ ] Amazon Simple Queue Service.

- - - - - -

### 39
Are Reserved Instances available for Multi-AZ Deployments?

- [ ] Only for Cluster Compute instances.
- [x] Yes for all instance types.
- [ ] Only for M3 instance types.
- [ ] No.

- - - - - -

### 40
A [...] for a VPC is a collection of subnets (typically private) that you may want to designate for your backend RDS DB Instances.

- [ ] DB Subnet Set.
- [ ] RDS Subnet Group.
- [x] DB Subnet Group.
- [ ] DB Subnet Collection.

- - - - - -

### 41
An instance is launched into a VPC subnet with the network ACL configured to al low all inbound traffic and deny all outbound traffic. The instance's security group is configured to allow SSH from any IPaddress and deny all outbound traffic. What changes need to be made to allow SSH access to the instance?

- [ ] The out bound security group needs to be modified to allow out bound traffic.
- [x] The outbound network ACL needs to be modified to allow outbound traffic.
- [ ] Nothing, it can be accessed from any IP address using SS.
- [ ] Both the outbound security group and outbound network ACL need to be modified to allow outbound traffic.

- - - - - -

### 42
You can modify the backup retention period; valid values are 0 (for no backup retention) to a maximum of [...] days.

- [ ] 45.
- [x] 35.
- [ ] 15.
- [ ] 5.

- - - - - -

### 43
To serve Web traffic for a popular product your chief financial officer and IT director have purchased 10 ml large heavy utilization Reserved Instances (RIs) evenly spread across two Availability Zones: Route 53 is used to deliver the traffic to an Elastic Load Balancer (ELB). After several months, the product grows even more popular and you need additional capacity As a result, your company purchases two C3.2xlarge medium utilization RIs You register the two c3 2xlarge instances with your ELB and quickly find that the ml large instances are at 100% of capacity and the c3 2xlarge instances have significant capacity that's unused Which option is the most cost effective and uses EC2 capacity most effectively?

- [x] Use a separate ELB for each instance type and distribute load to ELBs with Route 53 weighted round robin.
- [ ] Configure Autoscaning group and Launch Configuration with ELB to add up to 10 more on-demand ml large instances when triggered by Cloudwatch shut off c3 2xlarge instances.
- [ ] Route traffic to EC2 ml large and c3 2xlarge instances directly using Route 53 latency based routing and health checks shut off ELB.
- [ ] Configure ELB with two c3 2xiarge Instances and use on-demand Autoscaling group for up to two additional c3.2xlarge instances Shut on mi .large instances.

- - - - - -

### 44
An existing application stores sensitive information on a non-boot Amazon EBS data volume attached to an Amazon Elastic Compute Cloud instance. Which of the following approaches would protect the sensitive data on an Amazon EBS volume?

- [ ] Upload your customer keys to AWS CloudHS.
- [ ] Associate the Amazon EBS volume with AWS CloudHS.
- [ ] Re-mount the Amazon EBS volume.
- [x] Create and mount a new, encrypted Amazon EBS volume. Move the data to the new volume. Delete the old Amazon EBS volume.
- [ ] Unmount the EBS volume. Toggle the encryption attribute to True. Re-mount the Amazon EBS volume.
- [ ] Snapshot the current Amazon EBS volume. Restore the snapshot to a new, encrypted Amazon EBS volume. Mount the Amazon EBS volume.

- - - - - -

### 45
A user has launched one EC2 instance in the US West region. The user wants to access the RDS instance launched in the US East region from that EC2 instance. How can the user configure the access for that EC2 instance?

- [x] Configure the IP range of the US West region instance as the ingress security rule of RDS.
- [ ] It is not possible to access RDS of the US East region from the US West region.
- [ ] Open the security group of the US West region in the RDS security group's ingress rule.
- [ ] Create an IAM role which has access to RDS and launch an instance in the US West region with it.

- - - - - -

### 46
You have been asked to build AWS infrastructure for disaster recovery for your local applications and within that you should use an AWS Storage Gateway as part of the solution. Which of the following best describes the function of an AWS Storage Gateway?

- [ ] Accelerates transferring large amounts of data between the AWS cloud and portable storage devices .
- [ ] A web service that speeds up distribution of your static and dynamic web content.
- [x] Connects an on-premises software appliance with cloud-based storage to provide seamless and secure integration between your on-premises IT environment and AWS's storage infrastructure.
- [ ] Is a storage service optimized for infrequently used data, or 'cold data'.

- - - - - -

### 47
While creating an Amazon RDS DB, your first task is to set up a DB [...] that controls which IP address or EC2 instance can access your DB Instance.

- [ ] security token pool.
- [ ] security token.
- [ ] security pool.
- [x] security group.

- - - - - -

### 48
You need to import several hundred megabytes of data from a local Oracle database to an Amazon RDS DB instance. What does AWS recommend you use to accomplish this?

- [ ] Oracle export/import utilities.
- [ ] Oracle SQL Developer.
- [x] Oracle Data Pump.
- [ ] DBMS_FILE_TRANSFER.

- - - - - -

### 49
In the context of AWS support, why must an EC2 instance be unreachable for 20 minutes rather than allowing customers to open tickets immediately?

- [x] Because most reachability issues are resolved by automated processes in less than 20 minutes.
- [ ] Because all EC2 instances are unreachable for 20 minutes every day when AWS does routine maintenance.
- [ ] Because all EC2 instances are unreachable for 20 minutes when first launched.
- [ ] Because of all the reasons listed here.

- - - - - -

### 50
HTTP Query-based requests are HTTP requests that use the HTTP verb GET or POST and a Query parameter named [...].

- [x] Action.
- [ ] Value.
- [ ] Reset.
- [ ] Retrieve.

- - - - - -

