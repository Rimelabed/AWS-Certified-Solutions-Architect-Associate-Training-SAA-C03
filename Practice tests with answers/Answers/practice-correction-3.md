### 1
You have been given a scope to deploy some AWS infrastructure for a large organization. The requirements are that you will have a lot of EC2 instances but may need to add more when the average utilization of your Amazon EC2 fleet is high and conversely remove them when CPU utilization is low. Which AWS services would be best to use to accomplish this?

- [ ] Auto Scaling, Amazon CloudWatch and AWS Elastic Beanstalk.
- [x] Auto Scaling, Amazon CloudWatch and Elastic Load Balancing.
- [ ] Amazon CloudFront, Amazon CloudWatch and Elastic Load Balancing.
- [ ] AWS Elastic Beanstalk, Amazon CloudWatch and Elastic Load Balancing.

- - - - - -

### 2
When does the billing of an Amazon EC2 system begin?

- [ ] It starts when the Status column for your distribution changes from Creating to Deployed.
- [ ] It starts as soon as you click the create instance option on the main EC2 console.
- [ ] It starts when your instance reaches 720 instance hours.
- [x] It starts when Amazon EC2 initiates the boot sequence of an AMI instance.

- - - - - -

### 3
A user is storing a large number of objects on AWS S3. The user wants to implement the search functionality among the objects. How can the user achieve this?

- [ ] Use the indexing feature of S3.
- [ ] Tag the objects with the metadata to search on that.
- [ ] Use the query functionality of S3.
- [x] Make your own DB system which stores the S3 metadata for the search functionality.

- - - - - -

### 4
A corporate web application is deployed within an Amazon Virtual Private Cloud (VPC) and is connected to the corporate data center via an IPsec VPN. The application must authenticate against the on-premises LDAP server. After authentication, each logged-in user can only access an Amazon Simple Storage Space (S3) keyspace specific to that user. Which two approaches can satisfy these objectives? (Choose 2 answers)

- [ ] Develop an identity broker that authenticates against IAM security Token service to assume a Lam role in order to get temporary AWS security credentials The application calls the identity broker toget AWS temporary security credentials with access to the appropriate S3 bucket.
- [x] The application authenticates against LDAP and retrieves the name of an IAM role associated with the user. The application then ca lls the IAM Security Token Service to assume that IAM role The application can use the temporary credentials to access the appropriate S3 bucket.
- [x] Develop an identity broker that authenticates against LDAP and then calls IAM Security To ken Service to get IAM federated user credentials The application calls the identity broker to get IAMfederated user credentials with access to the appropriate S3 bucket.
- [ ] The application authenticates against LDAP the application then calls the AWS identity and Access Management (IAM) Security service to log in to IAM using the LDAP credentials the application can use the IAM temporary credentials to access the appropriate S3 bucket.
- [ ] The application authenticates against IAM Security Token Service using the LDAP credentials the application uses those temporary AWS security credentials to access the appropriate S3 bucket.

- - - - - -

### 5
A group can contain many users. Can a user belong to multiple groups?

- [x] Yes always.
- [ ] No.
- [ ] Yes but only if they are using two factor authentication.
- [ ] Yes but only in VPC.

- - - - - -

### 6
Does Dynamo DB support in-place atomic updates?

- [ ] It is not defined.
- [x] Yes.
- [ ] It does support in-place non-atomic updates.

- - - - - -

### 7
Can you move a Reserved Instance from one Availability Zone to another?

- [x] Yes, but each Reserved Instance is associated with a specific Region that cannot be changed.
- [ ] Yes, only in US-West-2.
- [ ] Yes, only in US-East-1.
- [ ] No.

- - - - - -

### 8
You want to establish a dedicated network connection from your premises to AWS in order to save money by transferring data directly to AWS rather than through your internet service provider. You are sure there must be some other benefits beyond cost savings. Which of the following statements would be the best choice to put your client's mind at rest?

- [ ] Different instances running on the same physical machine are isolated from each other via a 256-bit Advanced Encryption Standard (AES-256).
- [ ] Different instances running on the same physical machine are isolated from each other via the Xen hypervisor and via a 256-bit Advanced Encryption Standard (AES-256).
- [x] Different instances running on the same physical machine are isolated from each other via the Xen hypervisor.
- [ ] Different instances running on the same physical machine are isolated from each other via IAM permissions.

