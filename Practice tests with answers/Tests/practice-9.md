### 1
You need to create a JSON-formatted text file for AWS CloudFormation. This is your first template and the only thing you know is that the templates include several major sections but there is only one that is required for it to work. What is the only section required?

- [ ] Mappings.
- [ ] Outputs.
- [x] Resources.
- [ ] Conditions.

- - - - - -

### 2
A user wants to use an EBS-backed Amazon EC2 instance for a temporary job. Based on the input data, the job is most likely to finish within a week. Which of the following steps should be followed to terminate the instance automatically once the job is finished?

- [ ] Configure the EC2 instance with a stop instance to terminate it.
- [x] Configure the EC2 instance with ELB to terminate the instance when it remains idle.
- [ ] Configure the Cloud Watch alarm on the instance that should perform the termination action once the instance is idle.
- [ ] Configure the Auto Scaling schedule activity that terminates the instance after 7 days.

- - - - - -

### 3
You are building an automated transcription service in which Amazon EC2 worker instances process an uploaded audio file and generate a text file. You must store both of these files in the same durable storage until the text file is retrieved. You do not know what the storage capacity requirements are. Which storage option is both cost-efficient and scalable?

- [ ] Multiple Amazon EBS volume with snapshots.
- [ ] A single Amazon Glacier vault.
- [x] A single Amazon S3 bucket.
- [ ] Multiple instance stores.

- - - - - -

### 4
Your company has recently extended its datacenter into a VPC on AVVS to add burst computing capacity as needed Members of your Network Operations Center need to be able to go to the AWSManagement Console and administer Amazon EC2 instances as necessary You don't want to create new IAM users for each NOC member and make those users sign in again to the AWS Management Console Which option below will meet the needs for your NOC members?

- [ ] Use OAuth 2 0 to retrieve temporary AWS security credentials to enable your NOC members to sign in to the AVVS Management Console.
- [ ] Use web Identity Federation to retrieve AWS temporary security credentials to enable your NOC members to sign in to the AWS Management Console.
- [x] Use your on-premises SAML 2.0-compliant identity provider (IOP) to grant the NOC members federated access to the AWS Management Console via the AWS sing le sign-on (550) endpoint.
- [ ] Use your on-premises SAML2.0-compliam identity provider (IOP) to retrieve temporary security credentials to enable NOC members to sign in to the AWS Management Console.

- - - - - -

### 5
You have just set up your first Elastic Load Balancer (ELB) but it does not seem to be configured properly. You discover that before you start using ELB, you have to configure the listeners for your load balancer. Which protocols does ELB use to support the load balancing of applications?

- [x] HTTP and HTTPS.
- [ ] HTTP, HTTPS, TCP, SSL and SSH.
- [ ] HTTP, HTTPS, TCP, and SSL.
- [ ] HTTP, HTTPS, TCP, SSL and SFTP.

- - - - - -

### 6
A t2.medium EC2 instance type must be launched with what type of Amazon Machine Image (AMI)?

- [ ] An Instance store Hardware Virtual Machine AMI.
- [ ] An Instance store Paravirtual AMI.
- [ ] An Amazon EBS-backed Hardware Virtual Machine AMI.
- [x] An Amazon EBS-backed Paravirtual AMI.

- - - - - -

### 7
A user has created a subnet in VPC and launched an EC2 instance within it. The user has not selected the option to assign the IP address while launching the instance. The user has 3 elastic IPs and is trying to assign one of the Elastic IPs to the VPC instance from the console. The console does not show any instance in the IP assignment screen. What is a possible reason that the instance is unavailable in the assigned IP console?

- [ ] The IP address may be attached to one of the instances.
- [x] The IP address belongs to a different zone than the subnet zone.
- [ ] The user has not created an internet gateway.
- [ ] The IP addresses belong to EC2 Classic; so they cannot be assigned to VPC.

- - - - - -

### 8
Will I be alerted when automatic fail over occurs?

- [x] Only if SNS configured.
- [ ] Yes.
- [ ] No.
- [ ] Only if Cloud watch configured.

- - - - - -

### 9
Amazon EC2 provides a [...]. It is an HTTP or HTTPS request that uses the HTTP verbs GET or POST.

- [ ] web database.
- [ ] .NET framework.
- [x] Query API.
- [ ] C library.

- - - - - -

### 10
Which of the following requires a custom Cloud Watch metric to monitor?

