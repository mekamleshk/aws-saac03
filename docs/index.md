# AWS Solution Architect Associate Notes

Welcome to the documentation for the AWS Solution Architect Associate certification. These notes are organized by **Exam Weight**, allowing you to focus on the high-probability topics first.

---

## 🚨 Priority 1: The "Big 5" (Master These First)
**Goal:** Spend 60% of your revision time here. If you fail these, you fail the exam.

### Networking and Content Delivery
- [Amazon VPC](networking-and-content-delivery/vpc.md)
- [Amazon Route 53](networking-and-content-delivery/route53.md)
- [Amazon CloudFront](networking-and-content-delivery/cloudfront.md)
- [Elastic Load Balancing (ELB)](networking-and-content-delivery/elastic-load-balancing.md)
- [AWS Direct Connect](networking-and-content-delivery/direct-connect.md)
- [AWS Global Accelerator](networking-and-content-delivery/global-accelerator.md)
- [AWS PrivateLink](networking-and-content-delivery/private-link.md)
- [AWS Site-to-Site VPN](networking-and-content-delivery/site-to-site-vpn.md)
- [AWS Transit Gateway](networking-and-content-delivery/transit-gateway.md)
- [AWS Client VPN](networking-and-content-delivery/client-vpn.md)

### Compute
- [Amazon EC2](compute/ec2.md)
- [Amazon EC2 Auto Scaling](compute/ec2-auto-scaling.md)
- [AWS Elastic Beanstalk](compute/elastic-beanstalk.md)
- [AWS Batch](compute/batch.md)
- [AWS Outposts](compute/outposts.md)
- [AWS Serverless Application Repository](compute/serverless-application-repository.md)
- [VMware Cloud on AWS](compute/vmware-cloud-on-aws.md)
- [AWS Wavelength](compute/wavelength.md)

### Storage
- [Amazon S3](storage/s3.md)
- [Amazon Elastic Block Store (Amazon EBS)](storage/ebs.md)
- [Amazon Elastic File System (Amazon EFS)](storage/efs.md)
- [Amazon FSx (for all types)](storage/fsx.md)
- [AWS Storage Gateway](storage/storage-gateway.md)
- [AWS Backup](storage/backup.md)

### Database
- [Amazon RDS](database/rds.md)
- [Amazon Aurora](database/aurora.md)
- [Amazon Aurora Serverless](database/aurora-serverless.md)
- [Amazon DynamoDB](database/dynamodb.md)
- [Amazon ElastiCache](database/elasticache.md)
- [Amazon DocumentDB (with MongoDB compatibility)](database/documentdb.md)
- [Amazon Keyspaces (for Apache Cassandra)](database/keyspaces.md)
- [Amazon Neptune](database/neptune.md)
- [Amazon Quantum Ledger Database (Amazon QLDB)](database/qldb.md)

### Security, Identity, and Compliance
- [AWS Identity and Access Management (IAM)](security-identity-and-compliance/iam.md)
- [AWS Key Management Service (AWS KMS)](security-identity-and-compliance/kms.md)
- [Amazon Cognito](security-identity-and-compliance/cognito.md)
- [AWS WAF](security-identity-and-compliance/waf.md)
- [AWS Shield](security-identity-and-compliance/shield.md)
- [AWS Secrets Manager](security-identity-and-compliance/secrets-manager.md)
- [AWS IAM Identity Center (AWS Single Sign-On)](security-identity-and-compliance/iam-identity-center.md)
- [AWS Certificate Manager (ACM)](security-identity-and-compliance/acm.md)
- [Amazon GuardDuty](security-identity-and-compliance/guardduty.md)
- [AWS Security Hub](security-identity-and-compliance/security-hub.md)
- [AWS Network Firewall](security-identity-and-compliance/network-firewall.md)
- [AWS Firewall Manager](security-identity-and-compliance/firewall-manager.md)
- [AWS Directory Service](security-identity-and-compliance/directory-service.md)
- [AWS Resource Access Manager (AWS RAM)](security-identity-and-compliance/resource-access-manager.md)
- [Amazon Inspector](security-identity-and-compliance/inspector.md)
- [Amazon Macie](security-identity-and-compliance/macie.md)
- [AWS Artifact](security-identity-and-compliance/artifact.md)
- [AWS Audit Manager](security-identity-and-compliance/audit-manager.md)
- [AWS CloudHSM](security-identity-and-compliance/cloudhsm.md)
- [Amazon Detective](security-identity-and-compliance/detective.md)

---

## 🧩 Priority 2: Architecture & Decoupling
**Goal:** Understand how to connect services together (Serverless, Queues, Containers).

### Serverless
- [AWS Lambda](serverless/lambda.md)
- [AWS AppSync](serverless/appsync.md)
- [AWS Fargate](serverless/fargate.md)

### Application Integration
- [Amazon Simple Queue Service (Amazon SQS)](application-integration/sqs.md)
- [Amazon Simple Notification Service (Amazon SNS)](application-integration/sns.md)
- [AWS Step Functions](application-integration/step-functions.md)
- [Amazon EventBridge](application-integration/eventbridge.md)
- [Amazon AppFlow](application-integration/appflow.md)
- [Amazon MQ](application-integration/mq.md)

