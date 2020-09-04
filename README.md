**#100DaysOfDevops** is a challenge to read official documentations, FAQs and white papers of AWS different services and do hands-on practice of AWS services , Docker ,Kubernetes and Jenkins with the aim to get AWS Solution Architect Associate , AWS Developer Associate &amp; Kubernetes Administrator certification.

**How am I taking this challenge?***

I will dedicate at least 3 hours from my day for this challenge and will share my progress of what I’ve learned during that day in [today-I-learned.md](https://github.com/ZunairaSid/100-Days-Of-DevOps/blob/master/today-I-learned.md)


**Tentative roadmap :**

:curly_loop:   AWS</br>
:curly_loop: Bash Scripting</br>
:curly_loop: Docker</br>
:curly_loop: Kubernetes</br>
:curly_loop: Jenkins</br>

**White Papers**

- [x] [AWS Well Architecture Framework](https://bit.ly/3aAfe8J)<br>
- [ ] [AWS Blue-Green Deployment](https://bit.ly/2Q2r563)
- [x] [Overview of Security Processes](https://d1.awsstatic.com/whitepapers/Security/Intro_to_AWS_Security.pdf?did=wp_card&trk=wp_card)<br>
- [ ] [Implementing](https://bit.ly/2CHErSo)[Microservices on AWS](https://bit.ly/2CHErSo)
- [ ] [Practicing](https://d1.awsstatic.com/whitepapers/DevOps/practicing-continuous-integration-continuous-delivery-on-AWS.pdf)[CI/CD on AWS](https://d1.awsstatic.com/whitepapers/DevOps/practicing-continuous-integration-continuous-delivery-on-AWS.pdf)

**AWS hands-on task**


- [x] Set up a cost budget and billing alarm.<br>
- [x] Configure CloudWatch alarm when EC2 CPU utilization exceeds the defined limit.<br>
- [x] Build a 3-tier network from scratch using VPC,subnets, NACL,Internet gateway ,NAT gateway and route tables. <br>
- [ ] Create an IAM Role and configure an EC2 Instance for AWS Systems Manager.<br>
- [x] Set up CloudFront as HTTPS endpoint for S3.<br>
- [x] Create a Multi-Subnet network with secure access to private servers with outbound internet access using VPC , private &amp; public subnets ,NAT gateway &amp; Internet Gateway, and Bastion Host.<br>
- [x] Create VPC endpoints and attach it to S3 bucket.<br>
- [x] Enabled IPv6 on a VPC with a Private Subnet and Egress-Only Internet Gateway and verify connectivity.<br>
- [x] Monitor VPC using VPC flow logs and Amazon Athena<br>
- [x] Manage data in S3 with versioning , CORS and Lifecycle Rules.<br>
- [x] Secure S3 bucket policies using IAM policies.<br>
- [x] Share S3 bucket across accounts.<br>
- [x] Set up a S3 static website using AWS CLI.<br>
- [x] Integrate KMS custom keys with S3 objects.<br>
- [x] Analyze data in S3 with Amazon Athena.<br>
- [x] Create an S3 bucket batch operation job.<br>
- [x] Migrate BLOB data stored in a relational database table to S3.<br>
- [x] Create an EC2 work station and give limited permission to a IAM user to use it.<br>
- [ ] Build Fault Tolerance Website.
- [x] Create a custom AMI.
- [ ] Create a status website using EC2, S3 ,IAM roles and bash script.
- [x] Deploy Tomcat application dynamically.</br>
- [x] Use the OWASP Zed Attack Proxy (ZAP) to do a penetration test on a sample application.</br>
- [x] Use the OWASP Zed Attack Proxy (ZAP) to do a penetration test on a sample application.</br>
- [x] Use AWS scheduler to shut down EC2 instances.<br>
- [x] Build a static website with a custom domain, using Route 53 Alias record sets and S3 bucket.<br>
- [x] Build a website from two EC2 instances, and route traffic using an Application Load Balancer. Create and manage DNS records inside of Route 53.<br>
- [ ] Troubleshoot elastic load balancer connectivity.
- [x] Configured hybrid DNS using Route 53 inbound and outbound resolver endpoints.<br>
- [x] Troubleshoot  network connectivity connectivity in 3-tier network.<br>
- [x] Troubleshoot EC2 network connectivity issues.<br>
- [x] Validate connectivity for Amazon EC2 instance in a public and private subnet.<br>
- [ ] Manage the deployment of EC2 instances in an Auto Scaling Group using Lifecycle Hooks.
- [ ] Backup and restore from dynamoDB.
- [x] Backup and restore data using AMIs and EBS.<br>
- [ ] Use the Database Migrations Service (DMS) to migrate a database from an EC2 server to RDS.
- [ ] Process DynamoDB stream using lambda.
- [x] Set up an 2 EC2 instances with an autoscaling group and resized EBS volumes for performance.<br>
- [ ] Migrate data from a Relational Database to DynamoDB.
- [ ] Use Data Pipeline to copy DynamoDB data to an S3 bucket.
- [ ] Choose the right size EC2 instance for cost optimization.<br>
- [x] Create and configure a CloudTrail trail and a CloudWatch Logs & alarms ,in order to set up access email alerts for an S3 bucket write/read.<br>
- [x] Created a Windows EC2 instance and connected it through the remote desktop protocol(RDP).<br>
- [ ] Set AWS CloudWatch Logs and Incident Response using Elasticsearch ,Route 53 ,VPC Flow Logs,Elasticsearch Service and Kibana.
- [x] Configure CloudWatch alarm with SNS and send email on EC2 shut down.<br>
- [x] Config cloud watch dashboard to monitor resource utilization using custom widget and metrics.<br>
- [ ] Build CI/CD pipeline using AWS Pipeline to deploy static website on s3.
- [ ] Build a simple serverless website with route53 , API gateway and lambda.
- [ ] Create Serverless web page with API gateway and lambda .
- [ ] Create a reminder serverless application using a static website , hosted on S3 , using AWS Step Functions, API Gateway, AWS Lambda.
- [ ] Trigger a Lambda function using SQS and dynamoDB.
- [x] See logs using cloudwatch &amp; create billing alarms. <br>
- [x] Deploy a website canary using cloudformation. <br>
- [x] Deploy a basic infrastructure using CloudFormation Templates.<br>
- [x] Update cloud formation stacks with direct updates and changesets.<br>
- [ ] Roll updates to a highly distributed web application with AWS CodeDeploy.
- [ ] Implement AWS CodePipeline to deploy AWS infrastructure through AWS CloudFormation.
- [x] Created Cloud Formation template from existing resources using cloud former.<br>
- [x] Use Security groups and Network Access Control lists to secure the different layers of a multi-tier network.<br>
- [ ] Work with SQS standand queues and FIFO queues.
- [ ] Create and subscribe to AWS SNS topics.
- [ ] Create a Beanstalk application using CLI .
- [ ] Patch live kubernetes deployments and drain a node for maintenance.

**Kubernetes Hands-on task**

- [ ] Install and test components of kubernetes cluster.
- [ ] Setup kubernetes cluster with docker.
- [ ] Deploy Go microservice to kubernetes.
- [ ] Create a kubernetes cluster.
- [ ] Generate kubeconfig.
- [ ] Set up a frontend load balancer.
- [ ] Bootstrap kubernetes control panel
- [ ] Bootstrap worker nodes.
- [ ] AutoScale deployment.
- [ ] Schedule pods with taints &amp; tolerance.
- [ ] Deploy pod to a node with a label.
- [ ] Configure probes for pods.
- [ ] Implement state persistence for pods.
- [ ] Create PV for pods.
- [ ] Perform rolling update of a Go application.
- [ ] Configure cron job.
- [ ] Roll update of application.
- [ ] Set up a self healing application.
- [ ] Canary deployment with jenkins and kubernetes.
- [ ] Istio in kubernetes.
- [ ] Pod Security Policy.
- [ ] Monitor and output logs to a file.
- [ ] Monitoring with Prometheus &amp; gafana.
- [ ] Create a Service and Discovering DNS Name.
- [ ] Expose service to the internet.
- [ ] Create a cluster role to access PV.
- [ ] Repair failed pod.
- [ ] Create alert rules.
- [ ] Practice common kubernetes debugging skill.
- [ ] Smoke test the cluster.
- [ ] CKAD Practice exam-1.
- [ ] CKAD Practice exam-2.
- [ ] CKAD Practice exam-3.
