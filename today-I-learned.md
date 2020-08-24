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

**Links**
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
- Configure CloudWatch logs when EC2 CPU utilization exceeds the defined limit.
- Config cloud watch dashboard to monitor resource utilization using custom widget and metrics.
- Aws access control alerts using cloud watch , cloud trails and SNS.

Important links: [Metrics filer](https://amzn.to/3j3WXUj) , [Cloudtrail-policy-for-cloudwatch-logs](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-required-policy-for-cloudwatch-logs.html) .

![](RackMultipart20200822-4-4cyktl_html_237499165a11f2b9.gif)


************
**DAY 02 | 09/22/2020 | Saturday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Management &amp; Governances: Cloud Formation.

_Readings:_

- Read the [Cloud Formation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html) user guide.
- Read FAQs of [Cloud Formation](https://aws.amazon.com/cloudformation/faqs/).
- Read half [AWS well-architected white paper](https://d1.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf).

_Hands-on:_

- Build a basic infrastructure environment with an EC2 instance using cloud formation in JSON and YAML to understand its anatomy.
- Updating cloud formation stacks with direct updates and changesets.

Important links: [Templates snippets](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/CHAP_TemplateQuickRef.html)

![](RackMultipart20200822-4-4cyktl_html_237499165a11f2b9.gif)


************

**DAY 03 | 09/23/2020 | Sunday**

**Today&#39;s Progress:** Practicing AWS Management &amp; Governances: Cloud Formation.


_Readings:_

- Completed reading [AWS well-architected white paper](https://d1.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf).
- In-depth study of CloudFormation template anatomy.

Hands-on:

- Used three CloudFormation templates to build stacks and deploy DynamoDB tables, a VPC, and an S3 bucket.
- Deployed a web server using a cloud formation designer.
- Used condition function to determine if the VPC deployed by the template will be configured with default or dedicated tenancy.
- Deployed EC2 instance using cross-stack references.

![](RackMultipart20200823-4-16tdcwq_html_237499165a11f2b9.gif)



************

**DAY 04 | 09/24/2020 | Monday**

**Today&#39;s Progress:** Learning &amp; practicing AWS Security, Identity, &amp; Compliance services: IAM, Cognito, Amazon Inspector, Amazon Macie, WAF

_Readings:_

- Read FAQs of [Identity and Access Management](https://aws.amazon.com/iam/faqs/), [Cognito](https://aws.amazon.com/cognito/faqs/), [Amazon Inspector](https://aws.amazon.com/inspector/faqs/), [Amazon Macie](https://aws.amazon.com/macie/faq/), [WAF](https://aws.amazon.com/waf/faq/).

_Hands-on:_

- Played around with roles &amp; policies assigning, users &amp; groups management, created inline, managed &amp; custom policy, assign API access key, password policies,
- Created a new user with limited permissions to AWS resources.
- Created Cloud Formation template from existing resources using cloud former.

![](RackMultipart20200824-4-1wyb7w0_html_237499165a11f2b9.gif)
