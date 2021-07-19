# UdacityProject2
Udacity Cloud Devops Engineer Project 2

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