- [ ] Memory Utilization of an EC2 instance.
- [ ] CPU Utilization of an EC2 instance.
- [ ] Disk usage activity of an EC2 instance.
- [x] Data transfer of an EC2 instance.

- - - - - -

### 11
An International company has deployed a multi-tier web application that relies on DynamoDB in a single region For regulatory reasons they need disaster recovery capability in a separate region with a Recovery Time Objective of 2 hours and a Recovery Point Objective of 24 hours They should synchronize their data on a regular basis and be able to provision me web application rapidly using CloudFormation. The objective is to minimize changes to the existing web application, control the throughput of DynamoDB used for the synchronization of data and synchronize only the modified elements. Which design would you choose to meet these requirements?

- [x] Use AWS data Pipeline to schedule a DynamoDB cross region copy once a day. create a Last updated' attribute in your DynamoDB table that would represent the timestamp of the last update and use it as a filter.
- [ ] Use EMR and write a custom script to retrieve data from DynamoDB in the current region using a SCAN operation and push it to Dynamo DB in the second region.
- [ ] Use AWS data Pipeline to schedule an export of the DynamoDB table to S3 in the current region once a day then schedule another task immediately after it that will import data from S3 to DynamoDB in the other region.
- [ ] Send also each Ante into an SQS queue in me second region; use an auto-scaling group behind the SQS queue to replay the write in the second region.

- - - - - -

### 12
An Elastic IP address (EIP) is a static IP address designed for dynamic cloud computing. With an EIP, you can mask the failure of an instance or software by rapidly remapping the address to another instance in your account. Your EIP is associated with your AWS account, not a particular EC2 instance, and it remains associated with your account until you choose to explicitly release it. By default how many EIPs is each AWS account limited to on a per region basis?

- [ ] 1.
- [ ] 5.
- [ ] Unlimited.
- [x] 10.

- - - - - -

### 13
Which Amazon Storage behaves like raw, unformatted, external block devices that you can attach to your instances?

- [ ] None of these.
- [ ] Amazon Instance Storage
- [x] Amazon EBS
- [ ] All of these.

- - - - - -

### 14
You currently operate a web application in the AWS US-East region The application runs on an autoscaled layer of EC2 instances and an RDS Multi-AZ database Your IT security compliance officer has tasked you to develop a reliable and durable logging solution to track changes made to your EC2.1AM And RDS resources. The solution must ensure the integrity and confidentiality of your log data. Which of these solutions would you recommend?

- [x] Create a new CloudTrail trail with one new S3 bucket to store the logs and with the global services option selected Use IAM roles S3 bucket policies and Multi Factor Authentication (MFA) Delete on the S3 bucket that stores your logs.
- [ ] Create a new CloudTrail with one new S3 bucket to store the logs Configure SNS to send log file delivery notifications to your management system Use IAM roles and S3 bucket policies on the S3 bucket mat stores your logs.
- [ ] Create a new CloudTrail trail with an existing S3 bucket to store the logs and with the global services option selected Use S3 ACLs and Multi Factor Authentication (MFA) Delete on the S3 bucket that stores your logs.
- [ ] Create three new CloudTrail trails with three new S3 buckets to store the logs one for the AWS Management console, one for AWS SDKs and one for command line tools Use IAM roles and S3 bucket policies on the S3 buckets that store your logs.

- - - - - -

### 15
Does DynamoDB support in-place atomic updates?

- [x] Yes.
- [ ] No.
- [ ] It does support in-place non-atomic updates.
- [ ] It is not defined.

- - - - - -

### 16
Which of the following is true of Amazon EC2 security group?

- [ ] You can modify the outbound rules for EC2-Classic.
- [ ] You can modify the rules for a security group only if the security group controls the traffic for just one instance.
- [ ] You can modify the rules for a security group only when a new instance is created.
- [x] You can modify the rules for a security group at any time.

- - - - - -

### 17
You need to set up security for your VPC and you know that Amazon VPC provides two features that you can use to increase security for your VPC: security groups and network access control lists (ACLs). You have already looked into security groups and you are now trying to understand ACLs. Which statement below is incorrect in relation to ACLs?

- [ ] Supports allow rules and deny rules.
- [ ] Is stateful: Return traffic is automatically allowed, regardless of any rules.
- [ ] Processes rules in number order when deciding whether to allow traffic.
- [x] Operates at the subnet level (second layer of defense).

- - - - - -

