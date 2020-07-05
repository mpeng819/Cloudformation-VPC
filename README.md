# This CloudFormation template deploys a basic VPC, with the following:
# Tested in ap-northeast-1 and ap-southeast-1 region
# 2 x Public Subnets in 2 AZs
# 2 x Private Subnets in 2 AZs
# 1 x NAT instance in PublicSubnet1
# 1 x NAT instance in PublicSubnet2
# 1 x Public Facing Application Load Balancer
# 1 x ASG
# 2 x EC2 instance in 2 Private Subnet in the ASG, 1 EC2 per Private Subnet
# 1 x S3 Gateway Endpoints, associate Private RT1 and Private RT2
# Role for S3 Full Access
