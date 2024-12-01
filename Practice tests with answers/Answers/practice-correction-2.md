### 1
A friend tells you he is being charged $100 a month to host his WordPress website, and you tell him you can move it to AWS for him and he will only pay a fraction of that, which makes him very happy. He then tells you he is being charged $50 a month for the domain, which is registered with the same people that set it up, and he asks if it's possible to move that to AWS as well. You tell him you aren't sure, but will look into it. Which of the following statements is true in regards to transferring domain names to AWS?

- [ ] You can't transfer existing domains to AWS.
- [x] You can transfer existing domains into Amazon Route 53's management.
- [ ] You can transfer existing domains via AWS Direct Connect.
- [ ] You can transfer existing domains via AWS Import/Export.

- - - - - -

### 2
While creating the snapshots using the command line tools, which command should I be using?

- [ ] ec2-deploy-snapshot.
- [ ] ec2-fresh-snapshot.
- [x] ec2-create-snapshot.
- [ ] ec2-new-snapshot.

- - - - - -

### 3
All Amazon EC2 instances are assigned two IP addresses at launch, out of which one can only be reached from within the Amazon EC2 network?

- [ ] Multiple IP address.
- [ ] Public IP address.
- [x] Private IP address.
- [ ] Elastic IP Address.

- - - - - -

### 4
When an EC2 instance that is backed by an S3-based AMI is terminated, what happens to the data on the root volume?

- [ ] Data is automatically saved as an EBS snapshot.
- [ ] Data is automatically saved as an EBS volume.
- [ ] Data is unavailable until the instance is restarted.
- [x] Data is automatically deleted.

- - - - - -

### 5
You've created your first load balancer and have registered your EC2 instances with the load balancer. Elastic Load Balancing routinely performs health checks on all the registered EC2 instances and automatically distributes all incoming requests to the DNS name of your load balancer across your registered, healthy EC2 instances. By default, the load balancer uses the [...] protocol for checking the health of your instances.

- [ ] HTTPS.
- [x] HTTP.
- [ ] ICMP.
- [ ] IPv6.

- - - - - -

### 6
Amazon Elastic Load Balancing is used to manage traffic on a fleet of Amazon EC2 instances, distributing traffic to instances across all Availability Zones within a region. Elastic Load Balancing has all the advantages of an on-premises load balancer, plus several security benefits. Which of the following is not an advantage of ELB over an on-premise load balancer?

- [x] ELB uses a four-tier, key-based architecture for encryption.
- [ ] ELB offers clients a single point of contact, and can also serve as the first line of defense against attacks on your network.
- [ ] ELB takes over the encryption and decryption work from the Amazon EC2 instances and manages it centrally on the load balancer.
- [ ] ELB supports end-to-end traffic encryption using TLS (previously SSL) on those networks that use secure HTTP (HTTPS) connections.

- - - - - -

### 7
A web company is looking to implement an external payment service into their highly available application deployed in a VPC Their application EC2 instances are behind a public lacing ELB Auto scaling is used to add additional instances as traffic increases under normal load the application runs 2 instances in the Auto Scaling group but at peak it can scale 3x in size. The application instances need to communicate with the payment service over the Internet which requires whitelisting of all public IP addresses used to communicate with it. A maximum of 4 whitelisting IP addresses are allowed at a time and can be added through an API. How should they architect their solution?

- [x] Route payment requests through two NAT instances setup for High Availability and whitelist the Elastic IP addresses attached to the MAT instances.
- [ ] Whitelist the VPC Internet Gateway Public IP and route payment requests through the Internet Gateway.
- [ ] Whitelist the ELB IP addresses and route payment requests from the Application servers through the EL.
- [ ] Automatically assign public IP addresses to the application instances in the Auto Scaling group and run a script on boot that adds each instances public IP address to the payment validation whitelist AP.

- - - - - -

### 8
You are using Amazon SES as an email solution but are unsure of what its limitations are. Which statement below is correct in regards to that?

- [ ] New Amazon SES users who have received production access can send up to 1,000 emails per 24-hour period, at a maximum rate of 10 emails per second.
- [ ] Every Amazon SES sender has a the same set of sending limits.
- [ ] Sending limits are based on messages rather than on recipients.
- [x] Every Amazon SES sender has a unique set of sending limits.