### 18
A user is trying to launch a similar EC2 instance from an existing instance with the option 'Launch More like this'. The AMI of the selected instance is deleted. What will happen in this case?

- [ ] AWS does not need an AMI for the 'Launch more like this' option.
- [ ] AWS will launch the instance but will not create a new AMI.
- [x] AWS will create a new AMI and launch the instance.
- [ ] AWS will throw an error saying that the AMI is deregistered.

- - - - - -

### 19
True or False: When you use the AWS Management Console to delete an IAM user, IAM also deletes any signing certificates and any access keys belonging to the user.

- [ ] False.
- [ ] This is configurable.
- [x] True.

- - - - - -

### 20
You are working with a customer who is using Chef configuration management in their data center. Which service is designed to let the customer leverage existing Chef recipes in AWS?

- [ ] Amazon Simple Workflow Service.
- [ ] AWS Elastic Beanstalk.
- [x] AWS CloudFormation.
- [ ] AWS OpsWorks.

- - - - - -

### 21
Does Amazon RDS for SQL Server currently support importing data into the msdb database?

- [x] Yes.
- [ ] No.

- - - - - -

### 22
How can an EBS volume that is currently attached to an EC2 instance be migrated from one Availability Zone to another?

- [ ] Detach the volume and attach it to another EC2 instance in the other AZ.
- [ ] Simply create a new volume in the other AZ and specify the original volume as the source.
- [ ] Create a snapshot of the volume, and create a new volume from the snapshot in the other AZ.
- [x] Detach the volume, then use the ec2-migrate-voiume command to move it to another AZ.

- - - - - -

### 23
Having set up a website to automatically be redirected to a backup website if it fails, you realize that there are different types of failovers that are possible. You need all your resources to be available the majority of the time. Using Amazon Route 53 which configuration would best suit this requirement?

- [ ] Active-active failover.
- [ ] None. Route 53 can't failover.
- [ ] Active-passive failover.
- [x] Active-active-passive and other mixed configurations.

- - - - - -

### 24
A client application requires operating system privileges on a relational database server. What is an appropriate configuration for a highly available database architecture?

- [ ] A standalone Amazon EC2 instance.
- [x] Amazon RDS in a Multi-AZ configuration.
- [ ] Amazon EC2 instances in a replication configuration utilizing a single Availability Zone.
- [ ] Amazon EC2 instances in a replication configuration utilizing two different Availability Zones.

- - - - - -

### 25
Is decreasing the storage size of a DB Instance permitted?

- [x] Depends on the ROMS used.
- [ ] Yes.
- [ ] No.

- - - - - -

### 26
Can you encrypt EBS volumes?

- [x] Yes, you can enable encryption when you create a new EBS volume using the AWS Management Console, API, or CLI.
- [ ] No, you should use a third-party software to perform raw block-level encryption of an EBS volume.
- [ ] Yes, but you must use a third-party API for encrypting data before it's loaded on EBS.
- [ ] Yes, you can encrypt with the special 'ebs_encrypt' command through Amazon APIs.

- - - - - -

### 27
You must assign each server to at least [...] security group.

- [ ] 3.
- [ ] 2.
- [ ] 4.
- [x] 1.

- - - - - -

### 28
Is the encryption of connections between my application and my DB Instance using SSL for the MySQL server engines available?

- [x] Yes.
- [ ] Only in VPC.
- [ ] Only in certain regions.
- [ ] No.

- - - - - -

### 29
Your manager has come to you saying that he is very confused about the bills he is receiving from AWS as he is getting different bills for every user and needs you to look into making it more understandable. Which of the following would be the best solution to meet his request?

- [ ] AWS Billing Aggregation.
- [x] Consolidated Billing.
- [ ] Deferred Billing.
- [ ] Aggregated Billing.

- - - - - -

### 30
Regarding Amazon Route 53, if your application is running on Amazon EC2 instances in two or more Amazon EC2 regions and if you have more than one Amazon EC2 instance in one or more regions, you can use [...] to route traffic to the correct region and then use [...] route traffic to instances within the region, based on probabilities that you specify.

- [ ] weighted-based routing; alias resource record sets.
- [x] latency-based routing; weighted resource record sets.
- [ ] weighted-based routing; weighted resource record sets.
- [ ] latency-based routing; alias resource record sets.

- - - - - -

### 31
If I scale the storage capacity provisioned to my DB Instance by mid of a billing month, how will I be charged?

- [ ] You will be charged for the highest storage capacity you have used.
- [x] On a proration basis.

