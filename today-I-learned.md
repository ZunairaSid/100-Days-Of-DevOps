#
# **Today I Learned (TIL)**

**Disclaimer** : This timeline is tailored for the intermediate level and might not be suitable for everyone. Will be following [AWS Certified Solutions Architect – Associate (SAA-C02)](https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS-Certified-Solutions-Architect-Associate_Exam-Guide.pdf) , [AWS Certified Developer – Associate (DVA-C01)](https://d1.awsstatic.com/training-and-certification/docs-dev-associate/AWS-Certified-Developer-Associate_Exam-Guide.pdf)exam guides, [Docker Certified Associate Study Guide](https://training.mirantis.com/wp-content/uploads/2020/09/Docker-Study-Guide_v1.4_Aug-2020.pdf) and [CKA\_Curriculum](https://github.com/cncf/curriculum/blob/master/CKA_Curriculum_V1.18.pdf).</br>
_\* I will be using AWS service of Infrastructure as Code(IaC) **CloudFormation** for all AWS practice tasks._

************


**TIL Template :**

![](RackMultipart20200820-4-buben2_html_237499165a11f2b9.gif)
**DAY | DATE | DAY**

**Today&#39;s Progress:**

_Readings_</br>
_Hands-on_</br>
 _Quiz_</br>
_Whitepaper_</br>
_Important Links_</br>

![](RackMultipart20200820-4-buben2_html_237499165a11f2b9.gif)


************

**DAY 00 | 08/20/2020 | Thursday**

**Today&#39;s Progress:** Setting up everything.

- Set up an AWS account for hands-on.
- Read [AWS Certified Solutions Architect – Associate](https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS-Certified-Solutions-Architect-Associate_Exam-Guide.pdf), [AWS Certified Developer – Associate](https://d1.awsstatic.com/training-and-certification/docs-dev-associate/AWS-Certified-Developer-Associate_Exam-Guide.pdf) exam guide.
- Planned first 15 days readings and hands-on.
![](RackMultipart20200820-4-buben2_html_237499165a11f2b9.gif)


************
**DAY 01 | 08/21/2020 | Friday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Management &amp; Governances: _Cost &amp; Billing management, Cloud Trail, and Cloud Watch._

_Readings:_

- Read [AWS Cost and Billing management](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/billing-what-is.html), [Cloud Trail](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-user-guide.html),  [AWS Cloud Watch](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html) guide.
- Read FAQs of [Cloud Watch](https://aws.amazon.com/cloudwatch/faqs/), [Cloud Trail](https://aws.amazon.com/cloudtrail/faqs/), [Cloud Config](https://aws.amazon.com/config/faq/), [Cost Management](https://aws.amazon.com/aws-cost-management/faqs/).

_Hands-on:_

- Set up a [cost budget](https://aws.amazon.com/getting-started/hands-on/control-your-costs-free-tier-budgets/) and [billing alarm](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html) on AWS so I don&#39;t get a big AWS bill.
- Set up a CloudWatch Events alarm that triggers an SNS email notification on EC2 shut down.
- Configured CloudWatch logs when EC2 CPU utilization exceeds the defined limit.
- Configured cloud watch dashboard to monitor resource utilization using custom widget and metrics.
- Configured access control alerts using cloud watch , cloud trails and SNS.

Important links: [Metrics filer](https://amzn.to/3j3WXUj) , [Cloudtrail-policy-for-cloudwatch-logs](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-required-policy-for-cloudwatch-logs.html) .

![](RackMultipart20200822-4-4cyktl_html_237499165a11f2b9.gif)


************
**DAY 02 | 08/22/2020 | Saturday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Management &amp; Governances: _Cloud Formation._

_Readings:_

- Read the [Cloud Formation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html) user guide.
- Read FAQs of [Cloud Formation](https://aws.amazon.com/cloudformation/faqs/).
- Read half [AWS well-architected white paper](https://d1.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf).

_Hands-on:_

- Build a basic infrastructure environment with an EC2 instance using cloud formation in JSON and YAML to understand its anatomy.
- Updated cloud formation stacks with direct updates and changesets.

_Important links:_ [Templates snippets](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/CHAP_TemplateQuickRef.html),[CF deep-dive](https://github.com/natonic/CloudFormation-Deep-Dive)

![](RackMultipart20200822-4-4cyktl_html_237499165a11f2b9.gif)


************

**DAY 03 | 08/23/2020 | Sunday**

**Today&#39;s Progress:** Practicing AWS Management &amp; Governances: _Cloud Formation._


_Readings:_

- Completed reading [AWS well-architected white paper](https://d1.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf).
- Did in-depth study of CloudFormation template anatomy.

Hands-on:

- Used three CloudFormation templates to build stacks and deploy DynamoDB tables, a VPC, and an S3 bucket.
- Deployed a web server using a cloud formation designer.
- Used condition function to determine if the VPC deployed by the template will be configured with default or dedicated tenancy.
- Deployed EC2 instance using cross-stack references.

_Important links:_ [Sample templates](https://github.com/JulieElkinsAWS/CFtemplates),[AWS resource and property types](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-template-resource-type-ref.html)
![](RackMultipart20200823-4-16tdcwq_html_237499165a11f2b9.gif)



************

**DAY 04 | 08/24/2020 | Monday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Security, Identity, &amp; Compliance services: _IAM, Cognito, Amazon Inspector, Amazon Macie, WAF_

_Readings:_

- Read FAQs of [Identity and Access Management](https://aws.amazon.com/iam/faqs/), [Cognito](https://aws.amazon.com/cognito/faqs/), [Amazon Inspector](https://aws.amazon.com/inspector/faqs/), [Amazon Macie](https://aws.amazon.com/macie/faq/), [WAF](https://aws.amazon.com/waf/faq/).

_Hands-on:_

- Played around with roles &amp; policies assigning, users &amp; groups management. Created inline, managed &amp; custom policies.Assigned API access key, password policies to user.
- Created a new user with limited permissions to AWS resources.
- Created Cloud Formation template from existing resources using cloud former.

![](RackMultipart20200824-4-1wyb7w0_html_237499165a11f2b9.gif)


************

**DAY 05 | 08/25/2020 | Tuesday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Security, Identity, &amp; Compliance services: _AWS Directory Service, RAM, Single Sign-on_.

_Reading:_

- Read about [AWS Directory Service](https://docs.aws.amazon.com/directoryservice/latest/admin-guide/what_is.html), [AWS Resource Access Management(RAM)](https://docs.aws.amazon.com/ram/latest/userguide/what-is.html), [Single Sign-on](https://docs.aws.amazon.com/singlesignon/latest/userguide/what-is.html).
- FAQs of [AWS Directory service](https://aws.amazon.com/directoryservice/faqs/), [AWS Resource Access Manager](https://aws.amazon.com/ram/faqs/), [Single Sign-on](https://aws.amazon.com/single-sign-on/faqs/).

_Hands-on:_

  - Played around with Cognito.

![](RackMultipart20200825-4-1c7gn9o_html_237499165a11f2b9.gif)

************

**DAY 06 | 08/26/2020 | Wednesday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Networking &amp; Content Delivery: _VPC, Direct Connect, Global Accelerator, API gateway._

_Reading:_

- Read about [Nat gateway](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-gateway.html), [VPC flow logs](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html), [VPC endpoint](https://docs.aws.amazon.com/vpc/latest/userguide/endpoint-services-overview.html), [Direct connect](https://docs.aws.amazon.com/directconnect/latest/UserGuide/Welcome.html), [Network ACL](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html), [Global Accelerator](https://docs.aws.amazon.com/global-accelerator/latest/dg/what-is-global-accelerator.html), [API gateway](https://docs.aws.amazon.com/apigateway/?id=docs_gateway).
- Read FAQs of [VPC](https://aws.amazon.com/vpc/faqs/).
- Read [a comparison of NAT gateway and NAT instance](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-comparison.html).

_Hands-on:_

  - Built 3-tier network VPC from scratch. Built and connected VPC, multiple availability zones subnets, Internet Gateway, Route Tables, Nat gateway, &amp; Access Control List.
  - Created and connected VPC endpoint to S3 bucket.
  - Used Security groups and Network AccessControl lists to secure the different layers of a multi-tier network.

![](RackMultipart20200826-4-1ogakie_html_237499165a11f2b9.gif)


*******************
**DAY 07 | 08/27/2020 | Thursday**

**Today&#39;s Progress:** Practicing AWS Networking &amp; Content Delivery:

_Hands-on:_

  - Troubleshooted network connectivity.
  - Monitored VPC using a VPC flow log and cloud watch.
  - Deployed website canary with cloud formation.



*******************

**DAY 08 | 08/28/2020 | Friday**

**Today&#39;s Progress:** Practicing AWS Networking &amp; Content Delivery:

_Reading:_

- Read whitepaper [Overview of Security Processes](https://d0.awsstatic.com/whitepapers/aws-security-whitepaper.pdf)

_Hands-on:_

  - Enabled IPv6 on a VPC with a private Subnet and Egress-Only Internet Gateway and verified connectivity.

![](RackMultipart20200828-4-l23tc2_html_237499165a11f2b9.gif)


*************************

**DAY 09 | 08/29/2020 | Saturday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Networking &amp; Content Delivery: _Route53._

_Reading:_

- Read [Route 53](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/getting-started.html) and [DNS](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-dns.html) user guide.
- Read FAQs of [Route 53](https://aws.amazon.com/route53/faqs/).

_Hands-on:_

  - Registered DNS and Route53 routing policies.
  - Assigned FQDN (fully qualified domain name) to EC2 instance using route53.
  - Hosted static website with custom domain on AWS S3.
  - Managed DNS records with route53 for a highly available EC2 web server.
  - Configured hybrid DNS using Route 53 inbound and outbound resolver endpoints.

Important Links:

  - [Static website](https://github.com/linuxacademy/csa-a-2018/tree/master/penguinsite) ,Debugging ([nslookup](https://searchnetworking.techtarget.com/definition/nslookup) ,[Dig](https://www.a2hosting.com/kb/getting-started-guide/internet-and-networking/troubleshooting-dns-with-dig-and-nslookup) ,[dig + trace](https://ns1.com/blog/using-dig-trace) )

![](RackMultipart20200829-4-1bjiw0h_html_237499165a11f2b9.gif)



*************************

**DAY 10 | 08/30/2020 | Sunday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Networking &amp; Content Delivery: _CloudFront._

_Reading:_

- Read about [CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html).
- Read [FAQs of CloudFront](https://aws.amazon.com/cloudfront/faqs/).

_Hands-on:_

  - Set up CloudFront as HTTPS endpoint for S3.

![](RackMultipart20200830-4-1dxpjps_html_237499165a11f2b9.gif)


****************

**DAY 11 | 08/31/2020 | Monday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Storage: _S3 & S3 glacier._

_Reading:_

- Read about the [S3 security ,encryption , policies ,versioning, CORS ,lifecycle management,object lock ,select &amp; performance optimization.](https://docs.aws.amazon.com/AmazonS3/latest/dev/Welcome.html)
- Read about [S3 glacier.](https://docs.aws.amazon.com/amazonglacier/latest/dev/introduction.html)
- Read FAQs of [S3](https://aws.amazon.com/s3/faqs/) and [S3 glacier](https://aws.amazon.com/glacier/faqs/).

_Hands-on:_

  - Created an S3 bucket with lifecycle rules, CORS, and versioning.
  - Secured S3 bucket using IAM policies and bucket policies.
  - Shared S3 bucket across accounts.
  - Created an S3 bucket batch operation job.
  - Migrated BLOB data stored in a relational database table to S3.
  
 Important Links: [S3-cli](https://docs.aws.amazon.com/cli/latest/reference/s3/) ,[S3api-cli](https://docs.aws.amazon.com/cli/latest/reference/s3api/) , [Optimising-data](https://github.com/linuxacademy/Introduction-to-Optimizing-Data-Storage-in-AWS/tree/master/Lab)
![](RackMultipart20200831-4-izdwv9_html_237499165a11f2b9.gif)


**************************

**DAY 12 | 09/1/2020 | Tuesday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Storage: _EFS._

_Reading:_

- Read about [EBS](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AmazonEBS.html), [EBS snapshot](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html), and [EFS](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AmazonEFS.html),[Amazon Athena](https://docs.aws.amazon.com/athena/latest/ug/what-is.html).
- Read FAQs of[EFS](https://aws.amazon.com/efs/faq/),[EBS](https://aws.amazon.com/ebs/faqs/), and [Amazon Athena](https://aws.amazon.com/athena/faqs/).

_Hands-on:_

  - Set up a S3 static website using AWS CLI.
  - Integrated KMS custom keys with S3 objects.
  - Analyzed data in S3 with Amazon Athena.
  - Set up an 2 EC2 instances with an autoscaling group and resized EBS volumes for performance.

![](RackMultipart20200901-4-1cmcgrv_html_237499165a11f2b9.gif)


***************



![](RackMultipart20200902-4-1bs1qed_html_237499165a11f2b9.gif)

**DAY 13 | 09/2/2020 | Wednesday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Storage: _EFS._

_Reading:_

- Read about optimizing data storage in AWS and EFx.
- Read FAQs of [EC2](https://aws.amazon.com/ec2/faqs/).

_Hands-on:_

  - Troubleshoot EC2 network connectivity issues.
  - Created and validated connectivity for Amazon EC2 instance in a public and private subnet.

![](RackMultipart20200902-4-1bs1qed_html_237499165a11f2b9.gif)



**********************

**DAY 14 | 09/03/2020 | Thursday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Compute: _EC2._

_Hands-on:_

  - Performed backup and restore using AMIs and EBS.
  - Created a custom AMI.
  - Used EC2 image builder to create custom AMI.
  - Deployed Tomcat application dynamically.

![](RackMultipart20200903-4-17px9vy_html_237499165a11f2b9.gif)


******************

**DAY 15 | 09/04/2020 | Friday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Compute: _EC2._

_Reading:_

- Read about [differences in EBS , EFS , S3 and their use cases](https://www.missioncloud.com/blog/resource-amazon-ebs-vs-efs-vs-s3-picking-the-best-aws-storage-option-for-your-business).

_Hands-on:_

  - Used instance scheduler to shut down an EC2 instance.
  - Methods of choosing the right size EC2 instance for cost optimization.
  - Created a Windows EC2 instance and connected it through the remote desktop protocol(RDP).

![](RackMultipart20200904-4-y2ymby_html_237499165a11f2b9.gif)


**********************

**DAY 16 | 09/05/2020 | Saturday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Database : _RDS &amp; Redshift._

_Reading:_

- Read about the [Relational Database Service(RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)) &amp; [Redshift](https://docs.aws.amazon.com/redshift/latest/dg/welcome.html) .
- Read FAQs of [RDS](https://aws.amazon.com/rds/faqs/) &amp; [Redshift](https://aws.amazon.com/redshift/faqs/)

_Hands-on:_

  - Deployed RDS multi-AZ and Read Replica.
  - Created a private RDS database with NAT gateway, security groups, and accessed it using EC2 bastion host and IAM roles.
  - Restored RDS instance using snapshot.

![](RackMultipart20200905-4-33y0q8_html_237499165a11f2b9.gif)


**************************

**DAY 17 | 09/06/2020 | Sunday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Database: _DynamoDb._

_Reading:_

- Read about the [DynamoDb](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html).
- Read FAQs of [DynamoDb](https://aws.amazon.com/dynamodb/faqs/).

_Hands-on:_

  - Played around with DynamoDb table( indexing, data loading,write operations, using partition and sort keys, auditing access, using local and global secondary indexes to query for items in the table and their impact on performance and capacity unit usage).
  - Did on-demand and point-in-time recovery backups of dynamo DB.
  - Provision a DynamoDB Accelerator (DAX) on existing DynamoDB solution.
  - Read/ write to a DynamoDB table with the AWS Management Console, AWS CLI, and the Python Boto3 SDK.
  - Managed data relationships in dynamo DB(one-to-one, one-to-many, many-to-many, hierarchical data)
  - Implemented a simple application that accepts CSV files, converts them to DynamoDB-JSON, and puts the data into a table with the same name as the file.
  - Utilized write sharding to optimize data ingestion in Dynamodb.

![](RackMultipart20200906-4-iw97_html_237499165a11f2b9.gif)



*******************************

**DAY 18 | 09/07/2020 | Monday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Database: _Aurora &amp; Elasticache._

_Reading:_

- Read about [Aurora](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_AuroraOverview.html) and [Elasticache](https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/GettingStarted.html).
- Read FAQs of [Aurora](https://aws.amazon.com/rds/aurora/faqs/) and [Elasticache](https://aws.amazon.com/elasticache/faqs/).

_Hands-on:_

  - Created an Aurora database cluster and a database parameter group, along with a Custom Endpoint.
  - Used elasticache to improve DynamoDB performance.
  - Create an Aurora MySQL database cluster in private subnets using security groups.
  - Creating and Connecting to an Aurora Serverless Database via CLI.

![](RackMultipart20200907-4-1bdbrbz_html_237499165a11f2b9.gif)


*******************

**DAY 19 | 09/08/2020 | Tuesday**

**Today&#39;s Progress:** Learning &amp; practicing AWS HA Architecture: _Load Balancer, Health check &amp;: AWS Autoscaling._

_Reading:_

- Read about the [Load Balancer](https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/what-is-load-balancing.html), [Health Check](https://docs.aws.amazon.com/autoscaling/ec2/userguide/healthcheck.html),[Autoscaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html) &amp; l[aunch configuration](https://docs.aws.amazon.com/autoscaling/ec2/userguide/LaunchConfiguration.html).
- Read FAQs of [Load Balancer](https://aws.amazon.com/elasticloadbalancing/faqs/), and [Autoscaling](https://aws.amazon.com/ec2/autoscaling/faqs/).

_Hands-on:_

  - Ways of troubleshooting Elastic Load Balancer connectivity issues.
  - Set up an Application load balancer with an auto-scaling group, launch configuration, and route 53.
  - Deployed highly available web applications along with a highly available bastion host architecture using the RDS database from a snapshot, Security groups, Launch configurations, Auto Scaling groups, and Application Load Balancer.

![](RackMultipart20200908-4-1d14jcs_html_237499165a11f2b9.gif)


********************

**DAY 20 | 09/09/2020 | Wednesday**

**Today&#39;s Progress:** Learning AWS Compute: _Serverless application model &amp; Lambda_.

_Reading:_

- Read about [the Serverless application model(SAM)](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/sam-specification.html) and Lambda.
- Read FAQs of [the Lamba](https://aws.amazon.com/lambda/faqs/) and [Serverless application model(SAM)](https://aws.amazon.com/serverless/sam/faqs/#:~:text=The%20AWS%20Serverless%20Application%20Model%20(AWS%20SAM)%20is%20an%20open,and%20model%20it%20using%20YAML.).
- Read [a comparison](https://www.stratoscale.com/blog/dbaas/aurora-vs-rds/) of RDS MySQL and Aurora and their [use cases](https://www.percona.com/blog/2018/07/17/when-should-i-use-amazon-aurora-and-when-should-i-use-rds-mysql/).

![](RackMultipart20200909-4-1phiuvs_html_237499165a11f2b9.gif)


******************

**DAY 21 | 09/10/2020 | Thursday**

**Today&#39;s Progress:** Practicing AWS Compute: _Lambda_.

_Hands-on:_

  - Created simple lambda function (Lambda Console Function, Code Execution, Roles, Test, Events, Execution, Results )
  - Created an EC2 with lambda &amp; shut it down using basic lambda function.

![](RackMultipart20200910-4-y4p38i_html_237499165a11f2b9.gif)


********************

**DAY 22 | 09/11/2020 | Friday**

**Today&#39;s Progress:** Took the following quizzes on [AcloudGuru](http://acloudguru.com/).

_Quizzes:_

  - EC2 , IAM ,S3 ,Database ,Route53 ,VPC ,HA architecture , KMS and Encryption , Monitoring.

![](RackMultipart20200911-4-1vjb1ai_html_237499165a11f2b9.gif)


********************

**DAY 23 | 09/12/2020 | Saturday**

**Today&#39;s Progress:** Took  AWS certified solution architect associate practice exam on [AcloudGuru](http://acloudguru.com/).



![](RackMultipart20200911-4-1vjb1ai_html_237499165a11f2b9.gif)

******************


**DAY 24 | 09/13/2020 | Sunday**

**Today&#39;s Progress:** Took  S3 master class  on [AcloudGuru](http://acloudguru.com/) (1/2).



![](RackMultipart20200911-4-1vjb1ai_html_237499165a11f2b9.gif)



******************

**DAY 25 | 09/14/2020 | Monday**

**Today&#39;s Progress:** Completed  S3 master class  on [AcloudGuru](http://acloudguru.com/) .



![](RackMultipart20200911-4-1vjb1ai_html_237499165a11f2b9.gif)



******************

**DAY 26 | 09/15/2020 | Tuesday**

**Today&#39;s Progress:** Reading and Practicing _AWS Database Migration Service(DMS) & Service Caching strategies on AWS_

_Reading:_

- Read about Database Migration Service(DMS) and Service Caching strategies on AWS
- Read FAQs of [Database Migration Service(DMS)](https://aws.amazon.com/dms/faqs/)

_Hands-on:_

  - Used DMS to migrate a database from an EC2 server to RDS for cost optimization.
  - Used AWS DMS to migrate data to an aurora database.
  - Migrated a normalized relational database to an Amazon DynamoDB table.

![](RackMultipart20200915-4-vugtmz_html_237499165a11f2b9.gif)


***********************

**DAY 27 | 09/16/2020 | Wednesday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Application: _Simple Notification Service(SNS)_

_Reading:_

- Read the Simple Notification Service(SNS) user guide.
- Read FAQs of [Simple Notification Service(SWS](https://aws.amazon.com/ko/sns/faqs/)).

_Hands-on:_

  - Configure an S3 bucket to trigger AWS Simple Notification Service notifications whenever an object is added to an S3 bucket.

![](RackMultipart20200916-4-1et6uus_html_237499165a11f2b9.gif)


*****************

**DAY 28 | 09/17/2020 | Thursday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Application: _Simple Workflow Service(SWS)._

_Reading:_

- Read FAQs of [Simple Workflow Service(SWS)](https://aws.amazon.com/swf/faqs/).

_Hands-on:_

  - Created and subscribed to SNS topics using multiple endpoints (SMS, EMAIL &amp; LAMBDA).

![](RackMultipart20200917-4-1mf215a_html_237499165a11f2b9.gif)

***********

**DAY 29 | 09/18/2020 | Friday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Application: _Simple Queue Service(SQS)._

_Reading:_

- Read about the [Simple Queue Service(SQS)](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html).
- Read FAQs of [Simple Queue Service(SQS)](https://aws.amazon.com/sqs/faqs/).

_Hands-on:_

  - Creating and subscribing to AWS SQS topics.
  - Create and interact with first-in-first-out (FIFO) SQS queues.
  - Working with SQS standard queue, send messages to the queue, used multiple consumers to process queue data, set queue attributes, and consume messages.

![](RackMultipart20200918-4-1epyjh9_html_237499165a11f2b9.gif)


***********

**DAY 30 | 09/19/2020 | Saturday**

**Today&#39;s Progress:** Took overview of AWS services: AWS Shield, System manager parameter store , AWS WAF ,AWs Datasync , Snowball , Storage gateway , Spot instance and spot fleets , global accelerator , private links , Cloud HSM ,VPN cloudhub

![](RackMultipart20200919-4-o83kxg_html_237499165a11f2b9.gif)


************

**DAY 31 | 09/20/2020 | Sunday**

**Today&#39;s Progress:** Practicing AWS Application: Step Functions

_Hands-on:_

  - Used AWS Step Functions to Manage a Long-Running Process.
  - Performed Parallel Execution in AWS Step Functions.

![](RackMultipart20200920-4-slk4ou_html_237499165a11f2b9.gif)


*********
**DAY 32 | 09/21/2020 | Monday**

**Today&#39;s Progress:**

_Reading:_

- Read whitepaper [Blue/Green Deployments on AWS](https://d1.awsstatic.com/whitepapers/AWS_Blue_Green_Deployments.pdf) (half)

![](RackMultipart20200921-4-1f7a32r_html_237499165a11f2b9.gif)


*********
**DAY 33 | 09/22/2020 | Tuesday**

**Today&#39;s Progress:**

_Reading:_

- Completed reading of whitepaper [Blue/Green Deployments on AWS](https://d1.awsstatic.com/whitepapers/AWS_Blue_Green_Deployments.pdf) 

![](RackMultipart20200921-4-1f7a32r_html_237499165a11f2b9.gif)


*********
**DAY 34 | 09/23/2020 | Wednesday**

**Today&#39;s Progress:**

_Reading:_

- Read whitepaper [ Implementing Microservices on AWS](https://d1.awsstatic.com/whitepapers/microservices-on-aws.pdf) 

![](RackMultipart20200921-4-1f7a32r_html_237499165a11f2b9.gif)


*********
**DAY 35 | 09/24/2020 | Thursday**

**Today&#39;s Progress:**

_Reading:_

- Read whitepaper [Practicing Continuous Integration and Continuous Delivery on AWS ](https://d1.awsstatic.com/whitepapers/DevOps/practicing-continuous-integration-continuous-delivery-on-AWS.pdf) (half)

![](RackMultipart20200921-4-1f7a32r_html_237499165a11f2b9.gif)


*********
**DAY 36 | 09/25/2020 | Friday**

**Today&#39;s Progress:**

_Reading:_

- Completed reading of whitepaper [Practicing Continuous Integration and Continuous Delivery on AWS ](https://d1.awsstatic.com/whitepapers/DevOps/practicing-continuous-integration-continuous-delivery-on-AWS.pdf)

![](RackMultipart20200921-4-1f7a32r_html_237499165a11f2b9.gif)


*********

**DAY 36 | 09/26/2020 | Saturday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Developer tools: Codebuild , CodeCommit, CodeDeploy.

_Reading:_

- Read FAQs of [Codebuild](https://aws.amazon.com/codebuild/faqs/), [CodeCommit](https://aws.amazon.com/codecommit/faqs/).

_Hands-on:_

- Set up a source code repository with AWS CodeCommit and created an S3 bucket to host static web applications.
- Created code commit to trigger an email notification.
- Worked with CodeCommit from the CLI.
- Tracked CodeCommit commit metadata using dynamo DB.
- Rolling Updates to a Highly Distributed Web Application with AWS CodeDeploy.

![](RackMultipart20200926-4-nynuh5_html_237499165a11f2b9.gif)


*******
**DAY 38 | 09/27/2020 | Sunday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Developer tools : Codebuild , CodeCommit, CodeDeploy , CodePipeline ,Cloud9 ,X-ray.

_Reading:_

- Read FAQs of [CodePipeline](https://aws.amazon.com/codepipeline/faqs/) ,[Cloud9](https://aws.amazon.com/cloud9/faqs/) ,[X-ray](https://aws.amazon.com/xray/faqs/).

_Hands-on:_

- Created and use a Continuous Integration/Continuous Delivery pipeline to deploy a new version of the website automatically.
- Set up AWS CodePipeline to continuously deploy our web application to S3.
- Created code commit to trigger an email notification.

![](RackMultipart20200927-4-mtsyvk_html_237499165a11f2b9.gif)



**********

**DAY 39 | 09/28/2020 | Monday**

**Today&#39;s Progress:** Practicing AWS Developer tools : Code Star

_Reading:_

- Read FAQs of [CodeStar.](https://aws.amazon.com/codestar/faqs/)

_Hands-on:_

- Used AWS CodeStar, a frontend tool that will automatically configure AWS CodeCommit, AWS CodeBuild, AWS CodeDeploy, and AWS CodePipeline.
- Deployed custom code with a CI/CD Pipeline using AWS CodeStar.

![](RackMultipart20200928-4-o2d1te_html_237499165a11f2b9.gif)



**********

**DAY 40 | 09/29/2020 | Tuesday**

**Today&#39;s Progress:** Practicing AWS Developer tools:

_Hands-on:_

- Set up an AWS CodePipeline with a manual approval.
- Set up CodePipeline for continuous deployment to Elastic Beanstalk
- Monitored AWS CodePipeline changes through AWS CloudWatch events rules.


![](RackMultipart20200928-4-o2d1te_html_237499165a11f2b9.gif)


**********

**DAY 41 | 09/30/2020 | Wednesday**

**Today&#39;s Progress:**  Learning &amp; practicing Docker 

_Reading:_

- Read about  [Docker architecture & Docker engine.](https://docs.docker.com/get-started/overview/)

_Hands-on:_

- Installed docker & set up docker hub account.
- Shared image on dockerhub.
- Deployed static website to container.


![](RackMultipart20200928-4-o2d1te_html_237499165a11f2b9.gif)

**********

**DAY 42 | 10/01/2020 |Thursday**

**Today&#39;s Progress:** Learning &amp; practicing Docker

_Reading:_

- Read about  Docker image and containers.

_Hands-on:_

- Build container image.
- Dockerized node.js application


**********

**DAY 43 | 10/02/2020 | Friday**

**Today&#39;s Progress:** Learning &amp; practicing Docker

_Reading:_

- Read about  Docker file.

_Hands-on:_

- Created images using docker file.
- Tagged and pushed images to dockerhub


*********


**DAY 44 | 10/03/2020 | Saturday**

**Today&#39;s Progress:** Learning &amp; practicing Docker Volume

_Reading:_

- Read about  Docker Storage(Volume & bindmount).

_Hands-on:_

- Created data container.
- Used volume for persistent storage with container.



*********

**DAY 45 | 10/04/2020 | Sunday**

**Today&#39;s Progress:** Learning &amp; practicing Docker Optimization 

_Reading:_

- Read about Docker Optimization.

_Hands-on:_

- Optimized Docker Build with OnBuild.
- Optimized Docker Build with ignore file.



*********

**DAY 46 | 10/05/2020 | Monday**

**Today&#39;s Progress:** Learning &amp; practicing Docker Network 

_Reading:_

- Read about Docker Network and network types.

_Hands-on:_

- Deployed container with network bridge for secure communication .
- Created a linked network between application & database container.



*********

**DAY 47 | 10/06/2020 | Tuesday**

**Today&#39;s Progress:** Learning &amp; practicing Docker File 

_Reading:_

- Read about Docker File and instructions.

_Hands-on:_

- Created image using docker file using multi stage build. 
- Tagged and pushed the image to docekr hub.



*********

**DAY 48 | 10/07/2020 | Wednesday**

**Today&#39;s Progress:** Learning &amp; practicing Container management 

_Reading:_

- Read about Container management ways.

_Hands-on:_

- Managed docker using portainer. 
- Used Watchtower to keep container up to date.



*********
**DAY 49 | 10/08/2020 |Thursday**

**Today&#39;s Progress:** Learning &amp; practicing Managing images 

_Reading:_

- Read about Image management ways .

_Hands-on:_

- Buid a private docker registry.
- Looked into container logging ,adding metadata and tags.
- Buid a load balancing container.

*********
**DAY 50 | 10/09/2020 |Friday**

**Today&#39;s Progress:** Learning &amp; practicing Docker compose.

_Reading:_

- Read about Docker compose.

_Hands-on:_

- Building a microservice with docker compose. 



*********
**DAY 51 | 10/10/2020 |Saturday**

**Today&#39;s Progress:** Learning &amp; practicing Jenkins.

_Reading:_

- Read about CI/CD & test driven development.

_Hands-on:_

- Installed jenkins on ubuntu.
 - Explored the jenkins UI and system configuration.



*********
**DAY 52 | 10/11/2020 |Sunday**

**Today&#39;s Progress:** Learning &amp; practicing Jenkins.

_Reading:_

- Read about Jenkins plug-ins.

_Hands-on:_

- Installed jenkins on ubuntu.
 - Explored managing, updating &adding pug-ins.



*********
**DAY 53 | 10/12/2020 |Monday**

**Today&#39;s Progress:** Learning &amp; practicing Jenkins.

_Reading:_

- Read about Jenkins jobs.

_Hands-on:_

- Build a free style job .
- Added parameters and notifications in free style job .
 

*********
**DAY 54 | 10/13/2020 |Tuesday**

**Today&#39;s Progress:** Practicing Jenkins.

_Hands-on:_

- Set up a build remote agent.
- Distributed workload between build agents.
- Monitored a build remote agent.
 



*********

**DAY 55 | 10/14/2020 |Wednesday**

**Today&#39;s Progress:** Learning &amp; practicing Jenkins.


_Reading:_

- Read about Webhooks.

_Hands-on:_

- Build a free style job that used Git and ant installation.
 

*********
**DAY 56 | 10/15/2020 |Thursday**

**Today&#39;s Progress:** Learning &amp; practicing Jenkins.


_Reading:_

- Read about Jenkins upstream , downstream and triggers.

_Hands-on:_

- Linked jobs in jenkins and produced artifacts.
 
*********
**DAY 57 | 10/16/2020 |Friday**

**Today&#39;s Progress:** Learning &amp; practicing Jenkins.


_Reading:_

- Read about pipelines.

_Hands-on:_

- Created a pipeline job.
- Created a pipeline job using blue ocean editor.
 
*********
**DAY 58 | 10/17/2020 |Saturday**

**Today&#39;s Progress:** Learning &amp; practicing Jenkins pipelines.


_Reading:_

- Read about differences in scripted and declarative pipelines.

_Hands-on:_

- Created a scripted pipeline job.
- Created a declarative pipeline job.



 *********

**DAY 59 | 10/18/2020 |Sunday**

**Today&#39;s Progress:** Learning &amp; practicing Jenkins pipeline.


_Reading:_

- Read about pipelines triggers.

_Hands-on:_

- Created a multibranch pipeline job.


*********

**DAY 60 | 10/19/2020 |Monday**

**Today&#39;s Progress:** Learning &amp; practicing Jenkins pipeline.


_Reading:_

- Read about global libraries.

_Hands-on:_

- Used Jenkins build agents for carrying out different parts of a Jenkins job.
 

*********

**DAY 61 | 10/20/2020 |Tuesday**

**Today&#39;s Progress:** Learning &amp; practicing Jenkins pipeline.


_Reading:_

- Read about docker in pipeline.

_Hands-on:_

- Created a Jenkins Pipeline job to deploy Docker container with an application.
 
**********

**DAY 62 | 10/21/2020 | Wednesday**

**Today&#39;s Progress:** Reading &amp; practicing Kubernetes pod&#39;s containers.

_Reading:_

- Read about [containers](https://kubernetes.io/docs/concepts/containers/), [container patterns](https://kubernetes.io/blog/2015/06/the-distributed-system-toolkit-patterns/), &amp; [init container.](https://kubernetes.io/docs/concepts/workloads/pods/init-containers/)

_Hands-on:_

- [Assigned memory resources to containers in a pod](https://kubernetes.io/docs/tasks/configure-pod-container/assign-memory-resource/).
- [Assigned CPU resources to containers in a pod.](https://kubernetes.io/docs/tasks/configure-pod-container/assign-cpu-resource/)
- [Created a multi-container pod.](https://kubernetes.io/docs/tasks/configure-pod-container/quality-service-pod/#create-a-pod-that-has-two-containers)
- [Assign Extended Resources to a Container](https://kubernetes.io/docs/tasks/configure-pod-container/extended-resource/)
- Created a multi-container pod using the ambassador mode.

![](RackMultipart20201021-4-hfjqhi_html_237499165a11f2b9.gif)


**********

**DAY 63 | 10/22/2020 | Thursday**

**Today&#39;s Progress:** Reading &amp; practicing Kubernetes Pods.

_Reading:_

- Read about [pods, pod storage, pod network, static pod](https://kubernetes.io/docs/concepts/workloads/pods/) &amp; [pod lifecycle](https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle/).

_Hands-on:_

- [Created a static pod.](https://kubernetes.io/docs/tasks/configure-pod-container/static-pod/)
- Created Kubernetes Nginx pod using the YAML file.
- Created a multi-container pod using the ambassador mode.
- [Share Process Namespace between Containers in a Pod.](https://kubernetes.io/docs/tasks/configure-pod-container/share-process-namespace/)

![](RackMultipart20201023-4-ewgchu_html_237499165a11f2b9.gif)



**********

**DAY 64 | 10/23/2020 | Friday**

**Today&#39;s Progress:** Reading &amp; practicing Kubernetes Workloads: Deployments.

_Reading:_

- Read about [Deployments](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/), rollback, rollout history, rolling update, Canary Deployment
- Read about the [deployment YAML file](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/#writing-a-deployment-spec).

_Hands-on:_

- Deployed a microservice in Kubernetes.
- Rollbacked the microservices deployment.
- Performed a rolling update of an application.

![](RackMultipart20201023-4-ewgchu_html_237499165a11f2b9.gif)



**********


**DAY 65 | 10/24/2020 | Saturday**

**Today&#39;s Progress:** Reading &amp; practicing Kubernetes Workloads: ReplicaSet, StatefulSet, DaemonSet.

_Reading:_

- Read about [ReplicaSet](https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/), [Statefulset](https://kubernetes.io/docs/concepts/workloads/controllers/statefulset/), [DaemonSet](https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/)
- Read about the [ReplicaSet](https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/#writing-a-replicaset-manifest), [DaemonSet](https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/#writing-a-replicaset-manifest), and Statefulset manifest file.

_Hands-on:_

- [Created StatefulSet](https://kubernetes.io/docs/tutorials/stateful-application/basic-stateful-set/#creating-a-statefulset), [Replicaset](https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/#example) &amp; [DaemonSet](https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/#example)
- [Deployed Cassandra with a StatefulSet](https://kubernetes.io/docs/tutorials/stateful-application/cassandra/)
- [Run a Replicated Stateful Application](https://kubernetes.io/docs/tasks/run-application/run-replicated-stateful-application/)

![](RackMultipart20201025-4-19d7uw7_html_237499165a11f2b9.gif)

**********


**DAY 66 | 10/25/2020 | Sunday**

**Today&#39;s Progress:** Reading &amp; practicing Kubernetes Workloads: Jobs &amp; CronJob.

_Reading:_

- Read about [Job](https://kubernetes.io/docs/concepts/workloads/controllers/job/), [Job patterns](https://kubernetes.io/docs/concepts/workloads/controllers/job/#job-patterns), [CronJobs](https://kubernetes.io/docs/concepts/workloads/controllers/cron-jobs/)
- Read about the [job](https://kubernetes.io/docs/concepts/workloads/controllers/job/#running-an-example-job), [cronjob](https://kubernetes.io/docs/concepts/workloads/controllers/cron-jobs/#example) manifest file.

_Hands-on:_

- [Run a job](https://kubernetes.io/docs/concepts/workloads/controllers/job/#running-an-example-job) &amp; cronjob.
- [Clean up a finished job](https://kubernetes.io/docs/concepts/workloads/controllers/job/#clean-up-finished-jobs-automatically).

![](RackMultipart20201025-4-19d7uw7_html_237499165a11f2b9.gif)



**********
