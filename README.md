 # AWS CLF-02 Cloud Practitioner

Important note: Google searching criteria: examtopics aws clf-c02 Question #222

## 1. A company plans to use an Amazon Snowball Edge device to transfer files to the AWS Cloud. Which activities related to a Snowball Edge device are available to the company at no cost?

A. Use of the Snowball Edge appliance for a 10-day period

B. The transfer of data out of Amazon S3 and to the Snowball Edge appliance

**C.** The transfer of **data from the Snowball Edge appliance into Amazon S3**

D. Daily use of the Snowball Edge appliance after 10 days

## 2. A company has deployed applications on Amazon EC2 instances. The company needs to assess application vulnerabilities and must identify infrastructure deployments that do not meet best practices. Which AWS service can the company use to meet these requirements?

A. AWS Trusted Advisor

**B. Amazon Inspector**

C. AWS Config

D. Amazon GuardDuty

## 3. A company has a centralized group of users with large file storage requirements that have exceeded the space available on premises. The company wants to extend its file storage capabilities for this group while retaining the performance benefit of sharing content locally. What is the MOST operationally efficient AWS solution for this scenario?

A. Create an Amazon S3 bucket for each user. Mount each bucket by using an S3 file system mounting utility.

**B.** Configure and deploy an **AWS Storage Gateway file gateway**. Connect each user’s workstation to the file gateway.

C. Move each user’s working environment to Amazon WorkSpaces. Set up an Amazon WorkDocs account for each user.

D. Deploy an Amazon EC2 instance and attach an Amazon Elastic Block Store (Amazon EBS) Provisioned IOPS volume. Share the EBS volume directly with the users.

## 4. According to security best practices, how should an Amazon EC2 instance be given access to an Amazon S3 bucket?

A. Hard code an IAM user’s secret key and access key directly in the application, and upload the file.

B. Store the IAM user’s secret key and access key in a text file on the EC2 instance, read the keys, then upload the file.

**C.** Have the EC2 instance **assume a role** to obtain the privileges to upload the file.

D. Modify the S3 bucket policy so that any service can upload to it at any time.

## 5. Which option is a customer responsibility when using Amazon DynamoDB under the AWS Shared Responsibility Model?

A. Physical security of DynamoDB

B. Patching of DynamoDB

C. Access to DynamoDB tables

D. Encryption of data at rest in DynamoDB

## 6. Which option is a perspective that includes foundational capabilities of the AWS Cloud Adoption Framework (AWS CAF)?

A. Sustainability

B. Performance efficiency

C. Governance

D. Reliability

## 7. A company is running and managing its own Docker environment on Amazon EC2 instances. The company wants an alternative to help manage cluster size, scheduling, and environment maintenance. Which AWS service meets these requirements?

A. AWS Lambda

B. Amazon RDS

**C. AWS Fargate**

D. Amazon Athena

## 8. A company wants to run a NoSQL database on Amazon EC2 instances. Which task is the responsibility of AWS in this scenario?

A. Update the guest operating system of the EC2 instances.

B. Maintain high availability at the database layer.

**C. Patch the physical infrastructure that hosts the EC2 instances.**

D. Configure the security group firewall.

## 9. Which AWS services or tools can identify rightsizing opportunities for Amazon EC2 instances? (Choose two.)

A. AWS Cost Explorer

B. AWS Billing Conductor

C. Amazon CodeGuru

D. Amazon SageMaker

E. AWS Compute Optimizer

## 10. Which of the following are benefits of using AWS Trusted Advisor? (Choose two.)

A. Providing high-performance container orchestration

B. Creating and rotating encryption keys

C. Detecting underutilized resources to save costs

D. Improving security by proactively monitoring the AWS environment

E. Implementing enforced tagging across AWS resources

## 11. Which of the following is an advantage that users experience when they move on-premises workloads to the AWS Cloud?

A. Elimination of expenses for running and maintaining data centers

B. Price discounts that are identical to discounts from hardware providers

C. Distribution of all operational controls to AWS

D. Elimination of operational expenses

## 12. A company wants to manage deployed IT services and govern its infrastructure as code (IaC) templates. Which AWS service will meet this requirement?

A. AWS Resource Explorer

**B. AWS Service Catalog**

C. AWS Organizations

D. AWS Systems Manager

## 13. Which AWS service or tool helps users visualize, understand, and manage spending and usage over time?

A. AWS Organizations

B. AWS Pricing Calculator

**C. AWS Cost Explorer**

D. AWS Service Catalog

## 14. A company is using a central data platform to manage multiple types of data for its customers. The company wants to use AWS services to discover, transform, and visualize the data. Which combination of AWS services should the company use to meet these requirements? (Choose two.)

**A. AWS Glue**

B. Amazon Elastic File System (Amazon EFS)

C. Amazon Redshift

**D. Amazon QuickSight**

E. Amazon Quantum Ledger Database (Amazon QLDB)

## 15. A global company wants to migrate its third-party applications to the AWS Cloud. The company wants help from a global team of experts to complete the migration faster and more reliably in accordance with AWS internal best practices. Which AWS service or resource will meet these requirements?

A. AWS Support

**B. AWS Professional Services**

C. AWS Launch Wizard

D. AWS Managed Services (AMS)

## 16. An e-learning platform needs to run an application for 2 months each year. The application will be deployed on Amazon EC2 instances. Any application downtime during those 2 months must be avoided. Which EC2 purchasing option will meet these requirements MOST cost-effectively?

**A. Reserved Instances**

B. Dedicated Hosts

C. Spot Instances

D. On-Demand Instances

## 17. A developer wants to deploy an application quickly on AWS without manually creating the required resources. Which AWS service will meet these requirements?

A. Amazon EC2

**B. AWS Elastic Beanstalk**

C. AWS CodeBuild

D. Amazon Personalize

## 18. A company is storing sensitive customer data in an Amazon S3 bucket. The company wants to protect the data from accidental deletion or overwriting. Which S3 feature should the company use to meet these requirements?

A. S3 Lifecycle rules

B. S3 Versioning

C. S3 bucket policies

D. S3 server-side encryption

## 19. Which AWS service provides the ability to manage infrastructure as code?

A. AWS CodePipeline

B. AWS CodeDeploy

C. AWS Direct Connect

**D. AWS CloudFormation**

## 20. An online gaming company needs to choose a purchasing option to run its Amazon EC2 instances for 1 year. The web traffic is consistent, and any increases in traffic are predictable. The EC2 instances must be online and available without any disruption. Which EC2 instance purchasing option will meet these requirements MOST cost-effectively?

A. On-Demand Instances

B. Reserved Instances

C. Spot Instances

D. Spot Fleet

## 21. Which AWS service or feature allows a user to establish a dedicated network connection between a company’s on-premises data center and the AWS Cloud?

A. AWS Direct Connect

B. VPC peering

C. AWS VPN

D. Amazon Route 53

## 22. Which option is a physical location of the AWS global infrastructure?

A. AWS DataSync

B. AWS Region

C. Amazon Connect

D. AWS Organizations

## 23. A company wants to protect its AWS Cloud information, systems, and assets while performing risk assessment and mitigation tasks. Which pillar of the AWS Well-Architected Framework is supported by these goals?

A. Reliability

B. Security

C. Operational excellence

D. Performance efficiency

## 24. What is the purpose of having an internet gateway within a VPC?

A. To create a VPN connection to the VPC

B. To allow communication between the VPC and the internet

C. To impose bandwidth constraints on internet traffic

D. To load balance traffic from the internet across Amazon EC2 instances

## 25. A company is running a monolithic on-premises application that does not scale and is difficult to maintain. The company has a plan to migrate the application to AWS and divide the application into microservices. Which best practice of the AWS Well-Architected Framework is the company following with this plan?

A. Integrate functional testing as part of AWS deployment.

B. Use automation to deploy changes.

C. Deploy the application to multiple locations.

D. Implement loosely coupled dependencies.

## 26. A company has an AWS account. The company wants to audit its password and access key rotation details for compliance purposes. Which AWS service or tool will meet this requirement?

A. IAM Access Analyzer

B. AWS Artifact
 
C. IAM credential report

D. AWS Audit Manager

## 27. A company wants to receive a notification when a specific AWS cost threshold is reached. Which AWS services or tools can the company use to meet this requirement? (Choose two.)

A. Amazon Simple Queue Service (Amazon SQS)

B. AWS Budgets

C. Cost Explorer

D. Amazon CloudWatch

E. AWS Cost and Usage Report

## 28. Which AWS service or resource provides answers to the most frequently asked security-related questions that AWS receives from its users?

A. AWS Artifact

B. Amazon Connect

C. AWS Chatbot

D. AWS Knowledge Center

## 29. Which tasks are customer responsibilities, according to the AWS shared responsibility model? (Choose two.)

A. Configure the AWS provided security group firewall.

B. Classify company assets in the AWS Cloud.

C. Determine which Availability Zones to use for Amazon S3 buckets.

D. Patch or upgrade Amazon DynamoDB.

E. Select Amazon EC2 instances to run AWS Lambda on.

## 30. Which of the following are pillars of the AWS Well-Architected Framework? (Choose two.)

A. Availability

**B. Reliability**

C. Scalability

D. Responsive design

**E. Operational excellence**

## 31. Which AWS service or feature is used to send both text and email messages from distributed applications?

**A. Amazon Simple Notification Service (Amazon SNS)**

B. Amazon Simple Email Service (Amazon SES)

C. Amazon CloudWatch alerts

D. Amazon Simple Queue Service (Amazon SQS)

## 32. A user needs programmatic access to AWS resources through the AWS CLI or the AWS API. Which option will provide the user with the appropriate access?

A. Amazon Inspector

**B. Access keys**

C. SSH public keys

D. AWS Key Management Service (AWS KMS) keys

## 33. A company runs thousands of simultaneous simulations using AWS Batch. Each simulation is stateless, is fault tolerant, and runs for up to 3 hours. Which pricing model enables the company to optimize costs and meet these requirements?

A. Reserved Instances

B. Spot Instances

C. On-Demand Instances

D. Dedicated Instances

## 34. What does the concept of agility mean in AWS Cloud computing? (Choose two.)

A. The speed at which AWS resources are implemented

B. The speed at which AWS creates new AWS Regions

C. The ability to experiment quickly

D. The elimination of wasted capacity

E. The low cost of entry into cloud computing

## 35. A company needs to block SQL injection attacks. Which AWS service or feature can meet this requirement?

**A. AWS WAF**

B. AWS Shield

C. Network ACLs

D. Security groups

## 36. Which AWS service or feature identifies whether an Amazon S3 bucket or an IAM role has been shared with an external entity?

A. AWS Service Catalog

B. AWS Systems Manager

**C. AWS IAM Access Analyzer**

D. AWS Organizations

## 37. A cloud practitioner needs to obtain AWS compliance reports before migrating an environment to the AWS Cloud. How can these reports be generated?

A. Contact the AWS Compliance team.

B. Download the reports from AWS Artifact.

C. Open a case with AWS Support.

D. Generate the reports with Amazon Macie.

## 38. An ecommerce company has migrated its IT infrastructure from an on-premises data center to the AWS Cloud. Which cost is the company’s direct responsibility?

**A. Cost of application software licenses**

B. Cost of the hardware infrastructure on AWS

C. Cost of power for the AWS servers

D. Cost of physical security for the AWS data center

## 39. A company is setting up AWS Identity and Access Management (IAM) on an AWS account. Which recommendation complies with IAM security best practices?

A. Use the account root user access keys for administrative tasks.

B. Grant broad permissions so that all company employees can access the resources they need.

**C. Turn on multi-factor authentication (MFA) for added security during the login process.**

D. Avoid rotating credentials to prevent issues in production applications.

## 40. Elasticity in the AWS Cloud refers to which of the following? (Choose two.)

A. How quickly an Amazon EC2 instance can be restarted

B. The ability to rightsize resources as demand shifts

C. The maximum amount of RAM an Amazon EC2 instance can use

D. The pay-as-you-go billing model

E. How easily resources can be procured when they are needed

## 41. Which service enables customers to audit API calls in their AWS accounts?

A. AWS CloudTrail

B. AWS Trusted Advisor

C. Amazon Inspector

D. AWS X-Ray

## 42. What is a customer responsibility when using AWS Lambda according to the AWS shared responsibility model?

A. Managing the code within the Lambda function

B. Confirming that the hardware is working in the data center

C. Patching the operating system

D. Shutting down Lambda functions when they are no longer in use

## 43. A company has 5 TB of data stored in Amazon S3. The company plans to occasionally run queries on the data for analysis. Which AWS service should the company use to run these queries in the MOST cost-effective manner?

A. Amazon Redshift

B. Amazon Athena

C. Amazon Kinesis

D. Amazon RDS

## 44. Which AWS service can be used at no additional cost?

A. Amazon SageMaker
B. AWS Config
C. AWS Organizations
D. Amazon CloudWatch

## 45. Which AWS Cloud Adoption Framework (AWS CAF) capability belongs to the people perspective?

A. Data architecture

B. Event management

C. Cloud fluency

D. Strategic partnership

## 46. A company wants to make an upfront commitment for continued use of its production Amazon EC2 instances in exchange for a reduced overall cost. Which pricing options meet these requirements with the LOWEST cost? (Choose two.)

A. Spot Instances

B. On-Demand Instances

C. Reserved Instances

D. Savings Plans

E. Dedicated Hosts

