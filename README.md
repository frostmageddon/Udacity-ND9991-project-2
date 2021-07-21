# UdacityProject2
Udacity Cloud Devops Engineer Project 2
URL: http://Udaci-LoadB-BETRF1761YBL-1195538603.us-east-1.elb.amazonaws.com

Purpose of Project:
--------
The purpose of this project is to learn about Amazons AWS Cloudformation. By completing this lab within Udacity's Course ND9991, you will be able to confidently create autoscaling applications within the AWS environment.

How to run:
----
by running the commands:

  ./create.sh <StackName1> network.yml network-parameters.json
  ./create.sh <StackName2> servers.yml server-parameters.json

Verify Creation:
----
by checking the server stacks output after creation there will be a URL that is created in the form of http://<StackName2>-{az-09}-{09}.us-east-1.elb.amazonaws.com

Explanation of use of t2.medium:
---
Per the requirements of having 2 VPC and 4GI of Ram, the t2.medium offers that at what seems a lower cost with a hit to "bandwidth" compared to the T3.small. 

Issues while completing Project:
----
AWS thought that my IAM account for CLI was a breach of security so if someone could tell me what permissions a CLI user should have. please let me know. My Account was locked for 5 days while i waited for communication with AWS Security. 

