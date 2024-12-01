### 1
A Provisioned IOPS volume must be at least [...] GB in size.

- [ ] 1.
- [ ] 50.
- [ ] 20.
- [ ] 10.

- - - - - -

### 2
In Amazon EC2, while sharing an Amazon EBS snapshot, can the snapshots with AWS Marketplace product codes be public?

- [ ] Yes, but only for US-based providers.
- [ ] Yes, they can be public.
- [ ] No, they cannot be made public.
- [ ] Yes, they are automatically made public by the system.

- - - - - -

### 3
A company has an AWS account that contains three VPCs (Dev, Test, and Prod) in the same region. Test is peered to both Prod and Dev. All VPCs have non-overlapping CIDR blocks. The company wants to push minor code releases from Dev to Prod to speed up time to market. Which of the following options helps the company accomplish this?

- [ ] Create a new peering connection Between Prod and Dev along with appropriate routes.
- [ ] Create a new entry to Prod in the Dev route table using the peering connection as the target.
- [ ] Attach a second gateway to Dev. Add a new entry in the Prod route table identifying the gateway as the target.
- [ ] The VPCs have non-overlapping Cl DR blocks in the same account. The route tables contain local routes for all VPCs.

- - - - - -

### 4
The [...] service is targeted at organizations with multiple users or systems that use AWS products such as Amazon EC2, Amazon SimpleDB, and the AWS Management Console.

- [ ] Amazon RDS.
- [ ] AWS Integrity Management.
- [ ] AWS Identity and Access Management.
- [ ] Amazon EMR.

- - - - - -

### 5
You have just been given a scope for a new client who has an enormous amount of data (petabytes) that he constantly needs analysed. Currently he is paying a huge amount of money for a data warehousing company to do this for him and is wondering if AWS can provide a cheaper solution. Do you think AWS has a solution for this?

- [ ] Yes. Amazon SimpleDB.
- [ ] No. Not presently.
- [ ] Yes. Amazon Redshift.
- [ ] Yes. Your choice of relational AMIs on Amazon EC2 and EBS.

- - - - - -

### 6
You have set up an Elastic Load Balancer (ELB) with the usual default settings, which route each request independently to the application instance with the smallest load. However, someone has asked you to bind a user's session to a specific application instance so as to ensure that all requests coming from the user during the session will be sent to the same application instance. AWS has a feature to do this. What is it called?

- [ ] Connection draining.
- [ ] Proxy protocol.
- [ ] Tagging.
- [ ] Sticky session.

- - - - - -

### 7
You have written a CloudFormation template that creates 1 Elastic Load Balancer fronting 2 EC2 Instances. Which section of the template should you edit so that the DNS of the load balancer is returned upon creation of the stack?

- [ ] Resources.
- [ ] Outputs.
- [ ] Parameters.
- [ ] Mappings.

- - - - - -

### 8
AWS CloudFormation is a service that helps you model and set up your Amazon Web Services resources so that you can spend less time managing those resources and more time focusing on your applications that run in AWS. You create a template that describes all the AWS resources that you want (like Amazon EC2 instances or Amazon RDS DB instances), and AWS CloudFormation takes care of provisioning and configuring those resources for you. What formatting is required for this template?

- [ ] JSON-formatted document.
- [ ] CSS-formatted document.
- [ ] XML-formatted document.
- [ ] HTML-formatted document.

- - - - - -

### 9
A user has created an application which will be hosted on EC2. The application makes calls to DynamoDB to fetch certain data. The application is using the DynamoDB SDK to connect with from theEC2 instance. Which of the below mentioned statements is true with respect to the best practice for security in this scenario?

- [ ] The user should create an IAM user with DynamoDB access and use its credentials within the application to connect with DynamoDB.
- [ ] The user should attach an IAM role with DynamoDB access to the EC2 instance.
- [ ] The user should create an IAM role, which has EC2 access so that it will allow deploying the application.
- [ ] The user should create an IAM user with DynamoDB and EC2 access. Attach the user with the application so that it does not use the root account credentials.

- - - - - -

### 10
After setting up an EC2 security group with a cluster of 20 EC2 instances, you find an error in the security group settings. You quickly make changes to the security group settings. When will the changes to the settings be effective?

- [ ] The settings will be effective immediately for all the instances in the security group.
- [ ] The settings will be effective only when all the instances are restarted.
- [ ] The settings will be effective for all the instances only after 30 minutes.
- [ ] The settings will be effective only for the new instances added to the security group.

- - - - - -

### 11
Can a user get a notification of each instance start / terminate configured with Auto Scaling?

