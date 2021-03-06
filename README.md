# Udacity Cloud DevOps Nanodregree 2020
## Project: Deploy a High-Availability Web App using CloudFormation
AWS CloudFormation Infrastructure to deploy "Udagram" Web application.
Some important details about my project:
* Used NAT Instances instead of NAT Gatewyas (AWS Educate starter account user).
* Default AWS Region used: US East (N. Virginia)us-east-1. (AWS Educate starter account supported region).
* Set my own public S3 Bucket (udagram-demo-1) to make the manual copy of all app's files into the web servers of the infrastructure.
* The possibilities for SSH connections was considered since NAT Instances can work as bastions. All Security Groups rules regarding SSH connections are commented in the script. Commenting out those and running a stack update will enable SSH connections.  

## Infrastructure diagram
<img src="images/udagramInfra diagram.jpg">

## Sources of information and libraries used
* Infrastructure Diagrams, Networking Infrastructure and Servers and Security Groups lessons from Deploy Infrastructure as Code, Part 3 of the Nanodegree program.
* Setting Up NAT Instances: https://docs.aws.amazon.com/vpc/latest/userguide/VPC_NAT_Instance.html
* Attaching an IAM managed policy to an IAM role in AWS CloudFormation: https://aws.amazon.com/es/premiumsupport/knowledge-center/cloudformation-attach-managed-policy/
* Fonts animations in app's landing page from: https://daneden.github.io/animate.css/
* Fonts used in app's landing page: https://fonts.google.com/