- - - - - -

### 9
Your company is getting ready to do a major public announcement of a social media site on AWS. The website is running on EC2 instances deployed across multiple Availability Zones with a Multi-AZ RDS MySQL Extra Large DB Instance. The site performs a high number of small reads and writes per second and relies on an eventual consistency model. After comprehensive tests you discover that there is read contention on RDS MySQL. Which are the best approaches to meet these requirements? (Choose 2 answers)

- [x] Deploy ElasticCache in-memory cache running in each Availability Zone.
- [ ] Implement sharding to distribute load to multiple RDS MySQL instances.
- [ ] Increase the RDS MySQL Instance size and Implement provisioned IOPS.
- [x] Add an RDS MySQL read replica in each Availability Zone.

- - - - - -

### 10
What does a 'Domain' refer to in Amazon SWF?

- [ ] A security group in which only tasks inside can communicate with each other.
- [ ] A special type of worker.
- [x] A collection of related Workflows.
- [ ] The DNS record for the Amazon SWF service.

- - - - - -

### 11
The SQL Server [...] feature is an efficient means of copying data from a source database to your DB Instance. It writes the data that you specify to a data file, such as an ASCII file.

- [x] bulk copy.
- [ ] group copy.
- [ ] dual copy.
- [ ] mass copy.

- - - - - -

### 12
Any person or application that interacts with AWS requires security credentials. AWS uses these credentials to identify who is making the call and whether to allow the requested access. You have just set up a VPC network for a client and you are now thinking about the best way to secure this network. You set up a security group called vpcsecuritygroup. Which following statement is true in respect to the initial settings that will be applied to this security group if you choose to use the default settings for this group?

- [ ] Allow all inbound traffic and allow no outbound traffic.
- [x] Allow no inbound traffic and allow all outbound traffic.
- [ ] Allow inbound traffic on port 80 only and allow all outbound traffic.
- [ ] Allow all inbound traffic and allow all outbound traffic.

- - - - - -

### 13
Which one of the below is not an AWS Storage Service?

- [ ] Amazon S3.
- [ ] Amazon Glacier.
- [x] Amazon CloudFront.
- [ ] Amazon EBS.

- - - - - -

### 14
You are trying to launch an EC2 instance, however the instance seems to go into a terminated status immediately. What would probably not be a reason that this is happening?

- [ ] The AMI is missing a required part.
- [ ] The snapshot is corrupt.
- [x] You need to create storage in EBS first.
- [ ] You've reached your volume limit.

- - - - - -

### 15
A company is building software on AWS that requires access to various AWS services. Which configuration should be used to ensure mat AWS credentials (i.e., Access Key ID/Secret Access Key combination) are not compromised?

- [ ] Enable Multi-Factor Authentication for your AWS root account.
- [x] Assign an IAM role to the Amazon EC2 instance.
- [ ] Store the AWS Access Key ID/Secret Access Key combination in software comments.
- [ ] Assign an IAM user to the Amazon EC2 Instance.

- - - - - -

### 16
Can we attach an EBS volume to more than one EC2 instance at the same time?

- [ ] Yes.
- [x] No.
- [ ] Only EC2-optimized EBS volumes.
- [ ] Only in read mode.

- - - - - -

### 17
You need to measure the performance of your EBS volumes as they seem to be under performing. You have come up with a measurement of 1,024 KB I/O but your colleague tells you that EBS volume performance is measured in IOPS. How many IOPS is equal to 1,024 KB I/O?

- [ ] 16.
- [ ] 256.
- [ ] 8.
- [x] 4.

- - - - - -

### 18
Your company produces customer commissioned one-of-a-kind skiing helmets combining nigh fashion with custom technical enhancements Customers can show off their Individuality on the ski slopes and have access to head-up-displays. GPS rear-view cams and any other technical innovation they wish to embed in the helmet. The current manufacturing process is data rich and complex including assessments to ensure that the custom electronics and materials used to assemble the helmets are to the highest standards Assessments are a mixture of human and automated assessments you need to add a new set of assessment to model the failure modes of the custom electronics using GPUs with CUDA, across a cluster of servers with low latency networking. What architecture would allow you to automate the existing process using a hybrid approach and ensure that the architecture can support the evolution of processes over time?