### Containers
- [Amazon Elastic Container Service (Amazon ECS)](containers/ecs.md)
- [Amazon Elastic Kubernetes Service (Amazon EKS)](containers/eks.md)
- [Amazon Elastic Container Registry (Amazon ECR)](containers/ecr.md)
- [Amazon ECS Anywhere](containers/ecs-anywhere.md)
- [Amazon EKS Anywhere](containers/eks-anywhere.md)
- [Amazon EKS Distro](containers/eks-distro.md)

---

## ⚙️ Priority 3: Operations & Migration
**Goal:** Easy points. Focus on DataSync, CloudWatch, and Organizations.

### Migration and Transfer
- [AWS DataSync](migration-and-transfer/datasync.md)
- [AWS Database Migration Service (AWS DMS)](migration-and-transfer/dms.md)
- [AWS Snow Family](migration-and-transfer/snow-family.md)
- [AWS Transfer Family](migration-and-transfer/transfer-family.md)
- [AWS Application Discovery Service](migration-and-transfer/application-discovery-service.md)
- [AWS Application Migration Service](migration-and-transfer/application-migration-service.md)
- [AWS Migration Hub](migration-and-transfer/migration-hub.md)

### Management and Governance
- [Amazon CloudWatch](management-and-governance/cloudwatch.md)
- [AWS CloudTrail](management-and-governance/cloudtrail.md)
- [AWS Organizations](management-and-governance/organizations.md)
- [AWS Systems Manager](management-and-governance/systems-manager.md)
- [AWS Config](management-and-governance/config.md)
- [AWS Trusted Advisor](management-and-governance/trusted-advisor.md)
- [AWS CloudFormation](management-and-governance/cloudformation.md)
- [AWS Control Tower](management-and-governance/control-tower.md)
- [AWS Compute Optimizer](management-and-governance/compute-optimizer.md)
- [AWS Service Catalog](management-and-governance/service-catalog.md)
- [AWS Health Dashboard](management-and-governance/health-dashboard.md)
- [AWS License Manager](management-and-governance/license-manager.md)
- [Amazon Managed Grafana](management-and-governance/managed-grafana.md)
- [Amazon Managed Service for Prometheus](management-and-governance/managed-prometheus.md)
- [AWS Management Console](management-and-governance/management-console.md)
- [AWS Proton](management-and-governance/proton.md)
- [AWS Well-Architected Tool](management-and-governance/well-architected-tool.md)

### AWS Cost Management
- [AWS Cost Explorer](cost-management/cost-explorer.md)
- [AWS Budgets](cost-management/budgets.md)
- [Savings Plans](cost-management/savings-plans.md)
- [AWS Cost and Usage Report](cost-management/cost-usage-report.md)

---

## 🔍 Priority 4: Keyword Match Only
**Goal:** Don't overstudy. Just know the 1-sentence definition of each service.

### Analytics
- [Amazon Athena](analytics/athena.md)
- [Amazon Redshift](analytics/redshift.md)
- [AWS Glue](analytics/glue.md)
- [Amazon Kinesis](analytics/kinesis.md)
- [Amazon OpenSearch Service](analytics/opensearch.md)
- [Amazon EMR](analytics/emr.md)
- [Amazon QuickSight](analytics/quicksight.md)
- [AWS Data Exchange](analytics/data-exchange.md)
- [AWS Data Pipeline](analytics/data-pipeline.md)
- [AWS Lake Formation](analytics/lake-formation.md)
- [Amazon Managed Streaming for Apache Kafka (Amazon MSK)](analytics/msk.md)

### Front-End Web and Mobile
- [AWS Amplify](front-end-web-and-mobile/amplify.md)
- [Amazon API Gateway](front-end-web-and-mobile/api-gateway.md)
- [Amazon Pinpoint](front-end-web-and-mobile/pinpoint.md)
- [AWS Device Farm](front-end-web-and-mobile/device-farm.md)

### Machine Learning
- [Amazon SageMaker](machine-learning/sagemaker.md)
- [Amazon Rekognition](machine-learning/rekognition.md)
- [Amazon Transcribe](machine-learning/transcribe.md)
- [Amazon Polly](machine-learning/polly.md)
- [Amazon Comprehend](machine-learning/comprehend.md)
- [Amazon Lex](machine-learning/lex.md)
- [Amazon Translate](machine-learning/translate.md)
- [Amazon Forecast](machine-learning/forecast.md)
- [Amazon Fraud Detector](machine-learning/fraud-detector.md)
- [Amazon Kendra](machine-learning/kendra.md)
- [Amazon Textract](machine-learning/textract.md)

### Developer Tools
- [AWS X-Ray](developer-tools/x-ray.md)

### Media Services
- [Amazon Elastic Transcoder](media-services/elastic-transcoder.md)
- [Amazon Kinesis Video Streams](media-services/kinesis-video-streams.md)