## 47. A company wants to migrate its on-premises relational databases to the AWS Cloud. The company wants to use infrastructure as close to its current geographical location as possible. Which AWS service or resource should the company use to select its Amazon RDS deployment area?

A. Amazon Connect

B. AWS Wavelength

C. AWS Regions

D. AWS Direct Connect

## 48. A company is exploring the use of the AWS Cloud, and needs to create a cost estimate for a project before the infrastructure is provisioned. Which AWS service or feature can be used to estimate costs before deployment?

A. AWS Free Tier

B. AWS Pricing Calculator

C. AWS Billing and Cost Management

D. AWS Cost and Usage Report

## 49. A company is building an application that needs to deliver images and videos globally with minimal latency. Which approach can the company use to accomplish this in a cost effective manner?

A. Deliver the content through Amazon CloudFront.

B. Store the content on Amazon S3 and enable S3 cross-region replication.

C. Implement a VPN across multiple AWS Regions.

D. Deliver the content through AWS PrivateLink.

## 50. Which option is a benefit of the economies of scale based on the advantages of cloud computing?

A. The ability to trade variable expense for fixed expense

B. Increased speed and agility

C. Lower variable costs over fixed costs

D. Increased operational costs across data centers

## 51. Which of the following is a software development framework that a company can use to define cloud resources as code and provision the resources through AWS CloudFormation?

A. AWS CLI

B. AWS Developer Center

C. AWS Cloud Development Kit (AWS CDK)

D. AWS CodeStar

## 52. A company is developing an application that uses multiple AWS services. The application needs to use temporary, limited-privilege credentials for authentication with other AWS APIs. Which AWS service or feature should the company use to meet these authentication requirements?

A. Amazon API Gateway

B. IAM users

C. AWS Security Token Service (AWS STS)

D. IAM instance profiles

## 53. Which AWS service is a cloud security posture management (CSPM) service that aggregates alerts from various AWS services and partner products in a standardized format?

A. AWS Security Hub

B. AWS Trusted Advisor

C. Amazon EventBridge

D. Amazon GuardDuty

## 54. Which AWS service is always provided at no charge?

A. Amazon S3

B. AWS Identity and Access Management (IAM)

C. Elastic Load Balancers

D. AWS WAF

## 55. To reduce costs, a company is planning to migrate a NoSQL database to AWS. Which AWS service is fully managed and can automatically scale throughput capacity to meet database workload demands?

A. Amazon Redshift

B. Amazon Aurora

C. Amazon DynamoDB

D. Amazon RDS

## 56. A company is using Amazon DynamoDB. Which task is the company’s responsibility, according to the AWS shared responsibility model?

A. Patch the operating system.
B. Provision hosts.
C. Manage database access permissions.
D. Secure the operating system.

## 57. A company has a test AWS environment. A company is planning on testing an application within AWS. The application testing can be interrupted and does not need to run continuously. Which Amazon EC2 purchasing option will meet these requirements MOST cost-effectively?

A. On-Demand Instances

B. Dedicated Instances

C. Spot Instances

D. Reserved Instances

## 58. Which AWS service gives users the ability to discover and protect sensitive data that is stored in Amazon S3 buckets?

A. Amazon Macie

B. Amazon Detective

C. Amazon GuardDuty

D. AWS IAM Access Analyzer

## 59. Which of the following services can be used to block network traffic to an instance? (Choose two.)

A. Security groups

B. Amazon Virtual Private Cloud (Amazon VPC) flow logs

C. Network ACLs

D. Amazon CloudWatch

E. AWS CloudTrail

## 60. Which AWS service can identify when an Amazon EC2 instance was terminated?

A. AWS Identity and Access Management (IAM)

B. AWS CloudTrail

C. AWS Compute Optimizer

D. Amazon EventBridge

## 61. Which of the following is a fully managed MySQL-compatible database?

A. Amazon S3

B. Amazon DynamoDB

C. Amazon Redshift

**D. Amazon Aurora**

## 62. Which AWS service supports a hybrid architecture that gives users the ability to extend AWS infrastructure, AWS services, APIs, and tools to data centers, co-location environments, or on-premises facilities?

A. AWS Snowmobile

B. AWS Local Zones

C. AWS Outposts

D. AWS Fargate

## 63. Which AWS service can run a managed PostgreSQL database that provides online transaction processing (OLTP)?

A. Amazon DynamoDB

B. Amazon Athena

C. Amazon RDS

D. Amazon EMR

## 64. A company wants to provide managed Windows virtual desktops and applications to its remote employees over secure network connections. Which AWS services can the company use to meet these requirements? (Choose two.)

A. Amazon Connect

B. Amazon AppStream 2.0

C. Amazon WorkSpaces

D. AWS Site-to-Site VPN

E. Amazon Elastic Container Service (Amazon ECS)

## 65. A company wants to monitor for misconfigured security groups that are allowing unrestricted access to specific ports. Which AWS service will meet this requirement?

**A. AWS Trusted Advisor**

B. Amazon CloudWatch

C. Amazon GuardDuty

D. AWS Health Dashboard

## 66. Which AWS service is a key-value database that provides sub-millisecond latency on a large scale?

**A. Amazon DynamoDB**

B. Amazon Aurora

C. Amazon DocumentDB (with MongoDB compatibility)

D. Amazon Neptune

## 67. A company is deploying a machine learning (ML) research project that will require a lot of compute power over several months. The ML processing jobs do not need to run at specific times. Which Amazon EC2 instance purchasing option will meet these requirements at the lowest cost?

A. On-Demand Instances

B. Spot Instances

C. Reserved Instances

D. Dedicated Instances

## 68. Which AWS services or features provide disaster recovery solutions for Amazon EC2 instances? (Choose two.)

A. EC2 Reserved Instances

**B. EC2 Amazon Machine Images (AMIs)**

**C. Amazon Elastic Block Store (Amazon EBS) snapshots**

D. AWS Shield

E. Amazon GuardDuty

## 69. Which AWS service provides command line access to AWS tools and resources directly from a web browser?

A. AWS CloudHSM

**B. AWS CloudShell**

C. Amazon WorkSpaces

D. AWS Cloud Map

## 70. A network engineer needs to build a hybrid cloud architecture connecting on-premises networks to the AWS Cloud using AWS Direct Connect. The company has a few VPCs in a single AWS Region and expects to increase the number of VPCs to hundreds over time. Which AWS service or feature should the engineer use to simplify and scale this connectivity as the VPCs increase in number?

A. VPC endpoints

B. AWS Transit Gateway

C. Amazon Route 53

D. AWS Secrets Manager

## 71. A company wants to assess its operational readiness. It also wants to identify and mitigate any operational risks ahead of a new product launch. Which AWS Support plan offers guidance and support for this kind of event at no additional charge?

A. AWS Business Support

B. AWS Basic Support

C. AWS Developer Support

**D. AWS Enterprise Support**

## 72. A company wants to establish a schedule for rotating database user credentials. Which AWS service will support this requirement with the LEAST amount of operational overhead?

A. AWS Systems Manager
**B. AWS Secrets Manager**
C. AWS License Manager
D. AWS Managed Services

## 73. Which AWS service or feature can be used to create a private connection between an on-premises workload and an AWS Cloud workload?

A. Amazon Route 53

B. Amazon Macie

**C. AWS Direct Connect**

D. AWS PrivateLink

## 74. Which AWS service is used to provide encryption for Amazon EBS?

A. AWS Certificate Manager

B. AWS Systems Manager

**C. AWS KMS**

D. AWS Config

## 75. A company wants to manage its AWS Cloud resources through a web interface. Which AWS service will meet this requirement?

**A. AWS Management Console**

B. AWS CLI

C. AWS SDK

D. AWS Cloud9

## 76. Which of the following are advantages of the AWS Cloud? (Choose two.)

A. Trade variable expenses for capital expenses

**B. High economies of scale**

**C. Launch globally in minutes**

D. Focus on managing hardware infrastructure

E. Overprovision to ensure capacity

## 77. Which AWS Cloud benefit is shown by an architecture’s ability to withstand failures with minimal downtime?

A. Agility

B. Elasticity

C. Scalability

D. High availability

## 78. A developer needs to maintain a development environment infrastructure and a production environment infrastructure in a repeatable fashion. Which AWS service should the developer use to meet these requirements?

A. AWS Ground Station

B. AWS Shield

C. AWS IoT Device Defender

D. AWS CloudFormation

## 79. Which task is the customer’s responsibility, according to the AWS shared responsibility model?

A. Maintain the security of the AWS Cloud.

B. Configure firewalls and networks.

C. Patch the operating system of Amazon RDS instances.

D. Implement physical and environmental controls.

## 80. Which AWS service helps deliver highly available applications with fast failover for multi-Region and Multi-AZ architectures?

A. AWS WAF

B. AWS Global Accelerator

C. AWS Shield

D. AWS Direct Connect

## 81. A company has a set of ecommerce applications. The applications need to be able to send messages to each other. Which AWS service meets this requirement?

A. AWS Auto Scaling

B. Elastic Load Balancing

**C. Amazon Simple Queue Service (Amazon SQS)**

D. Amazon Kinesis Data Streams

## 82. What are the benefits of consolidated billing for AWS Cloud services? (Choose two.)

**A. Volume discounts**

B. A minimal additional fee for use

**C. One bill for multiple accounts**

D. Installment payment options

E. Custom cost and usage budget creation

## 83. A user wants to review all Amazon S3 buckets with ACLs and S3 bucket policies in the S3 console. Which AWS service or resource will meet this requirement?

A. S3 Multi-Region Access Points

B. S3 Storage Lens

C. AWS IAM Identity Center (AWS Single Sign-On)

D. Access Analyzer for S3

## 84. What is the best resource for a user to find compliance-related information and reports about AWS?

A. AWS Artifact

B. AWS Marketplace

C. Amazon Inspector

D. AWS Support

## 85. Which AWS service enables companies to deploy an application close to end users?

A. Amazon CloudFront

B. AWS Auto Scaling

C. AWS AppSync

D. Amazon Route 53

## 86. Which AWS service or feature improves network performance by sending traffic through the AWS worldwide network infrastructure?

A. Route table

B. AWS Transit Gateway

C. AWS Global Accelerator

D. Amazon VPC

## 87. Which AWS service provides highly durable object storage?

A. Amazon S3

B. Amazon Elastic File System (Amazon EFS)

C. Amazon Elastic Block Store (Amazon EBS)

D. Amazon FSx

## 88. Which responsibility belongs to AWS when a company hosts its databases on Amazon EC2 instances?

A. Database backups

B. Database software patches

C. Operating system patches

D. Operating system installations

## 89. Which of the following are advantages of moving to the AWS Cloud? (Choose two.)

A. The ability to turn over the responsibility for all security to AWS.

B. The ability to use the pay-as-you-go model.

C. The ability to have full control over the physical infrastructure.

D. No longer having to guess what capacity will be required.

E. No longer worrying about users access controls.

## 90. Which AWS service is a hybrid cloud storage service that provides on-premises users access to virtually unlimited cloud storage?

A. AWS DataSync

B. Amazon S3 Glacier

**C. AWS Storage Gateway**

D. Amazon Elastic Block Store (Amazon EBS)

## 91. A company plans to migrate to AWS and wants to create cost estimates for its AWS use cases. Which AWS service or tool can the company use to meet these requirements?

A. AWS Pricing Calculator

B. Amazon CloudWatch

C. AWS Cost Explorer

D. AWS Budgets

## 92. Which tool should a developer use to integrate AWS service features directly into an application?

**A. AWS Software Development Kit**

B. AWS CodeDeploy

C. AWS Lambda

D. AWS Batch

## 93. Which of the following is a recommended design principle of the AWS Well-Architected Framework?

A. Reduce downtime by making infrastructure changes infrequently and in large increments.

B. Invest the time to configure infrastructure manually.

**C. Learn to improve from operational failures.**

D. Use monolithic application design for centralization.

## 94. Using AWS Identity and Access Management (IAM) to grant access only to the resources needed to perform a task is a concept known as:

A. restricted access.

B. as-needed access.

C. least privilege access.

D. token access.

## 95. Which AWS service or tool can be used to set up a firewall to control traffic going into and coming out of an Amazon VPC subnet?

A. Security group

B. AWS WAF

C. AWS Firewall Manager

D. Network ACL

## 96. A company wants to operate a data warehouse to analyze data without managing the data warehouse infrastructure. Which AWS service will meet this requirement?

A. Amazon Aurora

B. Amazon Redshift Serverless

C. AWS Lambda

D. Amazon RDS

## 97. How does AWS Cloud computing help businesses reduce costs? (Choose two.)

A. AWS charges the same prices for services in every AWS Region.

B. AWS enables capacity to be adjusted on demand.

C. AWS offers discounts for Amazon EC2 instances that remain idle for more than 1 week.

D. AWS does not charge for data sent from the AWS Cloud to the internet.

E. AWS eliminates many of the costs of building and maintaining on-premises data centers.

## 98. A company wants to grant users in one AWS account access to resources in another AWS account. The users do not currently have permission to access the resources. Which AWS service will meet this requirement?

A. IAM group

B. IAM role

C. IAM tag

D. IAM Access Analyzer

## 99. Which task is the responsibility of AWS when using AWS services?

A. Management of IAM user permissions

B. Creation of security group rules for outbound access

**C. Maintenance of physical and environmental controls**

D. Application of Amazon EC2 operating system patches