- - - - - -

### 32
When using the following AWS services, which should be implemented in multiple Availability Zones for high availability solutions? (Choose 2 answers)

- [x] Amazon Dynamo DB.
- [x] Amazon Elastic Compute Cloud (EC2).
- [ ] Amazon Elastic Load Balancing.
- [ ] Amazon Simple Notification Service (SNS).
- [ ] Amazon Simple Storage Service (S3).

- - - - - -

### 33
A customer is hosting their company website on a cluster of web servers that are behind a public facing load balancer. The customer also uses Amazon Route 53 to manage their public DNS. How should the customer configure the DNS zone apex record to point to the load balancer?

- [x] Create an A record pointing to the IP address of the load balancer.
- [ ] Create a CNAME record pointing to the load balancer DNS name.
- [ ] Create a CNAME record aliased to the load balancer DNS name.
- [ ] Create an A record aliased to the load balancer DNS name.

- - - - - -

### 34
True or False: REST or Query requests are HTTP or HTTPS requests that use an HTTP verb (such as GET or POST) and a parameter named Action or Operation that specifies the API you are calling.

- [x] True.
- [ ] False.

- - - - - -

### 35
Which of the following features ensures even distribution of traffic to Amazon EC2 instances in multiple Availability Zones registered with a load balancer?

- [ ] Elastic Load Balancing request routing.
- [ ] An Amazon Route 53 weighted routing policy.
- [x] Elastic Load Balancing cross-zone load balancing.
- [ ] An Amazon Route 53 latency routing policy.

- - - - - -

### 36
Groups can't [...].

- [ ] be nested more than 3 levels.
- [ ] be nested at all.
- [ ] be nested more than 4 levels.
- [x] be nested more than 2 levels.

- - - - - -

### 37
You have been using T2 instances as your CPU requirements have not been that intensive. However you now start to think about larger instance types and start looking at M1 and M3 instances. You are a little confused as to the differences between them as they both seem to have the same ratio of CPU and memory. Which statement below is incorrect as to why you would use one over the other?

- [ ] M3 instances are less expensive than M1 instances.
- [ ] M3 instances are configured with more swap memory than M1 instances.
- [x] M3 instances provide better, more consistent performance that M1 instances for most use-cases.
- [ ] M3 instances also offer SSD-based instance storage that delivers higher I/O performance.

- - - - - -

### 38
Do the system resources on the Micro instance meet the recommended configuration for Oracle?

- [ ] Yes, completely.
- [x] Yes, but only for certain situations.

- - - - - -

### 39
Which of the following are true regarding AWS CloudTrail? (Choose 3 answers)

- [x] CloudTrail is enabled globally.
- [ ] CloudTrail is enabled by default.
- [ ] CloudTrail is enabled on a per-region basis.
- [ ] CloudTrail is enabled on a per-service basis.
- [x] Logs can be delivered to a single Amazon S3 bucket for aggregation.
- [x] CloudTrail is enabled for all available services within a region.
- [ ] Logs can only be processed and delivered to the region in which they are generated.

- - - - - -

### 40
If you're unable to connect via SSH to your EC2 instance, which of the following should you check and possibly correct to restore connectivity?

- [ ] Adjust Security Group to permit egress traffic over TCP port 443 from your IP.
- [ ] Configure the JAM role to permit changes to security group settings.
- [ ] Modify the instance security group to allow ingress of ICMP packets from your IP.
- [x] Adjust the instance's Security Group to permit ingress traffic over port 22 from your IP.
- [ ] Apply the most recently released Operating System security patches.

- - - - - -

### 41
A major finance organisation has engaged your company to set up a large data mining application. Using AWS you decide the best service for this is Amazon Elastic MapReduce (EMR) which you know uses Hadoop. Which of the following statements best describes Hadoop?

- [ ] Hadoop is 3rd Party software which can be installed using AMI.
- [ ] Hadoop is an open source python web framework.
- [x] Hadoop is an open source Java software framework.
- [ ] Hadoop is an open source javascript framework.

- - - - - -
### 42
A customer has established an AWS Direct Connect connection to AWS. The link is up and routes are being advertised from the customer's end, however the customer is unable to connect from EC2 instances inside its VPC to servers residing in its datacenter. Which of the following options provide a viable solution to remedy this situation? (Choose 2 answers)

