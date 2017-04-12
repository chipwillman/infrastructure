# infrastructure
AWS General Network and Infrastructure 

## Pre-requisites

1. AWS Account 
1. awscli installed
1. Hosted Zone for Public or Private Domain Name
1. PEM Key

## Create VPC

```
cd vpc
aws cloudformation update-stack --stack-name homevpc --template-body file://vpc_network.json --parameters file://params/vpc-params.json
```