## 100. A company wants to automate infrastructure deployment by using infrastructure as code (IaC). The company wants to scale production stacks so the stacks can be deployed in multiple AWS Regions. Which AWS service will meet these requirements?

A. Amazon CloudWatch

B. AWS Config

C. AWS Trusted Advisor

**D. AWS CloudFormation**

101. Which option is an AWS Cloud Adoption Framework (AWS CAF) platform perspective capability?

A. Data architecture

B. Data protection

C. Data governance

D. Data science

## 102. A company is running a workload in the AWS Cloud. Which AWS best practice ensures the MOST cost-effective architecture for the workload?

A. Loose coupling

B. Rightsizing

C. Caching

D. Redundancy

## 103. A company is using a third-party service to back up 10 TB of data to a tape library. The on-premises backup server is running out of space. The company wants to use AWS services for the backups without changing its existing backup workflows. Which AWS service should the company use to meet these requirements?

A. Amazon Elastic Block Store (Amazon EBS)

B. AWS Storage Gateway

C. Amazon Elastic Container Service (Amazon ECS)

D. AWS Lambda

## 104. Which AWS tool gives users the ability to plan their service usage, service costs, and instance reservations, and also allows them to set custom alerts when their costs or usage exceed established thresholds?

A. Cost Explorer

B. AWS Budgets

C. AWS Cost and Usage Report

D. Reserved Instance reporting

## 105. Which tasks are the customer’s responsibility, according to the AWS shared responsibility model? (Choose two.)

A. Establish the global infrastructure.

B. Perform client-side data encryption.

C. Configure IAM credentials.

D. Secure edge locations.

E. Patch Amazon RDS DB instances.

## 106. A developer has been hired by a large company and needs AWS credentials. Which are security best practices that should be followed? (Choose two.)

A. Grant the developer access to only the AWS resources needed to perform the job.

B. Share the AWS account root user credentials with the developer.

C. Add the developer to the administrator’s group in AWS IAM.

D. Configure a password policy that ensures the developer’s password cannot be changed.

E. Ensure the account password policy requires a minimum length.

## 107. A company has multiple AWS accounts that include compute workloads that cannot be interrupted. The company wants to obtain billing discounts that are based on the company’s use of AWS services. Which AWS feature or purchasing option will meet these requirements?

A. Resource tagging

B. Consolidated billing

C. Pay-as-you-go pricing

D. Spot Instances

108. A user wants to allow applications running on an Amazon EC2 instance to make calls to other AWS services. The access granted must be secure. Which AWS service or feature should be used?

A. Security groups

B. AWS Firewall Manager

C. IAM roles

D. IAM user SSH keys

## 109. A company wants a fully managed Windows file server for its Windows-based applications. Which AWS service will meet this requirement?

A. Amazon FSx

B. Amazon Elastic Kubernetes Service (Amazon EKS)

C. Amazon Elastic Container Service (Amazon ECS)

D. Amazon EMR

## 110. A company wants to migrate its NFS on-premises workload to AWS. Which AWS Storage Gateway type should the company use to meet this requirement?

A. Tape Gateway

B. Volume Gateway

C. Amazon FSx File Gateway

**D. Amazon S3 File Gateway**

## 111. A company needs to track the activity in its AWS accounts, and needs to know when an API call is made against its AWS resources. Which AWS tool or service can be used to meet these requirements?

A. Amazon CloudWatch

B. Amazon Inspector

**C. AWS CloudTrail**

D. AWS IAM

## 112. A company has an uninterruptible application that runs on Amazon EC2 instances. The application constantly processes a backlog of files in an Amazon Simple Queue Service (Amazon SQS) queue. This usage is expected to continue to grow for years. What is the MOST cost-effective EC2 instance purchasing model to meet these requirements?

A. Spot Instances

B. On-Demand Instances

C. Savings Plans

D. Dedicated Hosts

## 113. A company wants an AWS service to provide product recommendations based on its customer data. Which AWS service will meet this requirement?

A. Amazon Polly

B. Amazon Personalize

C. Amazon Comprehend

D. Amazon Rekognition

## 114. A company is planning its migration to the AWS Cloud. The company is identifying its capability gaps by using the AWS Cloud Adoption Framework (AWS CAF) perspectives. Which phase of the cloud transformation journey includes these identification activities?

A. Envision

B. Align

C. Scale

D. Launch

## 115. A social media company wants to protect its web application from common web exploits such as SQL injections and cross-site scripting. Which AWS service will meet these requirements?

A. Amazon Inspector

B. AWS WAF

C. Amazon GuardDuty

D. Amazon CloudWatch

## 116. Which fully managed AWS service assists with the creation, testing, and management of custom Amazon EC2 images?

A. EC2 Image Builder
B. Amazon Machine Image (AMI)
C. AWS Launch Wizard
D. AWS Elastic Beanstalk

## 117. A company wants an automated process to continuously scan its Amazon EC2 instances for software vulnerabilities. Which AWS service will meet these requirements?

A. Amazon GuardDuty

B. Amazon Inspector

C. Amazon Detective

D. Amazon Cognito

## 118. A company needs to perform data processing once a week that typically takes about 5 hours to complete. Which AWS service should the company use for this workload?

A. AWS Lambda

B. Amazon EC2

C. AWS CodeDeploy

D. AWS Wavelength

## 119. Which AWS service or feature provides log information of the inbound and outbound traffic on network interfaces in a VPC?

A. Amazon CloudWatch Logs

B. AWS CloudTrail

**C. VPC Flow Logs**

D. AWS Identity and Access Management (IAM)

## 120. A company wants to design a centralized storage system to manage the configuration data and passwords for its critical business applications. Which AWS service or capability will meet these requirements MOST cost-effectively?

A. AWS Systems Manager Parameter Store

B. AWS Secrets Manager

C. AWS Config

D. Amazon S3

## 121. A company plans to deploy containers on AWS. The company wants full control of the compute resources that host the containers. Which AWS service will meet these requirements?

A. Amazon Elastic Kubernetes Service (Amazon EKS)

B. AWS Fargate

**C. Amazon EC2**

D. Amazon Elastic Container Service (Amazon ECS)

## 122. Which AWS service or feature allows users to create new AWS accounts, group multiple accounts to organize workflows, and apply policies to groups of accounts?

A. AWS Identity and Access Management (IAM)

B. AWS Trusted Advisor

C. AWS CloudFormation

**D. AWS Organizations**

## 123. A company wants to store and retrieve files in Amazon S3 for its existing on-premises applications by using industry-standard file system protocols. Which AWS service will meet these requirements?

A. AWS DataSync

B. AWS Snowball Edge

**C. Amazon S3 File Gateway**

D. AWS Transfer Family

## 124. A company wants to block SQL injection attacks. Which AWS service or feature should the company use to meet this requirement?

**A. AWS WAF**

B. Network ACLs

C. Security groups

D. AWS Certificate Manager (ACM)

## 125. A company wants a unified tool to provide a consistent method to interact with AWS services. Which AWS service or tool will meet this requirement?

**A. AWS CLI**

B. Amazon Elastic Container Service (Amazon ECS)

C. AWS Cloud9

D. AWS Virtual Private Network (AWS VPN)

126. A company needs to evaluate its AWS environment and provide best practice recommendations in five categories: cost, performance, service limits, fault tolerance and security. Which AWS service can the company use to meet these requirements?

A. AWS Shield
B. AWS WAF
C. AWS Trusted Advisor
D. AWS Service Catalog

127. Which perspective in the AWS Cloud Adoption Framework (AWS CAF) includes capabilities for configuration management and patch management?

A. Platform
(X) B. Operations
C. Security
D. Governance

128. A company has a compute workload that is steady, predictable, and uninterruptible.
Which Amazon EC2 instance purchasing options meet these requirements MOST cost-effectively? (Choose two.)

A. On-Demand Instances
B. Reserved Instances
C. Spot Instances
D. Saving Plans
E. Dedicated Hosts

129. Which Amazon EC2 pricing model is the MOST cost efficient for an uninterruptible workload that runs once a year for 24 hours?

A. On-Demand Instances
B. Reserved Instances
C. Spot Instances
D. Dedicated Instances

130. Which option is a shared responsibility between AWS and its customers under the AWS shared responsibility model?

A. Configuration of Amazon EC2 instance operating systems
B. Application file system server-side encryption
C. Patch management
D. Security of the physical infrastructure

131. A company wants to migrate its on-premises workloads to the AWS Cloud. The company wants to separate workloads for chargeback to different departments.
Which AWS services or features will meet these requirements? (Choose two.)

A. Placement groups
(X) B. Consolidated billing
C. Edge locations
D. AWS Config
(X) E. Multiple AWS accounts

132. Which task is a responsibility of AWS, according to the AWS shared responsibility model?

A. Enable client-side encryption for objects that are stored in Amazon S3.
B. Configure IAM security policies to comply with the principle of least privilege.
C. Patch the guest operating system on an Amazon EC2 instance.
(X) D. Apply updates to the Nitro Hypervisor.

133. Which option is a benefit of using AWS for cloud computing?

A. Trade variable expense for fixed expense
(X) B. Pay-as-you-go pricing
C. Decreased speed and agility
D. Spending money running and maintaining data centers

134. Which option is an AWS Cloud Adoption Framework (AWS CAF) business perspective capability?

A. Culture evolution
B. Event management
C. Data monetization
D. Platform architecture

135. A company is assessing its AWS Business Support plan to determine if the plan still meets the company’s needs. The company is considering switching to AWS Enterprise Support.
Which additional benefit will the company receive with AWS Enterprise Support?

A. A full set of AWS Trusted Advisor checks
B. Phone, email, and chat access to cloud support engineers 24 hours a day, 7 days a week
(X) C. A designated technical account manager (TAM) to assist in monitoring and optimization
D. A consultative review and architecture guidance for the company’s applications

136. Which pricing model will interrupt a running Amazon EC2 instance if capacity becomes temporarily unavailable?

A. On-Demand Instances
B. Standard Reserved Instances
(X) C. Spot Instances
D. Convertible Reserved Instances

137. Which options are AWS Cloud Adoption Framework (AWS CAF) security perspective capabilities? (Choose two.)

A. Observability
B. Incident and problem management
C. Incident response
D. Infrastructure protection
E. Availability and continuity

138. A company wants to run its workload on Amazon EC2 instances for more than 1 year. This workload will run continuously.

Which option offers a discounted hourly rate compared to the hourly rate of On-Demand Instances?

A. AWS Graviton processor
B. Dedicated Hosts
C. EC2 Instance Savings Plans
D. Amazon EC2 Auto Scaling instances

139. Which characteristic of the AWS Cloud helps users eliminate underutilized CPU capacity?

A. Agility
B. Elasticity
C. Reliability
D. Durability

## 140. Which AWS services can a company use to achieve a loosely coupled architecture? (Choose two.)

A. Amazon WorkSpaces

B. Amazon Simple Queue Service (Amazon SQS)

C. Amazon Connect

D. AWS Trusted Advisor

E. AWS Step Functions

## 141. Which AWS Cloud service can send alerts to customers if custom spending thresholds are exceeded?

**A. AWS Budgets**

B. AWS Cost Explorer

C. AWS Cost Allocation Tags

D. AWS Organizations

## 142. A company plans to migrate to the AWS Cloud. The company wants to use the AWS Cloud Adoption Framework (AWS CAF) to define and track business outcomes as part of its cloud transformation journey. Which AWS CAF governance perspective capability will meet these requirements?

A. Benefits management

B. Risk management

C. Application portfolio management

D. Cloud financial management

## 143. A company needs to quickly and securely move files over long distances between its client and an Amazon S3 bucket. Which S3 feature will meet this requirement?

A. S3 Versioning

**B. S3 Transfer Acceleration**

C. S3ACLs

D. S3 Intelligent-Tiering

## 144. A company needs to continuously run an experimental workload on an Amazon EC2 instance and stop the instance after 12 hours. Which instance purchasing option will meet this requirement MOST cost-effectively?

**A. On-Demand Instances**

B. Reserved Instances

C. Spot Instances

D. Dedicated Instances

## 145. Which cloud transformation journey phase of the AWS Cloud Adoption Framework (AWS CAF) focuses on demonstrating how the cloud helps accelerate business outcomes?

A. Scale

**B. Envision**

C. Align

D. Launch

## 146. Which option is a customer responsibility under the AWS shared responsibility model?

A. Maintenance of underlying hardware of Amazon EC2 instances

**B. Application data security**

C. Physical security of data centers

D. Maintenance of VPC components

## 147. A company wants its Amazon EC2 instances to operate in a highly available environment, even if there is a natural disaster in a particular geographic area. Which approach will achieve this goal?

A. Use EC2 instances in multiple AWS Regions.

B. Use EC2 instances in multiple Amazon CloudFront locations.

C. Use EC2 instances in multiple edge locations.

D. Use EC2 instances in AWS Local Zones.

## 148. A company wants to modernize and convert a monolithic application into microservices. The company wants to move the application to AWS. Which migration strategy should the company use?

A. Rehost

B. Replatform

C. Repurchase

**D. Refactor**

## 149. A systems administrator created a new IAM user for a developer and assigned the user an access key instead of a user name and password. What is the access key used for?

A. To access the AWS account as the AWS account root user

B. To access the AWS account through the AWS Management Console

**C. To access the AWS account through a CLI**

D. To access all of a company’s AWS accounts

## 150. Which option is an environment that consists of one or more data centers?

A. Amazon CloudFront

