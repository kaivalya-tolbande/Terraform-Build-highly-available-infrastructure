Build highly available infrastructure using Terraform
This project involved the creation of a virtual private cloud (VPC) and associated infrastructure using the Infrastructure as Code tool, Terraform. The aim was to create a reliable and scalable environment to host a static website. To achieve this, I first created a VPC and then created subnets in two different availability zones. I also set up a NAT gateway and an internet gateway to enable communication between the VPC and the internet. In addition, I created EC2 instances in each of the subnets, with Apache server installed using user data scripts to host the static website.

For step by step implementation, follow this article - https://palak-bhawsar.hashnode.dev/terraform-create-vpc-subnets-and-ec2-instances-in-multiple-availability-zones

![image](https://github.com/kaivalya-tolbande/Terraform-Build-highly-available-infrastructure/assets/110324856/86865554-903a-4330-a6d1-4a234c694211)

![image](https://github.com/kaivalya-tolbande/Terraform-Build-highly-available-infrastructure/assets/110324856/ce894263-b1cc-4bdb-a945-f6f5ca226a56)