- [ ] Yes, if configured with the Launch Config.
- [ ] Yes, always.
- [ ] Yes, if configured with the Auto Scaling group.
- [ ] No.

- - - - - -

### 12
Which Amazon storage do you think is the best for my database-style applications that frequently encounter many random reads and writes across the dataset?

- [ ] None of these.
- [ ] Amazon Instance Storage.
- [ ] Any of these.
- [ ] Amazon EBS.

- - - - - -

### 13
In the Amazon RDS Oracle DB engine, the Database Diagnostic Pack and the Database Tuning Pack are only available with [...].

- [ ] Oracle Standard Edition.
- [ ] Oracle Express Edition.
- [ ] Oracle Enterprise Edition.
- [ ] None of these.

- - - - - -

### 14
Will my standby RDS instance be in the same Availability Zone as my primary?

- [ ] Only for Oracle RDS types.
- [ ] Yes.
- [ ] Only if configured at launch.
- [ ] No.

- - - - - -

### 15
An administrator is using Amazon CloudFormation to deploy a three tier web application that consists of a web tier and application tier that will utilize Amazon DynamoDB for storage when creating theCloudFormation template which of the following would allow the application instance access to the DynamoDB tables without exposing API credentials?

- [ ] Create an Identity and Access Management Role that has the required permissions to read and write from the required DynamoDB table and associate the Role to the application instances by referencing an instance profile.
- [ ] Use the Parameter section in the Cloud Formation template to nave the user input Access and Secret Keys from an already created IAM user that has me permissions required to read and write from the required DynamoDB table.
- [ ] Create an Identity and Access Management Role that has the required permissions to read and write from the required DynamoDB table and reference the Role in the instance profile property of the application instance.
- [ ] Create an identity and Access Management user in the CloudFormation template that has permissions to read and write from the required DynamoDB table, use the GetAtt function to retrieve the Access and secret keys and pass them to the application instance through user-data.

- - - - - -

### 16
In an experiment, if the minimum size for an Auto Scaling group is 1 instance, which of the following statements holds true when you terminate the running instance?

- [ ] Auto Scaling must launch a new instance to replace it.
- [ ] Auto Scaling will raise an alarm and send a notification to the user for action.
- [ ] Auto Scaling must configure the schedule activity that terminates the instance after 5 days.
- [ ] Auto Scaling will terminate the experiment.

- - - - - -

### 17
True or False: Manually created DB Snapshots are deleted after the DB Instance is deleted.

- [ ] True.
- [ ] False.

- - - - - -

### 18
Amazon S3 doesn't automatically give a user who creates [...] permission to perform other actions on that bucket or object.

- [ ] a file.
- [ ] a bucket or object.
- [ ] a bucket or file.
- [ ] a object or file.

- - - - - -

### 19
A company wants to review the security requirements of Glacier. Which of the below mentioned statements is true with respect to the AWS Glacier data security?

- [ ] All data stored on Glacier is protected with AES-256 serverside encryption.
- [ ] All data stored on Glacier is protected with AES-128 serverside encryption.
- [ ] The user can set the serverside encryption flag to encrypt the data stored on Glacier.
- [ ] The data stored on Glacier is not encrypted by default.

- - - - - -

### 20
What does Amazon EBS stand for?

- [ ] Elastic Block Storage.
- [ ] Elastic Business Server.
- [ ] Elastic Blade Server.
- [ ] Elastic Block Store.

- - - - - -

### 21
You have a distributed application that periodically processes large volumes of data across multiple Amazon EC2 Instances. The application is designed to recover gracefully from Amazon EC2 instance failures. You are required to accomplish this task in the most cost-effective way. Which of the following will meet your requirements?

- [ ] Spot Instances.
- [ ] Reserved instances.
- [ ] Dedicated instances.
- [ ] On-Demand instances.

- - - - - -

### 22
What does Amazon SWF stand for?

- [ ] Simple Web Flow.
- [ ] Simple Work Flow.
- [ ] Simple Wireless Forms.
- [ ] Simple Web Form.

- - - - - -

### 23
Can you specify the security group that you created for a VPC when you launch an instance in EC2-Classic?

- [ ] No, you can specify the security group created for EC2-Classic when you launch a VPC instance.
- [ ] Yes.
- [ ] No.
- [ ] No, you can specify the security group created for EC2-Classic to a non-VPC based instance only.

- - - - - -

### 24
Which two methods increases the fault tolerance of the connection to VPC-1? (Choose 2 answers)