- [ ] Use AWS Data Pipeline to manage movement of data & meta-data and assessments Use an autoscaling group of G2 instances in a placement group.
- [x] Use Amazon Simple Workflow (SWF) to manages assessments, movement of data & meta-data Use an auto-scaling group of G2 instances in a placement group.
- [ ] Use Amazon Simple Workflow (SWF) to manages assessments movement of data & meta-data Use an auto-scaling group of C3 instances with SR-IOV (Single Root 1/0 Virtualization).
- [ ] Use AWS data Pipeline to manage movement of data & meta-data and assessments use autoscaling group of C3 with SR-IOV (Single Root 1/0 virtualization).

- - - - - -

### 19
You are designing Internet connectivity for your VPC. The Web servers must be available on the Internet. The application must have a highly available architecture. Which alternatives should you consider? (Choose 2 answers)

- [ ] Configure a NAT instance in your VPC Create a default route via the NAT instance and associate it with all subnets Configure a DNS A record that points to the NAT instance public IP address.
- [ ] Configure a CloudFront distribution and configure the origin to point to the private IP addresses of your Web servers Configure a Route 53 CNAME record to your CloudFront distribution.
- [x] Place all your web servers behind EL8 Configure a Route 53 CNAME to point to the ELB DNS name.
- [x] Assign EIPs to all web servers. Configure a Route 53 record set with all EIPs. With health checks and DNS failover.
- [ ] Configure ELB with an EIP Place all your Web servers behind ELB Configure a Route 53 A record that points to the EIP.

- - - - - -

### 20
You need to configure an Amazon S3 bucket to serve static assets for your public-facing web application. Which methods ensure that all objects uploaded to the bucket are set to public read? (Choose 2 answers)

- [x] Set permissions on the object to public read during upload.
- [ ] Configure the bucket ACL to set all objects to public read.
- [x] Configure the bucket policy to set all objects to public read.
- [ ] Use AWS Identity and Access Management roles to set the bucket to public read.
- [ ] Amazon S3 objects default to public read, so no action is needed.

- - - - - -

### 21
A major customer has asked you to set up his AWS infrastructure so that it will be easy to recover in the case of a disaster of some sort. Which of the following is important when thinking about being able to quickly launch resources in AWS to ensure business continuity in case of a disaster?

- [ ] Create and maintain AMIs of key servers where fast recovery is required.
- [ ] Regularly run your servers, test them, and apply any software updates and configuration changes.
- [x] All items listed here are important when thinking about disaster recovery.
- [ ] Ensure that you have all supporting custom software packages available in AWS.

- - - - - -

### 22
You are developing a new mobile application and are considering storing user preferences in AWS. This would provide a more uniform cross-device experience to users using multiple mobile devices to access the application. The preference data for each user is estimated to be SOKB in size Additionally 5 million customers are expected to use the application on a regular basis. The solution needs to be cost-effective, highly available, scalable and secure, how would you design a solution to meet the above requirements?

- [ ] Setup an RDS MySQL instance in 2 Availability Zones to store the user preference data. Deploy a public facing application on a server in front of the database to manage security and access credentials.
- [x] Setup a DynamoDB table with an item for each user having the necessary attributes to hold the user preferences. The mobile application will query the user preferences directly from the DynamoDB table. Utilize ST.
- [ ] Web Identity Federation, and DynamoDB Fine Grained Access Control to authenticate and authorize access.
- [ ] Setup an RDS MySQL instance with multiple read replicas in 2 Availability Zones to store the user preference data. The mobile application will query the user preferences from the read replicas. Leverage the MySQL user management and access privilege system to manage security and access credentials.
- [ ] Store the user preference data in S3 Setup a DynamoDB table with an item for each user and an item attribute pointing to the user' S3 object. The mobile application will retrieve the S3 URL from DynamoDB and then access the S3 object directly utilize STS, Web identity Federation, and S3 ACLs to authenticate and authorize access.

