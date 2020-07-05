# Cloudformation: MyVPC-NAT-ALG-ASG.yml

# This CloudFormation template deploys a basic VPC, with the following:
# Works in ap-northeast-1, ap-northeast-2, ap-east-1 and ap-southeast-1 regions
# 2xPublic Subnets in 2 AZ
# 2xPrivate Subnets in 2 AZ
# 1xNAT instance in PublicSubnet1
# 1xpublic facing Application Load Balancer
# 1xASG ( 2 min, 4 max )
# 2xEC2 instance in 2 Private Subnet in the ASG, 1 EC2 each Private Subnet