**B. Availability Zone**

C. VPC

D. AWS Outposts

## 151. A company is moving an on-premises data center to the AWS Cloud. The company must migrate 50 petabytes of file storage data to AWS with the least possible operational overhead. Which AWS service or resource should the company use to meet these requirements?

**A. AWS Snowmobile**

B. AWS Snowball Edge

C. AWS Data Exchange

D. AWS Database Migration Service (AWS DMS)

## 152. A company has an application with robust hardware requirements. The application must be accessed by students who are using lightweight, low-cost laptops. Which AWS service will help the company deploy the application without investing in backend infrastructure or high-end client hardware?

**A. Amazon AppStream 2.0**

B. AWS AppSync

C. Amazon WorkLink

D. AWS Elastic Beanstalk

## 153. A company wants to query its server logs to gain insights about its customers’ experiences. Which AWS service will store this data MOST cost-effectively?

A. Amazon Aurora

B. Amazon Elastic File System (Amazon EFS)

C. Amazon Elastic Block Store (Amazon EBS)

**D. Amazon S3**

## 154. Which of the following is a recommended design principle for AWS Cloud architecture?

A. Design tightly coupled components.

B. Build a single application component that can handle all the application functionality.

C. Make large changes on fewer iterations to reduce chances of failure.

D. Avoid monolithic architecture by segmenting workloads.

## 155. Which AWS service helps users audit API activity across their AWS account?

A. AWS CloudTrail

B. Amazon Inspector

C. AWS WAF

D. AWS Config

## 156. Which task is a customer’s responsibility, according to the AWS shared responsibility model?

**A. Management of the guest operating systems**

B. Maintenance of the configuration of infrastructure devices

C. Management of the host operating systems and virtualization

D. Maintenance of the software that powers Availability Zones

## 157. A company wants to automatically add and remove Amazon EC2 instances. The company wants the EC2 instances to adjust to varying workloads dynamically. Which service or feature will meet these requirements?

A. Amazon DynamoDB

B. Amazon EC2 Spot Instances

C. AWS Snow Family

D. Amazon EC2 Auto Scaling 

## 158. A user wants to securely automate the management and rotation of credentials that are shared between applications, while spending the least amount of time on managing tasks. Which AWS service or feature can be used to accomplish this?

A. AWS CloudHSM

B. AWS Key Management Service (AWS KMS)

C. AWS Secrets Manager

D. Server-side encryption

## 159. Which security service automatically recognizes and classifies sensitive data or intellectual property on AWS?

A. Amazon GuardDuty

**B. Amazon Macie**

C. Amazon Inspector

D. AWS Shield

## 160. Which actions are best practices for an AWS account root user? (Choose two.)

A. Share root user credentials with team members.

B. Create multiple root users for the account, separated by environment.

**C. Enable multi-factor authentication (MFA) on the root user.**

**D. Create an IAM user with administrator privileges for daily administrative tasks, instead of using the root user.**

E. Use programmatic access instead of the root user and password.

## 161. A company is running a critical workload on an Amazon RDS DB instance. The company needs the DB instance to be highly available with a recovery time of less than 5 minutes. Which solution will meet these requirements?

A. Create a read replica of the DB instance.

B. Create a template of the DB instance by using AWS CloudFormation.

C. Take frequent snapshots of the DB instance. Store the snapshots in Amazon S3.

D. Modify the DB instance to be a Multi-AZ deployment.

## 162. A company plans to migrate its application to AWS and run the application on Amazon EC2 instances. The application will have continuous usage for 1 year. Which EC2 instance purchasing option will meet these requirements MOST cost-effectively?

**A. Reserved Instances**

B. Spot Instances

C. On-Demand Instances

D. Dedicated Hosts

## 163. A company needs to transfer data between an Amazon S3 bucket and an on-premises application. Who is responsible for the security of this data, according to the AWS shared responsibility model?

**A. The company**

B. AWS

C. Firewall vendor

D. AWS Marketplace partner

## 164. Which pillar of the AWS Well-Architected Framework refers to the ability of a system to recover from infrastructure or service disruptions and dynamically acquire computing resources to meet demand?

A. Security

**B. Reliability**

C. Performance efficiency

D. Cost optimization

## 165. A company wants to identify Amazon S3 buckets that are shared with another AWS account. Which AWS service or feature will meet these requirements?

A. AWS Lake Formation

B. IAM credential report

C. Amazon CloudWatch

**D. IAM Access Analyzer**

## 166. Which AWS service gives users the ability to build interactive business intelligence dashboards that include machine learning insights?

A. Amazon Athena

B. Amazon Kendra

**C. Amazon QuickSight**

D. Amazon Redshift

## 167. Which of the following is an AWS value proposition that describes a user’s ability to scale infrastructure based on demand?

A. Speed of innovation

**B. Resource elasticity**

C. Decoupled architecture

D. Global deployment

## 168. Which action is a security best practice for access to sensitive data that is stored in an Amazon S3 bucket?

A. Enable S3 Cross-Region Replication (CRR) on the S3 bucket.

B. Use IAM roles for applications that require access to the S3 bucket.

C. Configure AWS WAF to prevent unauthorized access to the S3 bucket.

D. Configure Amazon GuardDuty to prevent unauthorized access to the S3 bucket.

## 169. A company wants to know more about the benefits offered by cloud computing. The company wants to understand the operational advantage of agility. How does AWS provide agility for users?

A. The ability the ensure high availability by deploying workloads to multiple regions

B. A pay-as-you-go model for many services and resources

C. The ability to transfer infrastructure management to the AWS Cloud

D. The ability to provision and deprovision resources quickly with minimal effort

## 170. A company needs a central user portal so that users can log in to third-party business applications that support Security Assertion Markup Language (SAML) 2.0.Which AWS service will meet this requirement?

A. AWS Identity and Access Management (IAM)

B. Amazon Cognito

C. AWS IAM Identity Center (AWS Single Sign-On)

D. AWS CLI

## 171. Which AWS service should users use to learn about AWS service availability and operations?

A. Amazon EventBridge

B. AWS Service Catalog

C. AWS Control Tower

**D. AWS Health Dashboard**

## 172. Which AWS service or tool can be used to capture information about inbound and outbound traffic in an Amazon VPC?

**A. VPC Flow Logs**

B. Amazon Inspector

C. VPC endpoint services

D. NAT gateway

## 173. What is the customer ALWAYS responsible for managing, according to the AWS shared responsibility model?

A. Software licenses

B. Networking

C. Customer data

D. Encryption keys

## 174. Which AWS service can be used to retrieve compliance reports on demand?

A. AWS Secrets Manager

**B. AWS Artifact**

C. AWS Security Hub

D. AWS Certificate Manager

## 175. Which AWS service enables users to check for vulnerabilities on Amazon EC2 instances by using predefined assessment templates?

A. AWS WAF

B. AWS Trusted Advisor

(X)C. Amazon Inspector

D. AWS Shield

## 176. A company plans to migrate to the AWS Cloud. The company is gathering information about its on-premises infrastructure and requires information such as the hostname, IP address, and MAC address. Which AWS service will meet these requirements?

A. AWS DataSync

B. AWS Application Migration Service

**C. AWS Application Discovery Service**

D. AWS Database Migration Service (AWS DMS)

## 177. Which action will help increase security in the AWS Cloud?

A. Enable programmatic access for all IAM users.

B. Use IAM users instead of IAM roles to delegate permissions.

**C. Rotate access keys on a reoccurring basis.**

D. Use inline policies instead of customer managed policies.

## 178. A company is planning to migrate its application to the AWS Cloud. Which AWS tool or set of resources should the company use to analyze and assess its readiness for migration?

**A. AWS Cloud Adoption Framework (AWS CAF)**

B. AWS Pricing Calculator

C. AWS Well-Architected Framework

D. AWS Budgets

## 179. Which of the following describes some of the core functionality of Amazon S3?

A. Amazon S3 is a high-performance block storage service that is designed for use with Amazon EC2.

**B. Amazon S3 is an object storage service that provides high-level performance, security, scalability, and data availability.**

C. Amazon S3 is a fully managed, highly reliable, and scalable file storage system that is accessible over the industry-standard SMB protocol.

D. Amazon S3 is a scalable, fully managed elastic NFS for use with AWS Cloud services and on-premises resources.

## 180. Which AWS benefit is demonstrated by on-demand technology services that enable companies to replace upfront fixed expenses with variable expenses?

A. High availability

B. Economies of scale

**C. Pay-as-you-go pricing**

D. Global reach

181. Which AWS services or features enable users to connect on-premises networks to a VPC? (Choose two.)

**A. AWS VPN**

B. Elastic Load Balancing

**C. AWS Direct Connect**

D. VPC peering

E. Amazon CloudFront

## 182. A user needs to quickly deploy a nonrelational database on AWS. The user does not want to manage the underlying hardware or the database software. Which AWS service can be used to accomplish this?

A. Amazon RDS

**B. Amazon DynamoDB**

C. Amazon Aurora

D. Amazon Redshift

## 183. Which actions are examples of a company’s effort to rightsize its AWS resources to control cloud costs? (Choose two.)

**A. Switch from Amazon RDS to Amazon DynamoDB to accommodate NoSQL datasets.**

B. Base the selection of Amazon EC2 instance types on past utilization patterns.

**C. Use Amazon S3 Lifecycle policies to move objects that users access infrequently to lower-cost storage tiers.**

D. Use Multi-AZ deployments for Amazon RDS.

E. Replace existing Amazon EC2 instances with AWS Elastic Beanstalk.

## 184. Which AWS service or feature can a company use to apply security rules to specific Amazon EC2 instances?

A. Network ACLs

**B. Security groups**

C. AWS Trusted Advisor

D. AWS WAF

## 185. Which design principles support the reliability pillar of the AWS Well-Architected Framework? (Choose two.)

A. Perform operations as code.

B. Enable traceability.

**C. Automatically scale to meet demand.**

D. Deploy resources globally to improve response time.

**E. Automatically recover from failure.**

## 186. A company that uses AWS needs to transfer 2 TB of data. Which type of transfer of that data would result in no cost for the company?

A. Inbound data transfer from the internet

B. Outbound data transfer to the internet

C. Data transfer between AWS Regions

D. Data transfer between Availability Zones

## 187. A company wants to create templates that the company can reuse to deploy multiple AWS resources. Which AWS service or feature can the company use to meet this requirement?

A. AWS Marketplace

B. Amazon Machine Image (AMI)

**C. AWS CloudFormation**

D. AWS OpsWorks

## 188. A company is building an application that requires the ability to send, store, and receive messages between application components. The company has another requirement to process messages in first-in, first-out (FIFO) order.Which AWS service should the company use?

A. AWS Step Functions

B. Amazon Simple Notification Service (Amazon SNS)

C. Amazon Kinesis Data Streams

**D. Amazon Simple Queue Service (Amazon SQS)**

## 189. Which AWS service or feature is a browser-based, pre-authenticated service that can be launched directly from the AWS Management Console?

A. AWS API

B. AWS Lightsail

C. AWS Cloud9

**D. AWS CloudShell**

190. A company wants to migrate its database to a managed AWS service that is compatible with PostgreSQL.
Which AWS services will meet these requirements? (Choose two.)

A. Amazon Athena
(X)B. Amazon RDS
C. Amazon EC2
D. Amazon DynamoDB
(X)E. Amazon Aurora

191. A company has a fleet of cargo ships. The cargo ships have sensors that collect data at sea, where there is intermittent or no internet connectivity. The company needs to collect, format, and process the data at sea and move the data to AWS later. Which AWS service should the company use to meet these requirements?

A. AWS IoT Core
B. Amazon Lightsail
C. AWS Storage Gateway
(X)D. AWS Snowball Edge

192. A company hosts an application on multiple Amazon EC2 instances. The application uses Amazon Simple Notification Service (Amazon SNS) to send messages. Which AWS service or feature will give the application permission to access required AWS services?

A. AWS Certificate Manager (ACM)
(X)B. IAM roles
C. AWS Security Hub
D. Amazon GuardDuty

193. A user has limited knowledge of AWS services, but wants to quickly deploy a scalable Node.js application in the AWS Cloud. Which service should be used to deploy the application?

A. AWS CloudFormation
(X)B. AWS Elastic Beanstalk
C. Amazon EC2
D. AWS OpsWorks

194. A company needs a content delivery network that provides secure delivery of data, videos, applications, and APIs to users globally with low latency and high transfer speeds. Which AWS service meets these requirements?

(X)A. Amazon CloudFront
B. Elastic Load Balancing
C. Amazon S3
D. Amazon Elastic Transcoder

195. A company needs to use third-party software for its workload on AWS. Which AWS service or feature can the company use to purchase the software?

A. AWS Resource Access Manager
B. AWS Managed Services
C. AWS License Manager
(X)D. AWS Marketplace

196. A company needs fully managed, highly reliable, and scalable file storage that is accessible over the Server Message Block (SMB) protocol. Which AWS service will meet these requirements?

A. Amazon S3
B. Amazon Elastic File System (Amazon EFS)
(X)C. Amazon FSx for Windows File Server
D. Amazon Elastic Block Store (Amazon EBS)

197. A company needs to centrally configure and manage Amazon VPC security groups across multiple AWS accounts within an organization in AWS Organizations. Which AWS service should the company use to meet these requirements?

(X)A. AWS Firewall Manager
B. Amazon GuardDuty
C. Amazon Detective
D. AWS WAF