- - - - - -

### 23
In the Amazon RDS which uses the SQL Server engine, what is the maximum size for a Microsoft SQL Server DB Instance with SQL Server Express edition?

- [x] 10GB per DB.
- [ ] 100GB per DB.
- [ ] 2TB per DB.
- [ ] 1TB per DB.

- - - - - -

### 24
You have deployed a web application targeting a global audience across multiple AWS Regions under the domain name.example.com. You decide to use Route 53 Latency-Based Routing to serve web requests to users from the region closest to the user. To provide business continuity in the event of server downtime you configure weighted record sets associated with two web servers in separate Availability Zones per region. Dunning a DR test you notice that when you disable all web servers in one of the regions Route 53 does not automatically direct all users to the other region. What could be happening? (Choose 2 answers)

- [ ] Latency resource record sets cannot be used in combination with weighted resource record sets.
- [x] You did not setup an HTTP health check tor one or more of the weighted resource record sets associated with me disabled web servers.
- [ ] The value of the weight associated with the latency alias resource record set in the region with the disabled servers is higher than the weight for the other region.
- [ ] One of the two working web servers in the other region did not pass its HTTP health check.
- [x] You did not set 'Evaluate Target Health' to 'Yes' on the latency alias resource record set associated with example com in the region where you disabled the servers.

- - - - - -

### 25
Amazon EBS provides the ability to create backups of any Amazon EC2 volume into what is known as [...].

- [x] snapshots.
- [ ] images.
- [ ] instance backups.
- [ ] mirrors.

- - - - - -

### 26
You've been hired to enhance the overall security posture for a very large e-commerce site They have a well architected multi-tier application running in a VPC that uses ELBs in front of both the web and the app tier with static assets served directly from S3 They are using a combination of RDS and DynamoOB for their dynamic data and then archiving nightly into S3 for further processing with EMR They are concerned because they found questionable log entries and suspect someone is attempting to gain unauthorized access. Which approach provides a cost effective scalable mitigation to this kind of attack?

- [ ] Recommend that they lease space at a DirectConnect partner location and establish a lG DirectConnect connection to their vPC they would then establish Internet connectivity into their space, filter the traffic in hardware Web Application Firewall (WAF). And then pass the traffic through the DirectConnect connection into their application running in their VPC,
- [ ] Add previously identified hostile source IPs as an explicit INBOUND DENY NACL to the web tier sub net.
- [x] Add a WAF tier by creating a new ELB and an AutoScaling group of EC2 Instances running a host based WAF They would redirect Route 53 to resolve to the new WAF tier ELB The WAF tier wouldthier pass the traffic to the current web tier The web tier Security Groups would be updated to only allow traffic from the WAF tier Security Group
- [ ] Remove all but TLS 1 2 from the web tier ELB and enable Advanced Protocol Filtering This will enable the ELB itself to perform WAF functionality.

- - - - - -

### 27
You are designing the network infrastructure for an application server in Amazon VPC Users will access all the application instances from the Internet as well as from an on-premises network The on-premises network is connected to your VPC over an AWS Direct Connect link. How would you design routing to meet the above requirements?

- [x] Configure a single routing Table with a default route via the Internet gateway Propagate a default route via BGP on the AWS Direct Connect customer router. Associate the routing table with all VPCsubnets.
- [ ] Configure a single routing table with a default route via the internet gateway Propagate specific routes for the on-premises networks via BGP on the AWS Direct Connect customer router Associatethe routing table with all VPC subnets.
- [ ] Configure a single routing table with two default routes: one to the internet via an Internet gateway the other to the on-premises network via the VPN gateway use this routing table across all subnets in your VPC.
- [ ] Configure two routing tables one that has a default route via the Internet gateway and another that has a default route via the VPN gateway Associate both routing tables with each VPC subnet.

- - - - - -

### 28
You have multiple VPN connections and want to provide secure communication between sites using the AWS VPN CloudHub. Which statement is the most accurate in describing what you must do to set this up correctly?