- - - - - -

### 9
Can I detach the primary (ethO) network interface when the instance is running or stopped?

- [ ] Yes, You can.
- [x] No. You cannot.

- - - - - -

### 10
You have launched an Amazon Elastic Compute Cloud (EC2) instance into a public subnet with a primary private I P address assigned, an internet gateway is attached to the VPC, and the public route table is configured to send all Internet-based traffic to the Internet gateway. The instance security group is set to allow all outbound traffic but cannot access the internet. Why is the Internet unreachable from this instance?

- [x] The instance does not have a public IP address.
- [ ] The internet gateway security group must allow all outbound traffic.
- [ ] The instance security group must allow all inbound traffic.
- [ ] The instance 'Source/Destination check' property must be enabled.

- - - - - -

### 11
Which of the following statements best describes the differences between Elastic Beanstalk and CloudFormation?

- [ ] Elastic Beanstalk uses Elastic load balancing and CloudFormation doesn't.
- [ ] CloudFormation is faster in deploying applications than Elastic Beanstalk.
- [ ] Elastic Beanstalk is faster in deploying applications than CloudFormation.
- [x] CloudFormation is much more powerful than Elastic Beanstalk, because you can actually design and script custom resources.

- - - - - -

### 12
It is advised that you watch the Amazon CloudWatch [...] metric (available via the AWS Management Console or Amazon Cloud Watch APIs) carefully and recreate the Read Replica should it fall behind due to replication errors.

- [ ] Write Lag.
- [ ] Read Replica.
- [x] Replica Lag.
- [ ] Single Replica.

- - - - - -

### 13
Your application provides data transformation services. Files containing data to be transformed are first uploaded to Amazon S3 and then transformed by a fleet of spot EC2 instances. Fi les submitted by your premium customers must be transformed with the highest priority. How should you implement such a system?

- [ ] Use a DynamoDB table with an attribute defining the priority level. Transformation instances will scan the table for tasks, sorting the results by priority level.
- [ ] Use Route 53 latency based-routing to send high priority tasks to the closest transformation instances.
- [x] Use two SQS queues, one for high priority messages, the other for default priority. Transformation instances first poll the high priority queue; if there is no message, they poll the default priority queue.
- [ ] Use a single SQS queue. Each message contains the priority level. Transformation instances poll high-priority messages first.

- - - - - -

### 14
True or False: When you view the block device mapping for your instance, you can see only the EBS volumes, not the instance store volumes.

- [ ] Depends on the instance type.
- [ ] False.
- [ ] Depends on whether you use API call.
- [x] True.

- - - - - -

### 15
Does AWS CloudFormation support Amazon EC2 tagging?

- [x] Yes, AWS CloudFormation supports Amazon EC2 tagging.
- [ ] No, CloudFormation doesn't support any tagging.
- [ ] No, it doesn't support Amazon EC2 tagging.
- [ ] It depends if the Amazon EC2 tagging has been defined in the template.

- - - - - -

### 16
If I modify a DB Instance or the DB parameter group associated with the instance, should I reboot the instance for the changes to take effect?

- [x] Yes.
- [ ] No.

- - - - - -

### 17
If you are using Amazon RDS Provisioned IOPS storage with MySQL and Oracle database engines, you can scale the throughput of your database Instance by specifying the IOPS rate from [...].

- [ ] 1,000 to 100,000.
- [ ] 100 to 1,000.
- [ ] 10,000 to 100,000.
- [x] 1,000 to 10,000.

- - - - - -

### 18
To specify a resource in a policy statement, in Amazon EC2, can you use its Amazon Resource Name (ARN)?

- [x] Yes, you can.
- [ ] No, you can't because EC2 is not related to AR
- [ ] No, you can't because you can't specify a particular Amazon EC2 resource in an IAM policy.
- [ ] Yes, you can but only for the resources that are not affected by the action.

- - - - - -

### 19
An enterprise wants to use a third-party SaaS application. The SaaS application needs to have access to issue several API commands to discover Amazon EC2 resources running within the enterprise's account The enterprise has internal security policies that require any outside access to their environment must conform to the principles of least privilege and there must be controls in place to ensure that the credentials used by the 5aa5 vendor cannot be used by any other third party. Which of the following would meet all of these conditions?

