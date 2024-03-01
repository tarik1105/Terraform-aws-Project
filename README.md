# Setting up Infrastructure on AWS using Terraform

requirements:
vs code, Terraform, aws cli and aws account

<p align="center">
  <img src="/images/terraform.aws.png" width="550" title="tarik">
  <!-- <img src="your_relative_path_here_number_2_large_name" width="350" alt="accessibility text"> -->
</p>

steps:
1. define aws as provider.
2. create vpn and create two subnets with CIDR blocks.
3. configure Internet Gateway and route tables so we can access our instances over internet.
4. configure Security groups to expose ports.
5. create s3 bucket 
6. create Application Load Balancer to route traffic.