198. Which task is a responsibility of AWS, according to the AWS shared responsibility model?

A. Configure identity and access management for applications.
B. Manage encryption options for data that is stored on AWS.
C. Configure security groups for Amazon EC2 instances.
(X)D. Maintain the physical hardware of the infrastructure.

199. A company has an Amazon EC2 instance in a private subnet. The company wants to initiate a connection to the internet to pull operating system updates while preventing traffic from the internet from accessing the EC2 instance. Which AWS managed service allows this?

A. VPC endpoint
(X)B. NAT gateway
C. Amazon PrivateLink
D. VPC peering

200. Which actions are the responsibility of AWS, according to the AWS shared responsibility model? (Choose two.)

(X)A. Securing the virtualization layer
B. Patching the operating system on Amazon EC2 instances
C. Enforcing a strict password policy for IAM users
(X)D. Patching the operating system on Amazon RDS instances
E. Configuring security groups and network ACLs

201. A company is storing data that will not be frequently accessed in the AWS Cloud. If the company needs to access the data, the data needs to be retrieved within 12 hours. The company wants a solution that is cost-effective for storage costs for each gigabyte. Which Amazon S3 storage class will meet these requirements?

A. S3 Standard
B. S3 Glacier Flexible Retrieval
C. S3 One Zone-Infrequent Access (S3 One Zone-IA)
D. S3 Standard-Infrequent Access (S3 Standard-IA)

202. Which AWS service or resource can be used to identify services that have been used by a user within a specified date range?

A. Amazon S3 access control lists (ACLs)
B. AWS Certificate Manager (ACM)
C. Network Access Analyzer
D. AWS Identity and Access Management Access Analyzer

203. A company needs to engage third-party consultants to help maintain and support its AWS environment and the company’s business needs. Which AWS service or resource will meet these requirements?

A. AWS Support
B. AWS Organizations
C. AWS Service Catalog
D. AWS Partner Network (APN)

204. A company wants to create Amazon QuickSight dashboards every week by using its billing data.
Which AWS feature or tool can the company use to meet these requirements?

A. AWS Budgets
B. AWS Cost Explorer
(X)C. AWS Cost and Usage Report
D. AWS Cost Anomaly Detection

205. A company is planning to move data backups to the AWS Cloud. The company needs to replace on-premises storage with storage that is cloud-based but locally cached. Which AWS service meets these requirements?

A. AWS Storage Gateway
B. AWS Snowcone
C. AWS Backup
D. Amazon Elastic File System (Amazon EFS)

206. A company needs to organize its resources and track AWS costs on a detailed level. The company needs to categorize costs by business department, environment, and application. Which solution will meet these requirements?

A. Access the AWS Cost Management console to organize resources, set an AWS budget, and receive notifications of unintentional usage.
B. Use tags to organize the resources. Activate cost allocation tags to track AWS costs on a detailed level.
C. Create Amazon CloudWatch dashboards to visually organize and track costs individually.
D. Access the AWS Billing and Cost Management dashboard to organize and track resource consumption on a detailed level.

207. A company needs to plan, schedule, and run hundreds of thousands of computing jobs on AWS.
Which AWS service can the company use to meet this requirement?

A. AWS Step Functions
B. AWS Service Catalog
C. Amazon Simple Queue Service (Amazon SQS)
(X)D. AWS Batch

208. Which AWS services or features provide high availability and low latency by enabling failover across different AWS Regions? (Choose two.)

(X)A. Amazon Route 53
B. Network Load Balancer
C. Amazon S3 Transfer Acceleration
(X)D. AWS Global Accelerator
E. Application Load Balancer

209. Which of the following is a way to use Amazon EC2 Auto Scaling groups to scale capacity in the AWS Cloud?

(X)A. Scale the number of EC2 instances in or out automatically, based on demand.
B. Use serverless EC2 instances.
C. Scale the size of EC2 instances up or down automatically, based on demand.
D. Transfer unused CPU resources between EC2 instances.

210. Which abilities are benefits of the AWS Cloud? (Choose two.)

A. Trade variable expenses for capital expenses.
(X)B. Deploy globally in minutes.
C. Plan capacity in advance of deployments.
(X)D. Take advantage of economies of scale.
E. Reduce dependencies on network connectivity.

211. Which AWS security service protects applications from distributed denial of service attacks with always-on detection and automatic inline mitigations?

A. Amazon Inspector
B. AWS Web Application Firewall (AWS WAF)
C. Elastic Load Balancing (ELB)
(X)D. AWS Shield

212. Which AWS service allows users to model and provision AWS resources using common programming languages?

(X)A. AWS CloudFormation
B. AWS CodePipeline
C. AWS Cloud Development Kit (AWS CDK)
D. AWS Systems Manager

213. Which Amazon EC2 instance pricing model can provide discounts of up to 90%?

A. Reserved Instances
B. On-Demand
C. Dedicated Hosts
(X)D. Spot Instances

214. Which of the following acts as an instance-level firewall to control inbound and outbound access?

A. Network access control list
(X)B. Security groups
C. AWS Trusted Advisor
D. Virtual private gateways

215. A company must be able to develop, test, and launch an application in the AWS Cloud quickly.
Which advantage of cloud computing will meet these requirements?

A. Stop guessing capacity
B. Trade fixed expense for variable expense
C. Achieve economies of scale
(X)D. Increase speed and agility

216. A company has teams that have different job roles and responsibilities. The company’s employees often change teams. The company needs to manage permissions for the employees so that the permissions are appropriate for the job responsibilities. Which IAM resource should the company use to meet this requirement with the LEAST operational overhead?

A. IAM user groups
(X)B. IAM roles
C. IAM instance profiles
D. IAM policies for individual users

217. Which AWS service can a company use to securely store and encrypt passwords for a database?

A. AWS Shield
(X)B. AWS Secrets Manager
C. AWS Identity and Access Management (IAM)
D. Amazon Cognito

218. What can a cloud practitioner use to retrieve AWS security and compliance documents and submit them as evidence to an auditor or regulator?

A. AWS Certificate Manager
B. AWS Systems Manager
(X)C. AWS Artifact
D. Amazon Inspector

219. Which encryption types can be used to protect objects at rest in Amazon S3? (Choose two.)

(X)A. Server-side encryption with Amazon S3 managed encryption keys (SSE-S3)
(X)B. Server-side encryption with AWS KMS managed keys (SSE-KMS)
C. TLS
D. SSL
E. Transparent Data Encryption (TDE)

220. A company wants to integrate its online shopping website with social media login credentials.
Which AWS service can the company use to make this integration?

A. AWS Directory Service
B. AWS Identity and Access Management (IAM)
(X)C. Amazon Cognito
D. AWS IAM Identity Center (AWS Single Sign-On)

221. Which AWS service is used to track, record, and audit configuration changes made to AWS resources?

A. AWS Shield
B. AWS Config
C. AWS IAM
D. Amazon Inspector

222. A customer runs an On-Demand Amazon Linux EC2 instance for 3 hours, 5 minutes, and 6 seconds.
For how much time will the customer be billed?

A. 3 hours, 5 minutes
(X)B. 3 hours, 5 minutes, and 6 seconds
C. 3 hours, 6 minutes
D. 4 hours

223. A company website is experiencing DDoS attacks.
Which AWS service can help protect the company website against these attacks?

A. AWS Resource Access Manager
B. AWS Amplify
(X)C. AWS Shield
D. Amazon GuardDuty

224. A company wants a customized assessment of its current on-premises environment. The company wants to understand its projected running costs in the AWS Cloud. Which AWS service or tool will meet these requirements?

A. AWS Trusted Advisor
B. Amazon Inspector
C. AWS Control Tower
(X)D. Migration Evaluator

225. A company that has multiple business units wants to centrally manage and govern its AWS Cloud environments. The company wants to automate the creation of AWS accounts, apply service control policies (SCPs), and simplify billing processes. Which AWS service or tool should the company use to meet these requirements?

(X)A. AWS Organizations
B. Cost Explorer
C. AWS Budgets
D. AWS Trusted Advisor

226. A company is hosting an application in the AWS Cloud. The company wants to verify that underlying AWS services and general AWS infrastructure are operating normally. Which combination of AWS services can the company use to gather the required information? (Choose two.)

(X)A. AWS Personal Health Dashboard
B. AWS Systems Manager
C. AWS Trusted Advisor
(X)D. AWS Service Health Dashboard
E. AWS Service Catalog

227. A company needs to migrate a PostgreSQL database from on-premises to Amazon RDS.
Which AWS service or tool should the company use to meet this requirement?

A. Cloud Adoption Readiness Tool
B. AWS Migration Hub
(X)C. AWS Database Migration Service (AWS DMS)
D. AWS Application Migration Service

228. Which cloud concept is demonstrated by using AWS Compute Optimizer?

A. Security validation
(X)B. Rightsizing
C. Elasticity
D. Global reach

229. A company hosts a large amount of data in AWS. The company wants to identify if any of the data should be considered sensitive. Which AWS service will meet the requirement?

A. Amazon Inspector
(X)B. Amazon Macie
C. AWS Identity and Access Management (IAM)
D. Amazon CloudWatch

230. A user has a stateful workload that will run on Amazon EC2 for the next 3 years.
What is the MOST cost-effective pricing model for this workload?

A. On-Demand Instances
()B. Reserved Instances
C. Dedicated Instances
D. Spot Instances

231. Who enables encryption of data at rest for Amazon Elastic Block Store (Amazon EBS)?

A. AWS Support
(X)B. AWS customers
C. AWS Key Management Service (AWS KMS)
D. AWS Trusted Advisor

232. What can a user accomplish using AWS CloudTrail?

A. Generate an IAM user credentials report.
(X)B. Record API calls made to AWS services.
C. Assess the compliance of AWS resource configurations with policies and guidelines.
D. Ensure that Amazon EC2 instances are patched with the latest security updates.

233. A company is planning to host its workloads on AWS. Which AWS service requires the company to update and patch the guest operating system?

A. Amazon DynamoDB
B. Amazon S3
(X)C. Amazon EC2
D. Amazon Aurora

234. Which AWS service or feature will search for and identify AWS resources that are shared externally?

A. Amazon OpenSearch Service
B. AWS Control Tower
(X)C. AWS IAM Access Analyzer
D. AWS Fargate

235. A company is migrating its workloads to the AWS Cloud. The company must retain full control of patch management for the guest operating systems that host its applications. Which AWS service should the company use to meet these requirements?

A. Amazon DynamoDB
(X)B. Amazon EC2
C. AWS Lambda
D. Amazon RDS

236. At what support level do users receive access to a support concierge?

A. Basic Support
B. Developer Support
C. Business Support
(X)D. Enterprise Support

237. Which AWS service can a company use to visually design and build serverless applications?

A. AWS Lambda
B. AWS Batch
(X)C. AWS Application Composer
D. AWS App Runner

238. A company wants to migrate to AWS and use the same security software it uses on premises. The security software vendor offers its security software as a service on AWS. Where can the company purchase the security solution?

A. AWS Partner Solutions Finder
B. AWS Support Center
C. AWS Management Console
(X)D. AWS Marketplace

239. A company has deployed an Amazon EC2 instance. Which option is an AWS responsibility under the AWS shared responsibility model?

A. Managing and encrypting application data
B. Installing updates and security patches of guest operating system
C. Configuration of infrastructure devices
D. Configuration of security groups on each instance
 
240. A company wants to migrate its PostgreSQL database to AWS. The company does not use the database frequently. Which AWS service or resource will meet these requirements with the LEAST management overhead?

A. PostgreSQL on Amazon EC2
B. Amazon RDS for PostgreSQL
C. Amazon Aurora PostgreSQL-Compatible Edition
(X)D. Amazon Aurora Serverless

241. A company is using Amazon DynamoDB for its application database. Which tasks are the responsibility of AWS, according to the AWS shared responsibility model? (Choose two.)

A. Classify data.
B. Configure access permissions.
C. Manage encryption options.
(X)D. Provide public endpoints to store and retrieve data.
(X)E. Manage the infrastructure layer and the operating system.

242. A company wants to create a globally accessible ecommerce platform for its customers. The company wants to use a highly available and scalable DNS web service to connect users to the platform. Which AWS service will meet these requirements?

A. Amazon EC2
B. Amazon VPC
(X)C. Amazon Route 53
D. Amazon RDS

243. Which maintenance task is the customer’s responsibility, according to the AWS shared responsibility model?

A. Physical connectivity among Availability Zones
B. Network switch maintenance
C. Hardware updates and firmware patches
(X)D. Amazon EC2 updates and security patches

244. A company wants to improve its security posture by reviewing user activity through API calls.
Which AWS service will meet this requirement?

A. AWS WAF
B. Amazon Detective
C. Amazon CloudWatch
(X)D. AWS CloudTrail

245. A company is migrating to the AWS Cloud and plans to run experimental workloads for 3 to 6 months on AWS.
Which pricing model will meet these requirements?

A. Use Savings Plans for a 3-year term.
B. Use Dedicated Hosts.
C. Buy Reserved Instances.
(X)D. Use On-Demand Instances.

246. A company that has AWS Enterprise Support is launching a new version of a popular product in 2 months. The company expects a large increase in traffic to its website. The website is hosted on Amazon EC2 instances.
Which action should the company take to assess its readiness to scale for this launch?

