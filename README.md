# Udacity Cloud DevOps Nanodregree 2020
## Project: Deploy a High-Availability Web App using CloudFormation
AWS CloudFormation Infrastructure to deploy "Udagram" Web application.
Some important details about my project:
* Used NAT Instances instead of NAT Gatewyas (AWS Educate starter account user).
* Set my own public S3 Bucket (udagram-demo-1) to make the manual copy of all app's files into the web servers of the infrastructure.
* The possibilities for SSH connections was considered since NAT Instances can work as bastions. All Security Groups rules regarding SSH connections are commented in the script. Commenting out those and running a stack update will enable SSH connections.  
* URL: http://udagr-webap-1q8knp55ldh8f-294895476.us-east-1.elb.amazonaws.com/

## Infrastructure diagram
<img src="images/udagramInfra diagram.jpg">