- [ ] From the AWS Management Console, navigate to the Security Credentials page and retrieve the access and secret key for your account.
- [ ] Create an IAM user within the enterprise account assign a user policy to the IAM user that allows only the actions required by the SaaS application create a new access and secret key for the user and provide these credentials to the 5aa5 provider.
- [x] Create an IAM role for cross-account access allows the SaaS provider's account to assume the role and assign it a policy that allows only the actions required by the SaaS application.
- [ ] Create an IAM role for EC2 instances, assign it a policy that allows only the actions required tor the Saas application to work, provide the role ARM to the SaaS provider to use when launching their application instances.

- - - - - -

### 20
By default what are ENIs that are automatically created and attached to instances using the EC2 console set to do when the attached instance terminates?

- [ ] Remain as is.
- [x] Terminate.
- [ ] Hibernate.
- [ ] Pause.

- - - - - -

### 21
In EC2, what happens to the data in an instance store if an instance reboots (either intentionally or unintentionally)?

- [ ] Data is deleted from the instance store for security reasons.
- [x] Data persists in the instance store.
- [ ] Data is partially present in the instance store.
- [ ] Data in the instance store will be lost.

- - - - - -

### 22
You are designing a social media site and are considering how to mitigate distributed denial-of service (DDoS) attacks. Which of the below are viable mitigation techniques? (Choose 3 answers)

- [ ] Add multiple elastic network interfaces (ENis) to each EC2 instance to increase the network bandwidth.
- [ ] Use dedicated instances to ensure that each instance has the maximum performance possible.
- [x] Use an Amazon CloudFront distribution for both static and dynamic content.
- [x] Use an Elastic Load Balancer with auto scaling groups at the web. App and Amazon Relational Database Service (RDS) tiers.
- [x] Add alert Amazon CloudWatch to look for high Network in and CPU utilization.
- [ ] Create processes and capabilities to quickly add and remove rules to the instance OS firewall.

- - - - - -

### 23
In Amazon CloudFront, if you use Amazon EC2 instances and other custom origins with CloudFront, it is recommended to [...].

- [ ] not use Elastic Load Balancing.
- [ ] restrict Internet communication to private instances while allowing outgoing traffic.
- [ ] enable access key rotation for CloudWatch metrics.
- [x] specify the URL of the load balancer for the domain name of your origin server.

- - - - - -

### 24
Which of the following statements is true regarding attaching network interfaces to your instances in your VPC?

- [ ] You can attach 5 ENIs per instance type.
- [ ] You can attach as many ENIs as you want.
- [x] The number of ENIs you can attach varies by instance type.
- [ ] You can attach 100 ENIs total regardless of instance type.

- - - - - -

### 25
What is the reason for this?

- [ ] For security reasons.
- [ ] Hardware restrictions.
- [x] Public (IPV4) internet addresses are a scarce resource.
- [ ] There are only 5 network interfaces per instance.

- - - - - -

### 26
Can a 'user' be associated with multiple AWS accounts?

- [ ] Yes.
- [x] No.

- - - - - -

### 27
You have an application running on an Amazon Elastic Compute Cloud instance, that uploads 5 GB video objects to Amazon Simple Storage Service (S3). Video uploads are taking longer than expected, resulting in poor application performance. Which method will help improve performance of your application?

- [ ] Enable enhanced networking.
- [x] Use Amazon S3 multipart upload.
- [ ] Leveraging Amazon CloudFront, use the HTTP POST method to reduce latency.
- [ ] Use Amazon Elastic Block Store Provisioned IOPs and use an Amazon EBS-optimized instance.

- - - - - -

### 28
You have been given a scope to set up an AWS Media Sharing Framework for a new start up photo sharing company similar to flickr. The first thing that comes to mind about this is that it will obviously need a huge amount of persistent data storage for this framework. Which of the following storage options would be appropriate for persistent storage?

- [ ] Amazon Glacier or Amazon S3.
- [ ] Amazon Glacier or AWS Import/Export.
- [ ] AWS Import/Export or Amazon CloudFront.
- [x] Amazon EBS volumes or Amazon S3.

- - - - - -

### 29
You need a persistent and durable storage to trace call activity of an IVR (Interactive Voice Response) system. Call duration is mostly in the 2-3 minutes timeframe. Each traced call can be either active or terminated. An external application needs to know each minute the list of currently active calls, which are usually a few calls/second. Put once per month there is a periodic peak up to 1000 calls/second for a few hours. The system is open 24/7 and any downtime should be avoided. Historical data is periodically archived to files. Cost saving is a priority for this project. What database implementation would better fit this scenario, keeping costs as low as possible?