A. Replace the EC2 instances with AWS Lambda functions.
B. Use AWS Infrastructure Event Management (IEM) support.
C. Submit a request on AWS Marketplace to monitor the event.
D. Review the coverage reports in the AWS Cost Management console.

247. A company wants to launch multiple workloads on AWS. Each workload is related to a different business unit. The company wants to separate and track costs for each business unit. Which solution will meet these requirements with the LEAST operational overhead?

A. Use AWS Organizations and create one account for each business unit.
B. Use a spreadsheet to control the owners and cost of each resource.
C. Use an Amazon DynamoDB table to record costs for each business unit.
D. Use the AWS Billing console to assign owners to resources and track costs.

248. A company wants a time-series database service that makes it easier to store and analyze trillions of events each day. Which AWS service will meet this requirement?

A. Amazon Neptune
B. Amazon Timestream
C. Amazon Forecast
D. Amazon DocumentDB (with MongoDB compatibility)

249. Which option is a shared control between AWS and the customer, according to the AWS shared responsibility model?

A. Configuration management
B. Physical and environmental controls
C. Data integrity authentication
D. Identity and access management

250. A company often does not use all of its current Amazon EC2 capacity to run stateless workloads. The company wants to optimize its EC2 costs. Which EC2 instance type will meet these requirements?

(X)A. Spot Instances
B. Dedicated Instances
C. Reserved Instances
D. On-Demand Instances

251. A company wants to store data in Amazon S3. The company rarely access the data, and the data can be regenerated if necessary. The company wants to store the data in the most cost-effective storage class. Which S3 storage class will meet this requirement?

A. S3 Standard
B. S3 Intelligent-Tiering
C. S3 Standard-Infrequent Access (S3 Standard-IA)
(X)D. S3 One Zone-Infrequent Access (S3 One Zone-IA)

252. A company has migrated its workloads to AWS. The company wants to adopt AWS at scale and operate more efficiently and securely. Which AWS service or framework should the company use for operational support?

A. AWS Support
B. AWS Cloud Adoption Framework (AWS CAF)
(X)C. AWS Managed Services (AMS)
D. AWS Well-Architected Framework

253. A company wants to provision and manage its AWS infrastructure by using the common programming languages Typescript, Python, Java, and .NET. Which AWS service will meet this requirement?

A. AWS CodeBuild
B. AWS CloudFormation
C. AWS CLI
(X)D. AWS Cloud Development Kit (AWS CDK)

254. Which Amazon EC2 pricing model provides the MOST cost savings for an always-up, right-sized database server running for a project that will last 1 year?

A. On-Demand Instances
B. Convertible Reserved Instances
C. Spot Instances
(X)D. Standard Reserved Instances

255. A company has a physical tape library to store data backups. The tape library is running out of space. The company needs to extend the tape library's capacity to the AWS Cloud.

Which AWS service should the company use to meet this requirement?

A. Amazon Elastic File System (Amazon EFS)
B. Amazon Elastic Block Store (Amazon EBS)
C. Amazon S3
(X)D. AWS Storage Gateway

256. A company is using the AWS Free Tier for several AWS services for an application.
What will happen if the Free Tier usage period expires or if the application use exceeds the Free Tier usage limits?

(X)A. The company will be charged the standard pay-as-you-go service rates for the usage that exceeds the Free Tier usage.
B. AWS Support will contact the company to set up standard service charges.
C. The company will be charged for the services it consumed during the Free Tier period, plus additional charges for service consumption after the Free Tier period.
D. The company's AWS account will be frozen and can be restarted after a payment plan is established.

257. A company wants to monitor its workload performance. The company wants to ensure that the cloud services are delivered at a level that meets its business needs. Which AWS Cloud Adoption Framework (AWS CAF) perspective will meet these requirements?

A. Business
B. Governance
C. Platform
(X)D. Operations

258. A company wants to migrate its applications to the AWS Cloud. The company plans to identify and prioritize any business transformation opportunities and evaluate its AWS Cloud readiness. Which AWS service or tool should the company use to meet these requirements?

(X)A. AWS Cloud Adoption Framework (AWS CAF)
B. AWS Managed Services (AMS)
C. AWS Well-Architected Framework
D. AWS Migration Hub

259. A company need an AWS service that provides a clear baseline of what the company runs in its on-premises data centers. The company needs the projected cost to run its on-premises workloads in the AWS Cloud. What AWS service or tool will meet these requirements?

A. AWS Compute Optimizer
B. AWS Cost Explorer
C. AWS Systems Manager Agent (SSM Agent)
(X)D. Migration Evaluator

260. A company acquired another corporation. The company now has two AWS accounts. Which AWS service or tool can the company use to consolidate the billing for these two accounts?

A. AWS Systems Manager
(X)B. AWS Organizations
C. AWS License Manager
D. Cost Explorer

261. A company wants to set up its workloads to perform their intended functions and recover quickly from failure. Which pillar of the AWS Well-Architected Framework aligns with these goals?

A. Performance efficiency
B. Sustainability
(X)C. Reliability
D. Security

262. Which of the following is a managed AWS service that is used specifically for extract, transform, and load (ETL) data?

A. Amazon Athena
(X)B. AWS Glue
C. Amazon S3
D. AWS Snowball Edge

263. A company wants to migrate petabytes of data from its on-premises data center to AWS. The company does not want to use an internet connection to perform the migration. Which AWS service will meet these requirements?

A. AWS DataSync
B. Amazon Connect
(X)C. AWS Snowmobile
D. AWS Direct Connect

264. A company wants to receive alerts to monitor its overall operating costs for its AWS public cloud infrastructure. Which AWS offering will meet these requirements?

A. Amazon EventBridge
B. Compute Savings Plans
(X)C. AWS Budgets
D. Migration Evaluator

265. How does the AWS Enterprise Support Concierge team help users?

A. Supporting application development
B. Providing architecture guidance
(X)C. Answering billing and account inquiries
D. Answering questions regarding technical support cases

266. A company wants to run a simulation for 3 years without interruptions. Which Amazon EC2 instance purchasing option will meet these requirements MOST cost-effectively?

A. Spot Instances
(X)B. Reserved Instances Most Voted
C. Dedicated Hosts
D. On-Demand Instances

267. Which AWS service or resource can provide discounts on some AWS service costs in exchange for a spending commitment?

A. Amazon Detective
B. AWS Pricing Calculator
(X)C. Savings Plans
D. Basic Support

268. Which of the following are pillars of the AWS Well-Architected Framework? (Choose two.)

A. High availability
(X)B. Performance efficiency
C. Cost optimization
D. Going global in minutes
E. Continuous development

269. A company wants to use Amazon EC2 instances to provide a static website to users all over the world. The company needs to minimize latency for the users. Which solution meets these requirements?

A. Use EC2 instances in multiple edge locations.
B. Use EC2 instances in the same Availability Zone but in different AWS Regions.
(X)C. Use Amazon CloudFront with the EC2 instances configured as the source.
D. Use EC2 instances in the same Availability Zone but in different AWS accounts.

270. A team of researchers is going to collect data at remote locations around the world. Many locations do not have internet connectivity. The team needs to capture the data in the field, and transfer it to the AWS Cloud later. Which AWS service will support these requirements?

A. AWS Outposts
B. AWS Transfer Family
(X)C. AWS Snow Family
D. AWS Migration Hub

271. Which of the following are benefits that a company receives when it moves an on-premises production workload to AWS? (Choose two.)

A. AWS trains the company's staff on the use of all the AWS services.
B. AWS manages all security in the cloud.
C. AWS offers free support from technical account managers (TAMs).
D. AWS offers high availability.
E. AWS provides economies of scale.

272. A company has decided to adopt Amazon EC2 infrastructure and wants to scale various stateless services for short-term usage. Which EC2 pricing model is MOST cost-efficient to meet these requirements?

A. Spot Instances
B. On-Demand Instances
C. Reserved Instances
D. Dedicated Hosts

273. Which of the following are benefits of AWS Trusted Advisor? (Choose two.)

A. Access to Amazon Simple Queue Service (Amazon SQS)
B. Cost optimization recommendations
C. Hourly refresh of the service limit checks
D. Security checks
E. AWS Identity and Access Management (IAM) approval management

274. A company wants to save costs by archiving data that is no longer frequently accessed by end users. Which Amazon S3 feature will meet this requirement?

A. S3 Versioning
(X)B. S3 Lifecycle
C. S3 Object Lock
D. S3 Inventory

275. Which cloud computing advantage is a company applying when it uses AWS Regions to increase application availability to users in different countries?

A. Pay-as-you-go pricing
B. Capacity forecasting
C. Economies of scale
(X)D. Global reach

276. A company wants an AWS service to collect and process 10 TB of data locally and transfer the data to AWS. The company has intermittent connectivity.

Which AWS service will meet these requirements?

A. AWS Database Migration Service (AWS DMS)
B. AWS DataSync
C. AWS Backup
(X)D. AWS Snowball Edge

277. Which of the following is an AWS Well-Architected Framework design principle for operational excellence in the AWS Cloud?

A. Go global in minutes.
(X)B. Make frequent, small, reversible changes.
C. Implement a strong foundation of identity and access management
D. Stop spending money on hardware infrastructure for data center operations.

278. What is a benefit of using AWS serverless computing?

A. Application deployment and management are not required.
B. Application security will be fully managed by AWS.
C. Monitoring and logging are not needed.
(X)D. Management of infrastructure is offloaded to AWS.

279. A developer wants AWS users to access AWS services by using temporary security credentials.
Which AWS service or feature should the developer use to provide these credentials?

A. IAM policies
B. IAM user groups
(X)C. AWS Security Token Service (AWS STS)
D. AWS IAM Identity Center (AWS Single Sign-On)

280. A global company wants to use a managed security service for protection from SQL injection attacks. The service also must provide detailed logging information about access to the company's ecommerce applications. Which AWS service will meet these requirements?

A. AWS Network Firewall
B. Amazon RDS for SQL Server
C. Amazon GuardDuty
(X)D. AWS WAF

281. A company is migrating its on-premises server to an Amazon EC2 instance. The server must stay active at all times for the next 12 months.

Which EC2 pricing option is the MOST cost-effective for the company's workload?

A. On-Demand
B. Dedicated Hosts
C. Spot Instances
(X)D. Reserved Instances

282. Which of the following is the customer's responsibility under the AWS shared responsibility model? (Choose two.)

A. Maintain the configuration of infrastructure devices.
B. Maintain patching and updates within the hardware infrastructure.
(X)C. Maintain the configuration of guest operating systems and applications.
(X)D. Manage decisions involving encryption options.
E. Maintain infrastructure hardware.

283. A company wants to verify if multi-factor authentication (MFA) is enabled for all users within its AWS accounts. Which AWS service or resource will meet this requirement?

A. AWS Cost and Usage Report
(X)B. IAM credential reports
C. AWS Artifact
D. Amazon CloudFront reports

284. A company uses AWS security services and tools. The company needs a service to help manage the security alerts and must organize the alerts into a single dashboard. Which AWS service should the company use to meet these requirements?

A. Amazon GuardDuty
B. Amazon Inspector
C. Amazon Macie
(X)D. AWS Security Hub

285. A company wants to run its workloads in the AWS Cloud effectively, reduce management overhead, and improve processes. Which AWS Well-Architected Framework pillar represents these requirements?

A. Reliability
(X)B. Operational excellence
C. Performance efficiency
D. Cost optimization

286. A company uses Amazon S3 to store records that can contain personally identifiable information (PII). The company wants a solution that can monitor all S3 buckets for PII and immediately alert staff about vulnerabilities.

Which AWS service will meet these requirements?

A. Amazon GuardDuty
B. Amazon Detective
(X)C. Amazon Macie
D. AWS Shield

287. Which AWS service allows users to download security and compliance reports about the AWS infrastructure on demand?

A. Amazon GuardDuty
B. AWS Security Hub
(X)C. AWS Artifact
D. AWS Shield

288. An external auditor has requested that a company provide a list of all its IAM users, including the status of users' credentials and access keys. What is the SIMPLEST way to provide this information?

A. Create an IAM user account for the auditor, granting the auditor administrator permissions.
B. Take a screenshot of each user's page in the AWS Management Console, then provide the screenshots to the auditor.
(X)C. Download the IAM credential report, then provide the report to the auditor.
D. Download the AWS Trusted Advisor report, then provide the report to the auditor.

289. Which task can a company perform by using security groups in the AWS Cloud?

(X)A. Allow access to an Amazon EC2 instance through only a specific port.
B. Deny access to malicious IP addresses at a subnet level.
C. Protect data that is cached by Amazon CloudFront.
D. Apply a stateless firewall to an Amazon EC2 instance.

290. A company plans to run a compute-intensive workload that uses graphics processing units (GPUs). Which Amazon EC2 instance type should the company use?

(X)A. Accelerated computing
B. Compute optimized
C. Storage optimized
D. General purpose

291. Which of the following are features of network ACLs as they are used in the AWS Cloud? (Choose two.)

(X)A. They are stateless.
B. They are stateful.
C. They evaluate all rules before allowing traffic.
(X)D. They process rules in order, starting with the lowest numbered rule, when deciding whether to allow traffic.
E. They operate at the instance level.

292. Which capabilities are in the platform perspective of the AWS Cloud Adoption Framework (AWS CAF)? (Choose two.)

A. Performance and capacity management
(X)B. Data engineering
(X)C. Continuous integration and continuous delivery (CI/CD)
D. Infrastructure protection
E. Change and release management

