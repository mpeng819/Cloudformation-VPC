# Cloudformation-VPC
# This CloudFormation template deploys a basic VPC, with the following:
# Works in ap-northeast-1, ap-northeast-2, ap-east-1 and ap-southeast-1 regions
# 2 Public Subnets in 2 AZ
# 2 Private Subnets in 2 AZ
# 1 NAT instance in PublicSubnet1
# 1 public facing Application Load Balancer
# 1 1 ASG ( 2 min, 4 max )
# 2 EC2 instance in 2 Private Subnet in the ASG, 1 EC2 each Private Subnet