- [ ] Establish a hardware VPN over the internet between VPC-2 and the on-premises network.
- [ ] Establish a hardware VPN over the internet between VPC-1 and the on-premises network.
- [ ] Establish a new AWS Direct Connect connection and private virtual interface in the same region as VPC-2.
- [ ] Establish a new AWS Direct Connect connection and private virtual interface in a different AWS region than VPC-1.
- [ ] Establish a new AWS Direct Connect connection and private virtual interface in the same AWS region as VPC-1.

- - - - - -

### 25
How would you improve page load times for your users? (Choose 3 answers)

- [ ] Lower the scale up trigger of your Auto Scaling group to 30% so it scales more aggressively.
- [ ] Add an Amazon ElastiCache caching layer to your application for storing sessions and frequent DB queries.
- [ ] Configure Amazon CloudFront dynamic content support to enable caching of re-usable content from your site.
- [ ] Switch Amazon RDS database to the high memory extra large Instance type.
- [ ] Set up a second installation in another region, and use the Amazon Route 53 latency-based routing feature to select the right region.

- - - - - -

### 26
Typically, you want your application to check whether a request generated an error before you spend any time processing results. The easiest way to find out if an error occurred is to look for an [...] node in the response from the Amazon RDS API.

- [ ] incorrect.
- [ ] error.

- - - - - -

### 27
Through which of the following interfaces is AWS Identity and Access Management available? A. AWS Management Console. B. Command line interface (CLI). C. IAM Query API. D. Existing libraries.

- [ ] Only through Command line interface (CLI).
- [ ] A, B and C.
- [ ] A and C.
- [ ] All of the above.

- - - - - -

### 28
A [...] is a storage device that moves data in sequences of bytes or bits (blocks).

- [ ] block map.
- [ ] storage block.
- [ ] mapping device.
- [ ] block device.

- - - - - -

### 29
You have just finished setting up an advertisement server in which one of the obvious choices for a service was Amazon Elastic MapReduce( EMR) and are now troubleshooting some weird cluster states that you are seeing. Which of the below is not an Amazon EMR cluster state?

- [ ] STARTING.
- [ ] STOPPED.
- [ ] RUNNING.
- [ ] WAITING.

- - - - - -

### 30
A US-based company is expanding their web presence into Europe. The company wants to extend their AWS infrastructure from Northern Virginia (us-east-1) into the Dublin (eu-west-1) region. Which of the following options would enable an equivalent experience for users on both continents?

- [ ] Use a public-facing load balancer per region to load-balance web traffic, and enable HTTP health checks.
- [ ] Use a public-facing load balancer per region to load-balance web traffic, and enable sticky sessions.
- [ ] Use Amazon Route 53, and apply a geolocation routing policy to distribute traffic across both regions.
- [ ] Use Amazon Route 53, and apply a weighted routing policy to distribute traffic across both regions.

- - - - - -

### 31
You are building infrastructure for a data warehousing solution and an extra request has come through that there will be a lot of business reporting queries running all the time and you are not sure if your current DB instance will be able to handle it. What would be the best solution for this?

- [ ] DB Parameter Groups.
- [ ] Read Replicas.
- [ ] Multi-AZ DB Instance deployment.
- [ ] Database Snapshots.

- - - - - -

### 32
One of the criteria for a new deployment is that the customer wants to use AWS Storage Gateway. However you are not sure whether you should use gateway-cached volumes or gateway-stored volumes or even what the differences are. Which statement below best describes those differences?

- [ ] Gateway-cached lets you store your data in Amazon Simple Storage Service (Amazon S3) and retain a copy of frequently accessed data subsets locally. Gateway-stored enables you to configure your on-premises gateway to store all your data locally and then asynchronously back up point-in-time snapshots of this data to Amazon S3.
- [ ] Gateway-cached is free whilst gateway-stored is not.
- [ ] Gateway-cached is up to 10 times faster than gateway-stored.
- [ ] Gateway-stored lets you store your data in Amazon Simple Storage Service (Amazon S3) and retain a copy of frequently accessed data subsets locally. Gateway-cached enables you to configure your on-premises gateway to store all your data locally and then asynchronously back up point-in-time snapshots of this data to Amazon S3.

- - - - - -

### 33
In Amazon RDS, security groups are ideally used to:

- [ ] Define maintenance period for database engines.
- [ ] Launch Amazon RDS instances in a subnet.
- [ ] Create, describe, modify, and delete DB instances.
- [ ] Control what IP addresses or EC2 instances can connect to your databases on a DB instance.

- - - - - -

### 34
How long does an AWS free usage tier EC2 last for?

- [ ] Forever.
- [ ] 12 Months upon signup.
- [ ] 1 Month upon signup.
- [ ] 6 Months upon signup.

- - - - - -