293. According to the AWS shared responsibility model, the customer is responsible for applying the latest security updates and patches for which of the following?

A. Amazon DynamoDB
(X)B. Amazon EC2 instances
C. Amazon RDS instances
D. Amazon S3

294. Which Amazon S3 storage class is MOST cost-effective for unknown access patterns?

A. S3 Standard
B. S3 Standard-Infrequent Access (S3 Standard-IA)
C. S3 One Zone-Infrequent Access (S3 One Zone-IA)
(X)D. S3 Intelligent-Tiering

295. Which options are AWS Cloud Adoption Framework (AWS CAF) security perspective capabilities? (Choose two.)

A. Observability
B. Incident and problem management
(X)C. Incident response
(X)D. Infrastructure protection
E. Availability and continuity

296. A company has a managed IAM policy that does not grant the necessary permissions for users to accomplish required tasks. How can this be resolved?

A.Enable AWS Shield Advanced.
(X)B. Create a custom IAM policy.
C. Use a third-party web application firewall (WAF) managed rule from the AWS Marketplace.
D. Use AWS Key Management Service (AWS KMS) to create a customer-managed key.

297. Who is responsible for managing IAM user access and secret keys according to the AWS shared responsibility model?

A. IAM access and secret keys are static, so there is no need to rotate them.
(X)B. The customer is responsible for rotating keys.
C. AWS will rotate the keys whenever required.
D. The AWS Support team will rotate keys when requested by the customer.

298. A company needs to run a pre-installed third-party firewall on an Amazon EC2 instance. Which AWS service or feature can provide this solution?

A. Network ACLs
B. Security groups
(X)C. AWS Marketplace
D. AWS Trusted Advisor

299. Which AWS Cloud benefit gives a company the ability to quickly deploy cloud resources to access compute, storage, and database infrastructures in a matter of minutes?

A. Elasticity
B. Cost savings
(X)C. Agility
D. Reliability

## 300. Which of the following is entirely the responsibility of AWS, according to the AWS shared responsibility model?

A. Security awareness and training

B. Development of an IAM password policy

C. Patching of the guest operating system

**D. Physical and environmental controls**

## 301. Which of the following is a characteristic of the AWS account root user?

A. The root user is the only user that can be configured with multi-factor authentication (MFA).

B. The root user is the only user that can access the AWS Management Console.

**C. The root user is the first sign-in identity that is available when an AWS account is created.**

D. The root user has a password that cannot be changed.

## 302. An Amazon EC2 instance previously used for development is inaccessible and no longer appears in the AWS Management Console. Which AWS service should be used to determine what action made this EC2 instance inaccessible?

A. Amazon CloudWatch Logs

B. AWS Security Hub

C. Amazon Inspector

**D. AWS CloudTraiI**

## 303. A company's application developers need to quickly provision and manage AWS services by using scripts. Which AWS offering should the developers use to meet these requirements?

**A. AWS CLI**

B. AWS CodeBuild

C. AWS Cloud Adoption Framework (AWS CAF)

D. AWS Systems Manager Session Manager

## 304. A company wants to migrate unstructured data to AWS. The data needs to be securely moved with inflight encryption and end-to-end data validation. Which AWS service will meet these requirements?

A. AWS Application Migration Service

B. Amazon Elastic File System (Amazon EFS)

**C. AWS DataSync**

D. AWS Migration Hub

## 305. A development team wants to deploy multiple test environments for an application in a fast, repeatable manner. Which AWS service should the team use?

A. Amazon EC2

**B. AWS CloudFormation**

C. Amazon QuickSight

D. Amazon Elastic Container Service (Amazon ECS)

## 306. A company wants to quickly implement a continuous integration/continuous delivery (CI/CD) pipeline. Which AWS service will meet this requirement?

A. AWS Config

B. Amazon Cognito

C. AWS DataSync

**D. AWS CodeStar**

## 307. Which AWS Cloud deployment model uses AWS Outposts as part of the application deployment infrastructure?

A. On-premises

B. Serverless

C. Cloud-native

**D. Hybrid**

## 308. Which of the following is a fully managed graph database service on AWS?

A. Amazon Aurora

B. Amazon FSx

C. Amazon DynamoDB

**D. Amazon Neptune**

## 309. Which AWS service could an administrator use to provide desktop environments for several employees?

A. AWS Organizations

B. AWS Fargate

C. AWS WAF

**D. AWS WorkSpaces**

## 310. Which AWS service or feature gives users the ability to capture information about network traffic in a VPC?

**A. VPC Flow Logs**

B. Amazon Inspector

C. VPC route tables

D. AWS CloudTrail

## 311. Which type of AWS storage is ephemeral and is deleted when an Amazon EC2 instance is stopped or terminated?

A. Amazon Elastic Block Store (Amazon EBS)

**B. Amazon EC2 instance store**

C. Amazon Elastic File System (Amazon EFS)

D. Amazon S3

## 312. A company wants to provide access to Windows file shares in AWS from its on-premises workloads. The company does not want to provision any additional infrastructure or applications in its data center. Which AWS service will meet these requirements?

**A. Amazon FSx File Gateway**

B. AWS DataSync

C. Amazon S3

D. AWS Snow Family

## 313. A company wants durable storage for static content and infinitely scalable data storage infrastructure at the lowest cost. Which AWS service should the company choose?

A. Amazon Elastic Block Store (Amazon EBS)

**B. Amazon S3**

C. AWS Storage Gateway

D. Amazon Elastic File System (Amazon EFS)

## 314. An ecommerce company wants to use Amazon EC2 Auto Scaling to add and remove EC2 instances based on CPU utilization. Which AWS service or feature can initiate an Amazon EC2 Auto Scaling action to achieve this goal?

A. Amazon Simple Queue Service (Amazon SQS)

B. Amazon Simple Notification Service (Amazon SNS)

C. AWS Systems Manager

**D. Amazon CloudWatch alarm**

## 315. A company wants to transform its workforce by attracting and developing a digitally fluent high-performance workforce. The company wants to attract a diverse and inclusive workforce with appropriate mix of technical and non-technical skills. Which AWS Cloud Adoption Framework (AWS CAF) perspective will meet these requirements?

A. Business

**B. People**

C. Platform

D. Operations

## 316. A company wants to move its on-premises databases to managed cloud database services by using a simplified migration process. Which AWS service or tool can help the company meet this requirement?

A. AWS Storage Gateway

B. AWS Application Migration Service

C. AWS DataSync

**D. AWS Database Migration Service (AWS DMS)**

## 317. A company needs a fully managed file server that natively supports Microsoft workloads and file systems. The file server must also support the SMB protocol. Which AWS service should the company use to meet these requirements?

A. Amazon Elastic File System (Amazon EFS)

B. Amazon FSx for Lustre

**C. Amazon FSx for Windows File Server**

D. Amazon Elastic Block Store (Amazon EBS)

## 318. A company has been storing monthly reports in an Amazon S3 bucket. The company exports the report data into comma-separated values (.csv) files. A developer wants to write a simple query that can read all of these files and generate a summary report. Which AWS service or feature should the developer use to meet these requirements with the LEAST amount of operational overhead?

A. Amazon S3 Select

**B. Amazon Athena**

C. Amazon Redshift

D. Amazon EC2

## 319. Which AWS feature provides a no-cost platform for AWS users to join community groups, ask questions, find answers, and read community-generated articles about best practices?

A. AWS Knowledge Center

**B. AWS re:Post**

C. AWS IQ

D. AWS Enterprise Support

320. A company needs to search for text in documents that are stored in Amazon S3. Which AWS service will meet these requirements?

(X)A. Amazon Kendra
B. Amazon Rekognition
C. Amazon Polly
D. Amazon Lex

321. Which AWS services make use of global edge locations? (Choose two.)

A. AWS Fargate
(X)B. Amazon CloudFront
(X)C. AWS Global Accelerator
D. AWS Wavelength
E. Amazon VPC

322. A user needs a relational database but does not have the resources to manage the hardware, resiliency, and replication. Which AWS service option meets the user's requirements?

A. Run MySQL on Amazon Elastic Container Service (Amazon ECS).
B. Run MySQL on Amazon EC2.
(X)C. Choose Amazon RDS for MySQL.
D. Choose Amazon ElastiCache for Redis.

323. A company needs to deploy applications in the AWS Cloud as quickly as possible. The company also needs to minimize the complexity that is related to the management of AWS resources. Which AWS service should the company use to meet these requirements?

A. AWS Config
(X)B. AWS Elastic Beanstalk
C. Amazon EC2
D. Amazon Personalize

324. Which mechanism allows developers to access AWS services from application code?

(X)A. AWS Software Development Kit
B. AWS Management Console
C. AWS CodePipeline
D. AWS Config

325. A company is migrating to the AWS Cloud. The company wants to understand and identify potential security misconfigurations or unexpected behaviors. The company wants to prioritize any protective controls it might need. Which AWS Cloud Adoption Framework (AWS CAF) security perspective capability will meet these requirements?

A. Identity and access management
(X)B. Threat detection
C. Platform engineering
D. Availability and continuity management

326. A company wants to establish a private network connection between AWS and its corporate network. Which AWS service or feature will meet this requirement?

A. Amazon Connect
B. Amazon Route 53
(X)C. AWS Direct Connect
D. VPC peering

327. Which AWS services or features give users the ability to create a network connection between two VPCs? (Choose two.)

A. VPC endpoints
B. Amazon Route 53
(X)C. VPC peering
D. AWS Direct Connect
(X)E. AWS Transit Gateway

328. Which AWS service converts text to lifelike voices?

A. Amazon Transcribe
B. Amazon Rekognition
(X)C. Amazon Polly
D. Amazon Textract

329. A company wants to use application stacks to run a workload in the AWS Cloud. The company wants to use pre-configured instances. Which AWS service will meet these requirements?

(X)A. Amazon Lightsail
B. Amazon Athena
C. AWS Outposts
D. Amazon EC2

330. Which AWS services are supported by Savings Plans? (Choose two.)

(X)A. Amazon EC2
B. Amazon RDS
(X)C. Amazon SageMaker
D. Amazon Redshift
E. Amazon DynamoDB

331. Which AWS service or tool can provide rightsizing recommendations for Amazon EC2 resources at no additional cost?

A. AWS Well-Architected Tool
B. Amazon CloudWatch
(X)C. AWS Cost Explorer
D. Amazon S3 analytics

332. A company operates a petabyte-scale data warehouse to analyze its data. The company wants a solution that will not require manual hardware and software management. Which AWS service will meet these requirements?

A. Amazon DocumentDB (with MongoDB compatibility)
(X)B. Amazon Redshift
C. Amazon Neptune
D. Amazon ElastiCache

333. A library wants to automate the classification of electronic books based on the contents of the books. Which AWS service should the library use to meet this requirement?

A. Amazon Redshift
B. Amazon CloudSearch
(X)C. Amazon Comprehend
D. Amazon Aurora

334. Which task is a responsibility of AWS, according to the AWS shared responsibility model?

A. Encryption of application data
B. Authentication of application users
(X)C. Protection of physical network infrastructure
D. Configuration of firewalls

335. Which options are AWS Cloud Adoption Framework (AWS CAF) cloud transformation journey recommendations? (Choose two.)

(X)A. Envision phase
(X)B. Align phase
C. Assess phase
D. Mobilize phase
E. Migrate and modernize phase

336. A company wants to generate a list of IAM users. The company also wants to view the status of various credentials that are associated with the users, such as password, access keys, and multi-factor authentication (MFA) devices. Which AWS service or feature will meet these requirements?

(X)A. IAM credential report
B. AWS IAM Identity Center (AWS Single Sign-On)
C. AWS Identity and Access Management Access Analyzer
D. AWS Cost and Usage Report

337. A company is designing its AWS workloads so that components can be updated regularly and so that changes can be made in small, reversible increments. Which pillar of the AWS Well-Architected Framework does this design support?

A. Security
B. Performance efficiency
(X)C. Operational excellence
D. Reliability

## 338. A company wants to track tags, buckets, and prefixes for its Amazon S3 objects. Which S3 feature will meet this requirement?

**A. S3 Inventory report**

B. S3 Lifecycle

C. S3 Versioning

D. S3 ACLs

## 339. A company wants to allow users to authenticate and authorize multiple AWS accounts by using a single set of credentials. Which AWS service or resource will meet this requirement?

A. AWS Organizations

B. IAM user

**C. AWS IAM Identity Center (AWS Single Sign-On)**

D. AWS Control Tower

## 340. A company created an Amazon EC2 instance. The company wants to control the incoming and outgoing network traffic at the instance level. Which AWS resource or service will meet this requirement?

A. AWS Shield

**B. Security groups**

C. Network Access Analyzer

D. VPC endpoints

## 341. A company wants to use the AWS Cloud to deploy an application globally. Which architecture deployment model should the company use to meet this requirement?

**A. Multi-Region**

B. Single-Region

C. Multi-AZ

D. Single-AZ

## 342. A company wants a web application to interact with various AWS services. Which AWS service or resource will meet this requirement?

A. AWS CloudShell

B. AWS Marketplace

C. AWS Management Console

**D. AWS CLI**

## 343. A company is migrating its applications from on-premises to the AWS Cloud. The company wants to ensure that the applications are assigned only the minimum permissions that are needed to perform all operations. Which AWS service will meet these requirements?

**A. AWS Identity and Access Management (IAM)**

B. Amazon CloudWatch

C. Amazon Macie

D. Amazon GuardDuty

