#
# **Today I Learned (TIL)**

**Disclaimer** : This timeline is tailored for the intermediate level and might not be suitable for everyone. Will be following [AWS Certified Solutions Architect – Associate (SAA-C02)](https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS-Certified-Solutions-Architect-Associate_Exam-Guide.pdf) , [AWS Certified Developer – Associate (DVA-C01)](https://d1.awsstatic.com/training-and-certification/docs-dev-associate/AWS-Certified-Developer-Associate_Exam-Guide.pdf)exam guides, and [CKA\_Curriculum](https://github.com/cncf/curriculum/blob/master/CKA_Curriculum_V1.18.pdf).</br>
_\* I will be using AWS service of Infrastructure as Code(IaC) **CloudFormation** for all practice tasks._

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

**DAY 00 | 09/20/2020 | Thursday**

**Today&#39;s Progress:** Setting up everything.

- Set up an AWS account for hands-on.
- Read [AWS Certified Solutions Architect – Associate](https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS-Certified-Solutions-Architect-Associate_Exam-Guide.pdf), [AWS Certified Developer – Associate](https://d1.awsstatic.com/training-and-certification/docs-dev-associate/AWS-Certified-Developer-Associate_Exam-Guide.pdf) exam guide.
- Planned first 15 days readings and hands-on.
![](RackMultipart20200820-4-buben2_html_237499165a11f2b9.gif)


************
**DAY 01 | 09/21/2020 | Friday**

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
**DAY 02 | 09/22/2020 | Saturday**

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

**DAY 03 | 09/23/2020 | Sunday**

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

**DAY 04 | 09/24/2020 | Monday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Security, Identity, &amp; Compliance services: _IAM, Cognito, Amazon Inspector, Amazon Macie, WAF_

_Readings:_

- Read FAQs of [Identity and Access Management](https://aws.amazon.com/iam/faqs/), [Cognito](https://aws.amazon.com/cognito/faqs/), [Amazon Inspector](https://aws.amazon.com/inspector/faqs/), [Amazon Macie](https://aws.amazon.com/macie/faq/), [WAF](https://aws.amazon.com/waf/faq/).

_Hands-on:_

- Played around with roles &amp; policies assigning, users &amp; groups management, created inline, managed &amp; custom policy, assign API access key, password policies,
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

**DAY 06 | 09/26/2020 | Wednesday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Networking &amp; Content Delivery: _VPC, Direct Connect, Global Accelerator, API gateway._

_Reading:_

- Read about [Nat gateway](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-gateway.html), [VPC flow logs](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html), [VPC endpoint](https://docs.aws.amazon.com/vpc/latest/userguide/endpoint-services-overview.html), [Direct connect](https://docs.aws.amazon.com/directconnect/latest/UserGuide/Welcome.html), [Network ACL](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html), [Global Accelerator](https://docs.aws.amazon.com/global-accelerator/latest/dg/what-is-global-accelerator.html), [API gateway](https://docs.aws.amazon.com/apigateway/?id=docs_gateway).
- Read FAQs of [VPC](https://aws.amazon.com/vpc/faqs/).
- Read [a comparison of NAT gateway and NAT instance](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-comparison.html).

_Hands-on:_

  - Built 3-tier network VPC from scratch. Built and connected VPC, multiple availability zones subnets, Internet Gateway, Route Tables, Nat gateway, &amp; Access Control List.
  - Created and connected VPC endpoint and S3 bucket.
  - Used Security groups and Network AccessControl lists to secure the different layers of a multi-tier to secure network.

![](RackMultipart20200826-4-1ogakie_html_237499165a11f2b9.gif)


*******************
**DAY 07 | 09/27/2020 | Thursday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Networking &amp; Content Delivery:

_Hands-on:_

  - Troubleshooted network connectivity.
  - Monitored VPC using a VPC flow log.
  - Deployed website canary with cloud formation.



*******************

**DAY 08 | 09/28/2020 | Friday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Networking &amp; Content Delivery:

_Reading:_

- Read whitepaper [Overview of Security Processes](https://d0.awsstatic.com/whitepapers/aws-security-whitepaper.pdf)

_Hands-on:_

  - Enabled IPv6 on a VPC with a private Subnet and Egress-Only Internet Gateway and verified connectivity.

![](RackMultipart20200828-4-l23tc2_html_237499165a11f2b9.gif)


*************************

**DAY 09 | 09/29/2020 | Saturday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Networking &amp; Content Delivery: Route53.

_Reading:_

- Read [Route 53](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/getting-started.html) and[DNS](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-dns.html) user guide.
- Read FAQs of [Route 53](https://aws.amazon.com/route53/faqs/).

_Hands-on:_

  - Registered DNS, Route53 routing policies.
  - Assigned FQDN (fully qualified domain name) to EC2 instance using route53.
  - Hosted static website with custom domain on AWS S3.
  - Managed DNS records with route53 for a highly available web server.
  - Configured hybrid DNS using Route 53 inbound and outbound resolver endpoints.

Important Links:

  - [Static website](https://github.com/linuxacademy/csa-a-2018/tree/master/penguinsite) ,Debugging ([nslookup](https://searchnetworking.techtarget.com/definition/nslookup) ,[Dig](https://www.a2hosting.com/kb/getting-started-guide/internet-and-networking/troubleshooting-dns-with-dig-and-nslookup) ,[dig + trace](https://ns1.com/blog/using-dig-trace) )

![](RackMultipart20200829-4-1bjiw0h_html_237499165a11f2b9.gif)



*************************

**DAY 10 | 09/30/2020 | Sunday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Networking &amp; Content Delivery: CloudFront.
_Reading:_

- Read about [CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html).
- Read[FAQs of CloudFront](https://aws.amazon.com/cloudfront/faqs/).

_Hands-on:_

  - Set up CloudFront as HTTPS endpoint for S3.

![](RackMultipart20200830-4-1dxpjps_html_237499165a11f2b9.gif)


****************

**DAY 11 | 09/31/2020 | Monday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Storage: S3 ,S3 glacier.

_Reading:_

- Read about the [S3 security ,encryption , policies ,versioning, CORS ,lifecycle management,object lock ,select &amp; performance optimization.](https://docs.aws.amazon.com/AmazonS3/latest/dev/Welcome.html)
- Read about [S3 glacier.](https://docs.aws.amazon.com/amazonglacier/latest/dev/introduction.html)
- Read FAQs of[S3](https://aws.amazon.com/s3/faqs/) and [S3 glacier](https://aws.amazon.com/glacier/faqs/).

_Hands-on:_

  - Created an S3 bucket with lifecycle rules, CORS, and versioning.
  - Secured S3 bucket using IAM policies and bucket policies.
  - Shared S3 bucket across accounts.
  - Created an S3 bucket batch operation job.
  - Migrated BLOB data stored in a relational database table to S3.
  
 Important Links: [S3-cli](https://docs.aws.amazon.com/cli/latest/reference/s3/) ,[S3api-cli](https://docs.aws.amazon.com/cli/latest/reference/s3api/) , [Optimising-data](https://github.com/linuxacademy/Introduction-to-Optimizing-Data-Storage-in-AWS/tree/master/Lab)
![](RackMultipart20200831-4-izdwv9_html_237499165a11f2b9.gif)


**************************

**DAY 12 | 10/1/2020 | Tuesday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Storage: EFS.

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

**DAY 13 | 10/2/2020 | Wednesday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Storage: EFS.

_Reading:_

- Read about optimizing data storage in AWS and EFx.
- Read FAQs of[EC2](https://aws.amazon.com/ec2/faqs/).

_Hands-on:_

  - Troubleshoot EC2 network connectivity issues.
  - Created and validated connectivity for Amazon EC2 instance in a public and private subnet.

![](RackMultipart20200902-4-1bs1qed_html_237499165a11f2b9.gif)



**********************