- [x] Create a virtual private gateway with multiple customer gateways, each with unique Border Gateway Protocol (BGP) Autonomous System Numbers (ASNs).
- [ ] Create a virtual private gateway with multiple customer gateways, each with a unique set of keys.
- [ ] Create a virtual public gateway with multiple customer gateways, each with a unique Private subnet.
- [ ] Create a virtual private gateway with multiple customer gateways, each with unique subnet id.

- - - - - -

### 29
A user is aware that a huge download is occurring on his instance. He has already set the Auto Scaling policy to increase the instance count when the network I/O increases beyond a certain limit. How can the user ensure that this temporary event does not result in scaling?

- [ ] The network I/O are not affected during data download.
- [ ] The policy cannot be set on the network I/O.
- [ ] There is no way the user can stop scaling as it is already configured.
- [x] Suspend scaling.

- - - - - -

### 30
The Amazon EC2 web service can be accessed using the [...] web services messaging protocol. This interface is described by a Web Services Description Language (WSDL) document.

- [x] SOAP.
- [ ] DCOM.
- [ ] CORBA.
- [ ] XML-RPC.

- - - - - -

### 31
Which of the following are true regarding encrypted Amazon Elastic Block Store (EBS) volumes? (Choose 2 answers)

- [x] Supported on all Amazon EBS volume types.
- [x] Snapshots are automatically encrypted.
- [ ] Available to all instance types.
- [ ] Existing volumes can be encrypted.
- [ ] Shared volumes can be encrypted.

- - - - - -

### 32
Is Federated Storage Engine currently supported by Amazon RDS for MySQL?

- [ ] Only for Oracle RDS instances.
- [ ] Yes.
- [x] No.
- [ ] Only in VPC.

- - - - - -

### 33
While creating the snapshots using the API, which Action should I be using?

- [ ] MakeSnapShot.
- [ ] FreshSnapshot.
- [ ] DeploySnapshot.
- [x] CreateSnapshot.

- - - - - -

### 34
A customer needs to capture all client connection information from their load balancer every five minutes. The company wants to use this data for analyzing traffic patterns and troubleshooting their applications. Which of the following options meets the customer requirements?

- [x] Enable AWS CloudTrail for the load balancer.
- [ ] Enable access logs on the load balancer.
- [ ] Install the Amazon CloudWatch Logs agent on the load balancer.
- [ ] Enable Amazon CloudWatch metrics on the load balancer.

- - - - - -

### 35
Will my standby RDS instance be in the same Region as my primary?

- [ ] Only for Oracle RDS types.
- [x] Yes.
- [ ] Only if configured at launch.
- [ ] No.

- - - - - -

### 36
If I want my instance to run on a single-tenant hardware, which value do I have to set the instance's tenancy attribute to?

- [x] Dedicated.
- [ ] Isolated.
- [ ] One.
- [ ] Reserved.

- - - - - -

### 37
Can the string value of 'Key' be prefixed with :aws:'?

- [ ] Only in GovCloud.
- [ ] Only for S3 not EC2.
- [ ] Yes.
- [x] No.

- - - - - -

### 38
A user wants to increase the durability and availability of the EBS volume. Which of the below mentioned actions should he perform?

- [x] Take regular snapshots.
- [ ] Create an AM.
- [ ] Create EBS with higher capacity.
- [ ] Access EBS regularly.

- - - - - -

### 39
What does Amazon RDS stand for?

- [ ] Regional Data Server.
- [x] Relational Database Service.
- [ ] Nothing.
- [ ] Regional Database Service.

- - - - - -

### 40
You have been asked to set up monitoring of your network and you have decided that Cloudwatch would be the best service to use. Amazon CloudWatch monitors your Amazon Web Services (AWS) resources and the applications you run on AWS in real-time. You can use CloudWatch to collect and track metrics, which are the variables you want to measure for your resources and applications. Which of the following items listed can AWS Cloudwatch monitor?

- [ ] Log files your applications generate.
- [x] All of the items listed on this page.
- [ ] System-wide visibility into resource utilization, application performance, and operational health.
- [ ] Custom metrics generated by your applications and services.

- - - - - -

### 41
What is the maximum write throughput I can provision for a single Dynamic DB table?