### 35
After you recommend Amazon Redshift to a client as an alternative solution to paying data warehouses to analyze his data, your client asks you to explain why you are recommending Redshift. Which of the following would be a reasonable response to his request?

- [ ] It has high performance at scale as data and query complexity grows.
- [ ] It prevents reporting and analytic processing from interfering with the performance of OLTP workloads.
- [ ] You don't have the administrative burden of running your own data warehouse and dealing with setup, durability, monitoring, scaling, and patching.
- [ ] All answers listed are a reasonable response to his question.

- - - - - -

### 36
You can seamlessly join an EC2 instance to your directory domain. What connectivity do you need to be able to connect remotely to this instance?

- [ ] You must have IP connectivity to the instance from the network you are connecting from.
- [ ] You must have the correct encryption keys to connect to the instance remotely.
- [ ] You must have enough bandwidth to connect to the instance.
- [ ] You must use MFA authentication to be able to connect to the instance remotely.

- - - - - -

### 37
Does Amazon DynamoDB support both increment and decrement atomic operations?

- [ ] Only increment, since decrement are inherently impossible with DynamoDB's data model.
- [ ] No, neither increment nor decrement operations.
- [ ] Yes, both increment and decrement operations.
- [ ] Only decrement, since increment are inherently impossible with DynamoDB's data model.

- - - - - -

### 38
You nave multiple Amazon EC2 instances running in a cluster across multiple Availability Zones within the same region. What combination of the following should be used to ensure the highest network performance (packets per second), lowest latency, and lowest jitter? (Choose 3 answers)

- [ ] Amazon EC2 placement groups.
- [ ] Enhanced networking.
- [ ] Amazon PV AMI.
- [ ] Amazon HVM AMI.
- [ ] Amazon Linux.
- [ ] Amazon VPC.

- - - - - -

### 39
If an Amazon EBS volume is the root device of an instance, can I detach it without stopping the instance?

- [ ] Yes but only if Windows instance.
- [ ] Yes.
- [ ] No.
- [ ] Yes but only if a Linux instance.

- - - - - -

### 40
True or False: When you add a rule to a DB security group, you do not need to specify port number or protocol.

- [ ] Depends on the ROMS used.
- [ ] True.
- [ ] False.

- - - - - -

### 41
Before I delete an EBS volume, what can I do if I want to recreate the volume later?

- [ ] Create a copy of the EBS volume (not a snapshot).
- [ ] Store a snapshot of the volume.
- [ ] Download the content to an EC2 instance
- [ ] Back up the data in to a physical disk.

- - - - - -

### 42
An accountant asks you to design a small VPC network for him and, due to the nature of his business, just needs something where the workload on the network will be low, and dynamic data will be accessed infrequently. Being an accountant, low cost is also a major factor. Which EBS volume type would best suit his requirements?

- [ ] Magnetic.
- [ ] Any, as they all perform the same and cost the same.
- [ ] General Purpose (SSD).
- [ ] Magnetic or Provisioned IOPS (SSD).

- - - - - -

### 43
Uur company currently has a 2-tier web application running in an on-premises data center. You have experienced several infrastructure failures in the past two months resulting in significant financial losses. Your CIO is strongly agreeing to move the application to AWS. While working on achieving buy-in from the other company executives, he asks you to develop a disaster recovery plan to help improve Business continuity in the short term. He specifies a target Recovery Time Objective (RTO) of 4 hours and a Recovery Point Objective (RPO) of 1 hour or less. He also asks you to implement the solution within 2 weeks. Your database is 200GB in size and you have a 20Mbps Internet connection. How would you do this while minimizing costs?

- [ ] Create an EBS backed private AMI which includes a fresh install of your application. Develop a CloudFormation template which includes your AMI and the required EC2, AutoScaling, and ELBresources to support deploying the application across Multiple- Availability-Zones. Asynchronously replicate transactions from your on-premises database to a database instance in AWS across a secure VPN connection.
- [ ] Deploy your application on EC2 instances within an Auto Scaling group across multiple availability zones. Asynchronously replicate transactions from your on-premises database to a database instance in AWS across a secure VPN connection.
- [ ] Create an EBS backed private AMI which includes a fresh install of your application. Setup a script in your data center to backup the local database every 1 hour and to encrypt and copy the resulting file to an S3 bucket using multi-part upload.
- [ ] Install your application on a compute-optimized EC2 instance capable of supporting the application's average load. Synchronously replicate transactions from your on-premises database to a database instance in AWS across a secure Direct Connect connection.

- - - - - -

### 44
A customer implemented AWS Storage Gateway with a gateway-cached volume at their main office. An event takes the link between the main and branch office offline. Which methods will enable the branch office to access their data? (Choose 3 answers)