- [x] Use RDS Multi-AZ with two tables, one for 'Active calls' and one for 'Terminated calls'. in this way the 'Active calls' table is always small and effective to access.
- [ ] Use DynamoDB with a 'Calls' table and a Global Secondary Index on a 'lsActive' attribute that is present for active calls only in this way the Global Secondary index is sparse and more effective.
- [ ] Use DynamoDB with a 'Calls' table and a Global secondary index on a 'State' attribute that can equal to 'active' or 'terminated' in this way the Global Secondary index can be used for all Items in the table.
- [ ] Use RDS Multi-AZ with a 'CALLS' table and an Indexed 'STATE* field that can be equal to 'ACTIVE' or 'TERMINATED' in this way the SOL query Is optimized by the use of the Index.

- - - - - -

### 30
If you have chosen Multi-AZ deployment, in the event of a planned or unplanned outage of your primary DB Instance, Amazon RDS automatically switches to the standby replica. The automatic failover mechanism simply changes the record of the main DB Instance to point to the standby DB Instance.

- [ ] DNAME.
- [x] CNAME.
- [ ] TXT.
- [ ] MX.

- - - - - -

### 31
All Amazon EC2 instances are assigned two IP addresses at launch. Which are those?

- [ ] 2 Elastic IP addresses.
- [ ] A private IP address and an Elastic IP address.
- [ ] A public IP address and an Elastic IP address.
- [x] A private IP address and a public IP address.

- - - - - -

### 32
You need to pass a custom script to new Amazon Linux instances created in your Auto Scaling group. Which feature allows you to accomplish this?

- [ ] User data.
- [x] EC2Config service.
- [ ] IAM roles.
- [ ] AWS Config.

- - - - - -

### 33
A customer wants to track access to their Amazon Simple Storage Service (S3) buckets and also use this information for their internal security and access audits. Which of the following will meet the Customer requirement?

- [x] Enable AWS CloudTrail to audit all Amazon S3 bucket access.
- [ ] Enable server access logging for all required Amazon S3 buckets.
- [ ] Enable the Requester Pays option to track access via AWS Billing.
- [ ] Enable Amazon S3 event notifications for Put and Post.

- - - - - -

### 34
Which DNS name can only be resolved within Amazon EC2?

- [ ] Public DNS name.
- [x] Internal DNS name.
- [ ] External DNS name.
- [ ] Global DNS name.

- - - - - -

### 35
An AWS customer is deploying an application mat is composed of an AutoScaling group of EC2 Instances. The customers security policy requires that every outbound connection from these instances to any other service within the customers Virtual Private Cloud must be authenticated using a unique x 509 certificate that contains the specific instance-id. In addition an x 509 certificates must Designed by the customer's Key management service in order to be trusted for authentication. Which of the following configurations will support these requirements?