- [ ] 1,000 write capacity units.
- [ ] 100,000 write capacity units.
- [x] Dynamic DB is designed to scale without limits, but if you go beyond 10,000 you have to contact AWS first.
- [ ] 10,000 write capacity units.

- - - - - -

### 42
Do Amazon EBS volumes persist independently from the running life of an Amazon EC2 instance?

- [ ] Yes, they do but only if they are detached from the instance.
- [ ] No, you cannot attach EBS volumes to an instance.
- [ ] No, they are dependent.
- [x] Yes, they do.

- - - - - -

### 43
What is a Security Group?

- [ ] None of these.
- [ ] A list of users that can access Amazon EC2 instances.
- [ ] An Access Control List (ACL) for AWS resources.
- [x] A firewall for inbound traffic, built-in around every Amazon EC2 instance.

- - - - - -

### 44
You need to set up a high level of security for an Amazon Relational Database Service (RDS) you have just built in order to protect the confidential information stored in it. What are all the possible security groups that RDS uses?

- [x] DB security groups, VPC security groups, and EC2 security groups.
- [ ] DB security groups only.
- [ ] EC2 security groups only.
- [ ] VPC security groups, and EC2 security groups.

- - - - - -

### 45
In the 'Detailed' monitoring data available for your Amazon EBS volumes, Provisioned IOPS volumes automatically send [...] minute metrics to Amazon CloudWatch.

- [ ] 3.
- [x] 1.
- [ ] 5.
- [ ] 2.

- - - - - -

### 46
You are looking at ways to improve some existing infrastructure as it seems a lot of engineering resources are being taken up with basic management and monitoring tasks and the costs seem to be excessive. You are thinking of deploying Amazon ElasticCache to help. Which of the following statements is true in regards to ElasticCache?

- [ ] You can improve load and response times to user actions and queries however the cost associated with scaling web applications will be more.
- [ ] You can't improve load and response times to user actions and queries but you can reduce the cost associated with scaling web applications.
- [ ] You can improve load and response times to user actions and queries however the cost associated with scaling web applications will remain the same.
- [x] You can improve load and response times to user actions and queries and also reduce the cost associated with scaling web applications.

- - - - - -

### 47
A customer needs corporate IT governance and cost oversight of all AWS resources consumed by its divisions. The divisions want to maintain administrative control of the discrete AWS resources they consume and keep those resources separate from the resources of other divisions. Which of the following options, when used together will support the autonomy/control of divisions while enabling corporate IT to maintain governance and cost oversight? (Choose 2 answers)

- [ ] Use AWS Consolidated Billing and disable AWS root account access for the child accounts.
- [ ] Enable IAM cross-account access for all corporate IT administrators in each child account.
- [ ] Create separate VPCs for each division within the corporate IT AWS account.
- [x] Use AWS Consolidated Billing to link the divisions' accounts to a parent corporate account.
- [x] Write all child AWS CloudTrail and Amazon CloudWatch logs to each child account's Amazon S3 'Log' bucket.

- - - - - -

### 48
After creating a new IAM user which of the following must be done before they can successfully make API calls?

- [ ] Add a password to the user.
- [ ] Enable Multi-Factor Authentication for the user.
- [ ] Assign a Password Policy to the user.
- [x] Create a set of Access Keys for the user.

- - - - - -

### 49
A friend wants you to set up a small BitTorrent storage area for him on Amazon S3. You tell him it is highly unlikely that AWS would allow such a thing in their infrastructure. However you decide to investigate. Which of the following statements best describes using BitTorrent with Amazon S3?

- [ ] Amazon S3 does not support the BitTorrent protocol because it is used for pirated software.
- [ ] You can use the BitTorrent protocol but only for objects that are less than 100 GB in size.
- [ ] You can use the BitTorrent protocol but you need to ask AWS for specific permissions first.
- [x] You can use the BitTorrent protocol but only for objects that are less than 5 GB in size.

- - - - - -

### 50
IAM's Policy Evaluation Logic always starts with a default [...] for every request, except for those that use the AWS account's root security credentials?

- [ ] Permit.
- [x] Deny.
- [ ] Cancel.

- - - - - -