## 344. Which options are AWS Cloud Adoption Framework (AWS CAF) governance perspective capabilities? (Choose two.)

A. Identity and access management

**B. Cloud financial management**

**C. Application portfolio management**

D. Innovation management

E. Product management

## 345. Which AWS service provides a single location to track the progress of application migrations?

A. AWS Application Discovery Service

B. AWS Application Migration Service

C. AWS Service Catalog

**D. AWS Migration Hub**

## 346. A company launched an Amazon EC2 instance with the latest Amazon Linux 2 Amazon Machine Image (AMI). Which actions can a system administrator take to connect to the EC2 instance? (Choose two.)

**A. Use Amazon EC2 Instance Connect.**

B. Use a Remote Desktop Protocol (RDP) connection.

C. Use AWS Batch.

**D. Use AWS Systems Manager Session Manager.**

E. Use Amazon Connect.

## 347. Which architecture concept describes the ability to deploy resources on demand and release resources when they are no longer needed?

A. High availability

B. Decoupled architecture

C. Resilience

**D. Elasticity**

## 348. Which task requires a user to sign in as the AWS account root user?

A. The deletion of IAM users

**B. The deletion of an AWS account**

C. The creation of an organization in AWS Organizations

D. The deletion of Amazon EC2 instances

## 349. What does the Amazon S3 Intelligent-Tiering storage class offer?

A. Payment flexibility by reserving storage capacity

B. Long-term retention of data by copying the data to an encrypted Amazon Elastic Block Store (Amazon EBS) volume

**C. Automatic cost savings by moving objects between tiers based on access pattern changes**

D. Secure, durable, and lowest cost storage for data archiva.

## 350. A company needs Amazon EC2 instances for a workload that can tolerate interruptions. Which EC2 instance purchasing option meets this requirement with the LARGEST discount compared to On-Demand prices?

**A. Spot Instances**

B. Convertible Reserved Instances

C. Standard Reserved Instances

D. Dedicated Hosts

## 351. A company is planning to migrate to the AWS Cloud. The company wants to identify measurable business outcomes that will explain the value of the company's decision to migrate. Which phase of the cloud transformation journey includes these activities?

**A. Envision**

B. Align

C. Scale

D. Launch

## 352. Which AWS service or component allows inbound traffic from the internet to access a VPC?

**A. Internet gateway**

B. NAT gateway

C. AWS WAF

D. VPC peering

## 353. Which AWS service can companies use to create infrastructure from code?

A. Amazon Elastic Kubernetes Service (Amazon EKS)

B. AWS Outposts

C. AWS CodePipeline

**D. AWS CloudFormation**

## 354. Which guideline is a well-architected design principle for building cloud applications?

A. Keep static data closer to compute resources.

B. Provision resources for peak capacity.

**C. Design for automated recovery from failure.**

D. Use tightly coupled components.

## 355. A company needs to move 75 petabytes of data from its on-premises data centers to AWS. Which AWS service should the company use to meet these requirements MOST cost-effectively?

A. AWS Snowball Edge Storage Optimized

**B. AWS Snowmobile**

C. AWS Direct Connect

D. AWS Storage Gateway

## 356. Which of the following are pillars of the AWS Well-Architected Framework? (Choose two.)

A. Resource scalability

**B. Performance efficiency**

C. System elasticity

D. Agile development

**E. Operational excellence**

## 357. A company needs to connect its on-premises data center to the AWS Cloud. The company needs a dedicated, low-latency connection with consistent network performance. Which AWS service will meet these requirements?

A. AWS Global Accelerator

B. Amazon CloudFront

**C. AWS Direct Connect**

D. AWS Managed VPN

## 358. Which design principles should a company apply to AWS Cloud workloads to maximize sustainability and minimize environmental impact? (Choose two.)

**A. Maximize utilization of Amazon EC2 instances.**

B. Minimize utilization of Amazon EC2 instances.

C. Minimize usage of managed services.

D. Force frequent application reinstallations by users.

**E. Reduce the need for users to reinstall applications.**

## 359. In which ways does the AWS Cloud offer lower total cost of ownership (TCO) of computing resources than on-premises data centers? (Choose two.)

**A. AWS replaces upfront capital expenditures with pay-as-you-go costs.**

B. AWS is designed for high availability, which eliminates user downtime.

C. AWS eliminates the need for on-premises IT staff.

**D. AWS uses economies of scale to continually reduce prices.**

E. AWS offers a single pricing model for Amazon EC2 instances.

## 360.  company wants to deploy some of its resources in the AWS Cloud. To meet regulatory requirements, the data must remain local and on premises. There must be low latency between AWS and the company resources. Which AWS service or feature can be used to meet these requirements?

A. AWS Local Zones

B. Availability Zones

**C. AWS Outpost**

D. AWS Wavelength Zones

## 361. Which of the following AWS services are serverless? (Choose two.)

A. AWS Outposts

B. Amazon EC2

C. Amazon Elastic Kubernetes Service (Amazon EKS)

**D. AWS Fargate**

**E. AWS Lambda**

## 362. When a user wants to utilize their existing per-socket, per-core, or per-virtual machine software licenses for a Microsoft Windows server running on AWS, which Amazon EC2 instance type is required?

A. Spot Instances

B. Dedicated Instances

**C. Dedicated Hosts**

D. Reserved Instances

## 363. A solutions architect needs to maintain a fleet of Amazon EC2 instances so that any impaired instances are replaced with new ones. Which AWS service should the solutions architect use?

A. Amazon Elastic Container Service (Amazon ECS)

B. Amazon GuardDuty

C. AWS Shield

**D. AWS Auto Scaling**

## 364. Which AWS service provides on-premises applications with low-latency access to data that is stored in the AWS Cloud?

A. Amazon CloudFront

**B. AWS Storage Gateway**

C. AWS Backup

D. AWS DataSync

## 365. What does Amazon CloudFront provide?

A. Automatic scaling for all resources to power an application from a single unified interface

**B. Secure delivery of data, videos, applications, and APIs to users globally with low latency**

C. Ability to directly manage traffic globally through a variety of routing types, including latency-based routing, geo DNS, geoproximity, and weighted round robin

D. Automatic distribution of incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and AWS Lambda functions

## 366. Which AWS service supports the deployment and management of applications in the AWS Cloud?

A. Amazon CodeGuru

B. AWS Fargate

C. AWS CodeCommit

**D. AWS Elastic Beanstalk**

## 367. A company wants to integrate natural language processing (NLP) into business intelligence (BI) dashboards. The company wants to ask questions and receive answers with relevant visualizations. Which AWS service or tool will meet these requirements?

A. Amazon Macie

B. Amazon Rekognition

**C. Amazon QuickSight Q**

D. Amazon Lex

## 368. Which Amazon S3 feature or storage class uses the AWS backbone network and edge locations to reduce latencies from the end user to Amazon S3?

A. S3 Cross-Region Replication

**B. S3 Transfer Acceleration**

C. S3 Event Notifications

D. S3 Standard-Infrequent Access (S3 Standard-IA)

## 369. Which AWS service provides the ability to host a NoSQL database in the AWS Cloud?

A. Amazon Aurora

**B. Amazon DynamoDB**

C. Amazon RDS

D. Amazon Redshift

## 370. Which AWS service is a relational database compatible with MySQL and PostgreSQL?

A. Amazon Redshift

B. Amazon DynamoDB

**C. Amazon Aurora**

D. Amazon Neptune

## 371. Which architecture design principle describes the need to isolate failures between dependent components in the AWS Cloud?

A. Use a monolithic design.

B. Design for automation.

C. Design for single points of failure.

**D. Loosely couple components**

## 372. Which benefit of cloud computing gives a company the ability to deploy applications to users all over the world through a network of AWS Regions, Availability Zones, and edge locations?

A. Economy of scale

**B. Global reach**

C. Agility

D. High availability

## 373. Which AWS service makes it easier to monitor and troubleshoot application logs and cloud resources?

A. Amazon EC2

B. AWS Identity and Access Management (IAM)

**C. Amazon CloudWatch**

D. AWS CloudTrail

## 374. Which AWS service uses AWS Compute Optimizer to provide sizing recommendations based on workload metrics?

**A. Amazon EC2**

B. Amazon RDS

C. Amazon Lightsail

D. AWS Step Functions

## 375. Which AWS service will help a company plan a migration to AWS by collecting the configuration, usage, and behavior data of on-premises data centers?

A. AWS Resource Groups

**B. AWS Application Discovery Service**

C. AWS Service Catalog

D. AWS Systems Manager

## 376. Which AWS service uses a combination of publishers and subscribers?

A. AWS Lambda

**B. Amazon Simple Notification Service (Amazon SNS)**

C. Amazon CloudWatch

D. AWS CloudFormation

## 377. A company is in the early stages of planning a migration to AWS. The company wants to obtain the monthly predicted total AWS cost of ownership for future Amazon EC2 instances and associated storage. Which AWS service or tool should the company use to meet these requirements?
 
**A.AWS Pricing Calculator**
B. AWS Compute Optimizer
C. AWS Trusted Advisor
D. AWS Application Migration Service

## 378. A company deploys a new application to Amazon EC2 instances. The application code is stored in an AWS CodeCommit repository. The company uses an AWS CodePipeline pipeline to deploy the code to the EC2 instances through a continuous integration and continuous delivery (CI/CD) process.

A SysOps administrator needs to ensure that sensitive database information is configured properly on the EC2 instances to prevent accidental leakage of credentials.

Which solutions will store and retrieve the sensitive information in the MOST secure manner? (Choose two.)

**A.** Store the values in **AWS Secrets Manager**. Update the code to retrieve these values when the application starts. Store the values as environmental variables that the application can use.

B. Store the values in AWS Systems Manager Parameter Store as secret strings. Update the code to retrieve these values when the application starts. Store the values as environmental variables that the application can use.

C. Store the values in an AWS Lambda function. Update the code to invoke the Lambda function when the application starts. Configure the Lambda function to inject the values as environmental variables that the application can use.

D. Store the configuration information in a file on the EC2 instances. Ensure that the underlying drives are encrypted by AWS Key Management Service (AWS KMS). Update the application to read the file when the application starts. Store the values as environmental variables.

E. Store the values in a text file in an Amazon S3 bucket. In the CI/CD pipeline, copy the file to the EC2 instance in an appropriate location on a disk that the application can read.

## 379. A large company is migrating its entire IT portfolio to AWS. Each business unit in the company has a standalone AWS account that supports both development and test environments. New accounts to support production workloads will be needed soon.

The finance department requires a centralized method for payment but must maintain visibility into each group's spending to allocate costs.

The security team requires a centralized mechanism to control IAM usage in all the company’s accounts.

What combination of the following options meets the company’s needs with the LEAST effort? (Choose two.)

A. Use a collection of parameterized AWS CloudFormation templates defining common IAM permissions that are launched into each account. Require all new and existing accounts to launch the appropriate stacks to enforce the least privilege model.

**B.** Use **AWS Organizations** to create a new organization from a chosen payer account and define an organizational unit hierarchy. Invite the existing accounts to join the organization and create new accounts using Organizations.

C. Require each business unit to use its own AWS accounts. Tag each AWS account appropriately and enable Cost Explorer to administer chargebacks.

**D.** Enable all features of AWS Organizations and establish appropriate service control policies that filter IAM permissions for sub-accounts.

E. Consolidate all of the company's AWS accounts into a single AWS account. Use tags for billing purposes and the IAM’s Access Advisor feature to enforce the least privilege model.

## 380. A company needs to analyze its AWS Cloud environment to determine whether the company is following security best practices. The company wants recommendations about how to close security gaps. Which AWS service should the company use to obtain these recommendations?

A. AWS WAF

B. AWS Systems Manager

**C. AWS Trusted Advisor**

D. AWS Shield

## 381. A company is using AWS Identity and Access Management (IAM). Who can manage the access keys of the AWS account root user?

A. IAM users in the same account that have been granted permission

B. IAM roles in any account that have been granted permission

C. IAM users and roles that have been granted permission

**D. The AWS account owner**

## 382. A company needs a managed NFS file system that the company can use with its AWS compute resources. Which AWS service or feature will meet these requirements?

A. Amazon Elastic Block Store (Amazon EBS)

B. AWS Storage Gateway Tape Gateway

C. Amazon S3 Glacier Flexible Retrieval

**D. Amazon Elastic File System (Amazon EFS)**

## 383. A company is migrating to the cloud. It wants to evaluate the configurations of virtual machines in its existing data center environment to ensure that it can size new Amazon EC2 instances accurately. The company wants to collect metrics, such as CPU, memory, and disk utilization, and it needs an inventory of what processes are running on each instance. The company would also like to monitor network connections to map communications between servers. Which would enable the collection of this data MOST cost effectively?

**A.** Use **AWS Application Discovery Service** and deploy the data collection agent to each virtual machine in the data center.

B. Configure the Amazon CloudWatch agent on all servers within the local environment and publish metrics to Amazon CloudWatch Logs.

C. Use AWS Application Discovery Service and enable agentless discovery in the existing virtualization environment.

D. Enable AWS Application Discovery Service in the AWS Management Console and configure the corporate firewall to allow scans over a VPN.

## 384. An application requires a database that offers consistent performance and latency that can be measured in single-digit milliseconds. Which AWS service meets these requirements?

**A. Amazon DynamoDB**

B. Amazon RDS

C. Amazon Redshift

D. Amazon EMR