- [ ] Configure an IAM Role that grants access to an Amazon S3 object containing a signed certificate and configure me Auto Scaling group to launch instances with this role Have the instances bootstrap get the certificate from Amazon S3 upon first boot.
- [ ] Embed a certificate into the Amazon Machine Image that is used by the Auto Scaling group Have the launched instances generate a certificate signature request with the instance's assigned instance- id to the Key management service for signature.
- [x] Configure the Auto Scaling group to send an SNS notification of the launch of a new instance to the trusted key management service. Have the Key management service generate a signed certificate and send it directly to the newly launched instance.
- [ ] Configure the launched instances to generate a new certificate upon first boot Have the Key management service poll the AutoScaling group for associated instances and send new instances a certificate signature (hat contains the specific instance-id.

- - - - - -

### 36
A company is storing data on Amazon Simple Storage Service (S3). The company's security policy mandates that data is encrypted at rest. Which of the following methods can achieve this? (Choose 3 answers)

- [x] Use Amazon S3 server-side encryption with AWS Key Management Service managed keys.
- [x] Use Amazon S3 server-side encryption with customer-provided keys.
- [ ] Use Amazon S3 server-side encryption with EC2 key pair.
- [ ] Use Amazon S3 bucket policies to restrict access to the data at rest.
- [x] Encrypt the data on the client-side before ingesting to Amazon S3 using their own master key.
- [ ] Use SSL to encrypt the data while in transit to Amazon S3.

- - - - - -

### 37
In Amazon EC2, you are billed instance-hours when [...].

- [x] your EC2 instance is in a running state.
- [ ] the instance exits from Amazon S3 console.
- [ ] your instance still exits the EC2 console.
- [ ] EC2 instances stop.

- - - - - -

### 38
Which of the below mentioned options is a possible solution to avoid any security threat?

- [ ] Use the IAM based single sign between the AWS resources and the organization application.
- [x] Use the IAM role and assign it to the instance.
- [ ] Since the application is hosted on EC2, it does not need credentials to access S3.
- [ ] Use the 509 certificates instead of the access and the secret access keys.

- - - - - -

### 39
In Amazon EC2 Container Service components, what is the name of a logical grouping of container instances on which you can place tasks?

- [x] A cluster.
- [ ] A container instance.
- [ ] A container.
- [ ] A task definition.

- - - - - -

### 40
You are looking to migrate your Development (Dev) and Test environments to AWS. You have decided to use separate AWS accounts to host each environment. You plan to link each accounts bill to a Master AWS account using Consolidated Billing. To make sure you Keep within budget you would like to implement a way for administrators in the Master account to have access to stop, delete and/or terminate resources in both the Dev and Test accounts. Identify which option will allow you to achieve this goal.

- [ ] Create IAM users in the Master account with full Admin permissions. Create cross-account roles in the Dev and Test accounts that grant the Master account access to the resources in the account by inheriting permissions from the Master account.
- [ ] Create IAM users and a cross-account role in the Master account that grants full Admin permissions to the Dev and Test accounts.
- [x] Create IAM users in the Master account Create cross-account roles in the Dev and Test accounts that have full Admin permissions and grant the Master.
- [ ] Link the accounts using Consolidated Billing. This will give IAM users in the Master account access to resources in the Dev and Test accounts.

- - - - - -

### 41
What will be the status of the snapshot until the snapshot is complete?

- [ ] Running.
- [ ] Working.
- [ ] Progressing.
- [x] Pending.

- - - - - -

### 42
A customer is running a multi-tier web application farm in a virtual private cloud (VPC) that is not connected to their corporate network. They are connecting to the VPC over the Internet to manage all of their Amazon EC2 instances running in both the public and private subnets. They have only authorized the bastion-security-group with Microsoft Remote Desktop Protocol (RDP) access to the application instance security groups, but the company wants to further limit administrative access to all of the instances in the VPC. Which of the following Bastion deployment scenarios will meet this requirement?

- [ ] Deploy a Windows Bastion host on the corporate network that has RDP access to all instances in the VP.
- [ ] Deploy a Windows Bastion host with an Elastic IP address in the public subnet and allow SSH access to the bastion from anywhere.
- [x] Deploy a Windows Bastion host with an Elastic IP address in the private subnet, and restrict RDP access to the bastion from only the corporate public IP addresses.
- [ ] Deploy a Windows Bastion host with an auto-assigned Public IP address in the public subnet, and allow RDP access to the bastion from only the corporate public IP addresses.

- - - - - -

### 43
True or False: Common points of failures like generators and cooling equipment are shared across Availability Zones.

- [ ] True.
- [x] False.

- - - - - -

### 44
A company is building a voting system for a popular TV show, viewers win watch the performances then visit the show's website to vote for their favorite performer. It is expected that in a short period of time after the show has finished the site will receive millions of visitors. The visitors will first login to the site using their Amazon.com credentials and then submit their vote. After the voting is completed the page will display the vote totals. The company needs to build the site such that can handle the rapid influx of traffic while maintaining good performance but also wants to keep costs to a minimum. Which of the design patterns below should they use?

- [ ] Use CloudFront and an Elastic Load balancer in front of an auto-scaled set of web servers, the web servers will first can the Login With Amazon service to authenticate the user then process the users vote and store the result into a multi-AZ Relational Database Service instance.
- [ ] Use CloudFront and the static website hosting feature of S3 with the Javascript SDK to call the Login With Amazon service to authenticate the user, use IAM Roles to gain permissions to a DynamoDB table to store the users vote.
- [ ] Use CloudFront and an Elastic Load Balancer in front of an auto-scaled set of web servers, the web servers will first call the Login with Amazon service to authenticate the user, the web servers will process the users vote and store the result into a DynamoDB table using IAM Roles for EC2 instances to gain permissions to the DynamoDB table.
- [x] Use CloudFront and an Elastic Load Balancer in front of an auto-scaled set of web servers, the web servers will first call the Login. With Amazon service to authenticate the user, the web servers win process the users vote and store the result into an SQS queue using IAM Roles for EC2 Instances to gain permissions to the SQS queue. A set of application servers will then retrieve the items from the queue and store the result into a DynamoDB table.

- - - - - -

### 45
You are designing a photo sharing mobile app the application will store all pictures in a single Amazon S3 bucket. Users will upload pictures from their mobile device directly to Amazon S3 and will be able to view and download their own pictures directly from Amazon S3. You want to configure security to handle potentially millions of users in the most secure manner possible. What should your server-side application do when a new user registers on the photo sharing mobile application?

- [ ] Create a set of long-term credentials using AWS Security Token Service with appropriate permissions Store these credentials in the mobile app and use them to access Amazon S3.
- [x] Record the user's Information in Amazon RDS and create a role in IAM with appropriate permissions. When the user uses their mobile app create temporary credentials using the AWS Security Token Service 'Assume Role' function Store these credentials in the mobile app's memory and use them to access Amazon S3 Generate new credentials the next time the user runs the mobile app.
- [ ] Record the user's Information in Amazon DynamoDB.
- [ ] When the user uses their mobile app create temporary credentials using AWS Security Token Service with appropriate permissions Store these credentials in the mobile app's memory and use them to access Amazon S3 Generate new credentials the next time the user runs the mobile app.
- [ ] Create IAM user. Assign appropriate permissions to the IAM user Generate an access key and secret key for the IAM user, store them in the mobile app and use these credentials to access Amazon S3.
- [ ] Create an IAM user. Update the bucket policy with appropriate permissions for the IAM user Generate an access Key and secret Key for the IAM user, store them in the mobile app and use these credentials to access Amazon S3.

- - - - - -

### 46
Is there a limit to how many groups a user can be in?

- [x] Yes for all users.
- [ ] Yes for all users except root.
- [ ] No.
- [ ] Yes unless special permission granted.

- - - - - -

### 47
Which is the default region in AWS?

- [ ] eu-west-1.
- [x] us-east-1.
- [ ] us-east-2.
- [ ] ap-southeast-1.

- - - - - -

### 48
Your company hosts a social media site supporting users in multiple countries. You have been asked to provide a highly available design tor the application that leverages multiple regions tor the most recently accessed content and latency sensitive portions of the wet) site The most latency sensitive component of the application involves reading user preferences to support web site personalization and ad selection. In addition to running your application in multiple regions, which option will support this application's requirements?