- [ ] Add a route to the route table with an IPsec VPN connection as the target.
- [ ] Enable route propagation to the virtual pinnate gateway (VGW).
- [x] Enable route propagation to the customer gateway (CGW).
- [ ] Modify the route table of all Instances using the 'route' command.
- [x] Modify the Instances VPC subnet route table by adding a route back to the customer's on-premises environment.

- - - - - -

### 43
While creating a network in the VPC, which of the following is true of a NAT device?

- [ ] You have to administer the NAT Gateway Service provided by AW
- [x] You can choose to use any of the three kinds of NAT devices offered by AWS for special purposes.
- [ ] You can use a NAT device to enable instances in a private subnet to connect to the Internet.
- [ ] You are recommended to use AWS NAT instances over NAT gateways, as the instances provide better availability and bandwidth.

- - - - - -

### 44
Which of the following statements is NOT true about using Elastic IP Address (EIP) in EC2-Classic and EC2-VPC platforms?

- [x] In the EC2-VPC platform, the Elastic IP Address (EIP) does not remain associated with the instance when you stop it.
- [ ] In the EC2-Classic platform, stopping the instance disassociates the Elastic IP Address (EIP) from it.
- [ ] In the EC2-VPC platform, if you have attached a second network interface to an instance, when you disassociate the Elastic IP Address (EIP) from that instance, a new public IP address is not assigned to the instance automatically; you'll have to associate an EIP with it manually.
- [ ] In the EC2-Classic platform, if you disassociate an Elastic IP Address (EIP) from the instance, the instance is automatically assigned a new public IP address within a few minutes.

- - - - - -

### 45
A user has hosted an application on EC2 instances. The EC2 instances are configured with ELB and Auto Scaling. The application server session time out is 2 hours. The user wants to configure connection draining to ensure that all in-flight requests are supported by ELB even though the instance is being deregistered. What time out period should the user specify for connection draining?

- [ ] 1 hour.
- [ ] 30 minutes.
- [ ] 5 minutes.
- [X] 2 hours.

- - - - - -

### 46
What does the following command do with respect to the Amazon EC2 security groups? ec2-create-group CreateSecurityGroup

- [ ] Groups the user created security groups in to a new group for easy access.
- [X] Creates a new security group for use with your account.
- [ ] Creates a new group inside the security group.
- [ ] Creates a new rule inside the security group.

- - - - - -

### 47
You are in the process of moving your friend's WordPress site onto AWS to try and save him some money, and you have told him that he should probably also move his domain name. He asks why he can't leave his domain name where it is and just have his infrastructure on AWS. What would be an incorrect response to his question?

- [ ] Route 53 offers low query latency for your end users.
- [X] Route 53 is designed to automatically answer queries from the optimal location depending on network conditions.
- [ ] The globally distributed nature of AWS's DNS servers helps ensure a consistent ability to route your end users to your application.
- [ ] Route 53 supports Domain Name System Security Extensions (DNSSEC).

- - - - - -

### 48
Which of the following are characteristics of a reserved instance? (Choose 3 answers)

- [ ] It can be migrated across Availability Zones.
- [x] It is specific to an Amazon Machine Image (AMI).
- [ ] It can be applied to instances launched by Auto Scaling.
- [x] It is specific to an instance Type.
- [X] It can be used to lower Total Cost of Ownership (TCO) of a system.

- - - - - -

### 49
A user has defined an AutoScaling termination policy to first delete the instance with the nearest billing hour. AutoScaling has launched 3 instances in the US-East-1A region and 2 instances in the US-East-1B region. One of the instances in the US-East-1B region is running nearest to the billing hour. Which instance will AutoScaling terminate first while executing the termination action?

- [ ] Random Instance from US-East-1A.
- [x] Instance with the nearest billing hour in US-East-1B.
- [ ] Instance with the nearest billing hour in US-East-1A.
- [ ] Random instance from US-East-1B.

- - - - - -

### 50
You have an environment that consists of a public subnet using Amazon VPC and 3 instances that are running in this subnet. These three instances can successfully communicate with other hosts on the Internet. You launch a fourth instance in the same subnet, using the same AMI and security group configuration you used for the others, but find that this instance cannot be accessed from the internet. What should you do to enable Internet access?

- [ ] Deploy a NAT instance into the public subnet.
- [x] Assign an Elastic IP address to the fourth instance.
- [ ] Configure a publically routable IP Address in the host OS of the fourth instance.
- [ ] Modify the routing table for the public subnet.

- - - - - -