- [ ] Use a HTTPS GET to the Amazon S3 bucket where the files are located.
- [ ] Restore by implementing a lifecycle policy on the Amazon S3 bucket.
- [ ] Make an Amazon Glacier Restore API ca ll to load the files into another Amazon S3 bucket within four to six hours.
- [ ] Launch a new AWS Storage Gateway instance AMI in Amazon EC2, and restore from a gateway snapshot.
- [ ] Create an Amazon EBS volume from a gateway snapshot, and mount it to an Amazon EC2 instance.
- [ ] Launch an AWS Storage Gateway virtual iSCSI device at the branch office, and restore from a gateway snapshot.

- - - - - -

### 45
Your customer is willing to consolidate their log streams (access logs application logs security logs etc.) in one single system. Once consolidated, the customer wants to analyze these logs in real time based on heuristics. From time to time, the customer needs to validate heuristics, which requires going back to data samples extracted from the last 12 hours. What is the best approach to meet your customer's requirements?

- [ ] Send all the log events to Amazon SQS, setup an Auto Scaling group of EC2 servers to consume the logs and apply the heuristics.
- [ ] Send all the log events to Amazon Kinesis develop a client process to apply heuristics on the logs.
- [ ] Configure Amazon Cloud Trail to receive custom logs, use EMR to apply heuristics the logs.
- [ ] Setup an Auto Scaling group of EC2 syslogd servers, store the logs on S3 use EMR to apply heuristics on the logs.

- - - - - -

### 46
Can the string value of 'Key' be prefixed with laws?

- [ ] No.
- [ ] Only for EC2 not S3.
- [ ] Yes.
- [ ] Only for S3 not EC.

- - - - - -

### 47
You are configuring your company's application to use Auto Scaling and need to move user state information. Which of the following AWS services provides a shared data store with durability and lowlatency?

- [ ] AWS ElastiCache Memcached.
- [ ] Amazon Simple Storage Service.
- [ ] Amazon EC2 instance storage.
- [ ] Amazon DynamoDB.

- - - - - -

### 48
Your company previously configured a heavily used, dynamically routed VPN connection between your on-premises data center and AWS. You recently provisioned a DirectConnect connection and would like to start using the new connection. After configuring DirectConnect settings in the AWS Console, which of the following options win provide the most seamless transition for your users?

- [ ] Delete your existing VPN connection to avoid routing loops configure your DirectConnect router with the appropriate settings and verity network traffic is leveraging DirectConnect.
- [ ] Configure your DirectConnect router with a higher 8GP priority man your VPN router, verify network traffic is leveraging Directconnect and then delete your existing VPN connection.
- [ ] Update your VPC route tables to point to the DirectConnect connection configure your DirectConnect router with the appropriate settings verify network traffic is leveraging DirectConnect and then delete the VPN connection.
- [ ] Configure your DirectConnect router, update your VPC route tables to point to the DirectConnect connection, configure your VPN connection with a higher BGP pointy. And verify network traffic is leveraging the DirectConnect connection.

- - - - - -

### 49
After setting up several database instances in Amazon Relational Database Service (Amazon RDS) you decide that you need to track the performance and health of your databases. How can you do this?

- [ ] Subscribe to Amazon RDS events to be notified when changes occur with a DB instance, DB snapshot, DB parameter group, or DB security group.
- [ ] Use the free Amazon CloudWatch service to monitor the performance and health of a DB instance.
- [ ] All of the items listed will track the performance and health of a database.
- [ ] View, download, or watch database log files using the Amazon RDS console or Amazon RDS APIs. You can also query some database log files that are loaded into database tables.

- - - - - -

### 50
You deployed your company website using Elastic Beanstalk and you enabled log file rotation to S3. An Elastic MapReduce job is periodically analyzing the logs on S3 to build a usage dashboard that you share with your CIO. You recently improved overall performance of the website using CloudFront for dynamic content delivery and your website as the origin. After this architectural change, the usage dashboard shows that the traffic on your website dropped by an order of magnitude. How do you fix your usage dashboard?

- [ ] Enable CloudFront to deliver access logs to S3 and use them as input of the Elastic MapReduce job.
- [ ] Turn on Cloud Trail and use trail log tiles on S3 as input of the Elastic MapReduce job.
- [ ] Change your log collection process to use Cloud Watch ELB metrics as input of the Elastic Map Reduce job.
- [ ] Use Elastic Beanstalk 'Rebuild Environment' option to update log delivery to the Elastic Map Reduce job.
- [ ] Use Elastic Beanstalk 'Restart App server(s)' option to update log delivery to the Elastic Map Reduce job.

- - - - - -