- [x] Serve user content from S3. CloudFront and use Route 53 latency-based routing between ELBs in each region Retrieve user preferences from a local DynamoDB table in each region and leverage SQS to capture changes to user preferences with 505 workers for propagating updates to each table.
- [ ] Use the 53 Copy API to copy recently accessed content to multiple regions and serve user content from S3. CloudFront with dynamic content and an ELB in each region Retrieve user preferences from an ElasticCache cluster in each region and leverage SNS notifications to propagate user preference changes to a worker node in each region.
- [ ] Use the 53 Copy API to copy recently accessed content to multiple regions and serve user content from S3 CloudFront and Route 53 latency-based routing Between ELBs in each region Retrieve user preferences from a DynamoDB table and leverage SQS to capture changes to user preferences with 505 workers for propagating DynamoDB updates.
- [ ] Serve user content from S3. CloudFront with dynamic content, and an ELB in each region Retrieve user preferences from an ElastiCache cluster in each region and leverage Simple Workflow (SWF) to manage the propagation of user preferences from a centralized OB to each ElastiCache cluster.

- - - - - -

### 49
A [...] is a document that provides a formal statement of one or more permissions.

- [x] policy.
- [ ] permission.
- [ ] role.
- [ ] resource.

- - - - - -

### 50
A company wants to implement their website in a virtual private cloud (VPC). The web tier will use an Auto Scaling group across multiple Availability Zones (AZs). The database will use Multi-AZ RDSMySQL and should not be publicly accessible. What is the minimum number of subnets that need to be configured in the VPC?

- [ ] 1.
- [ ] 2.
- [ ] 3.
- [x] 4.

- - - - - -

