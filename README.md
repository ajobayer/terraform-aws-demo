# terraform-aws-web-stack

Terraform is a tool for building, changing, and versioning infrastructure safely and efficiently. Terraform can manage existing and popular service providers as well as custom in-house solutions.

# AWS following Service & Resources has been used to provisioning Web Stack
- VPC: Amazon VPC lets you provision a logically isolated section of the Amazon Web Services (AWS) cloud where you can launch AWS resources in a virtual network that you define. You have complete control over your virtual networking environment, including selection of your own IP address ranges, creation of subnets, and configuration of route tables and network gateways.

- Security Groups: A security group acts as a virtual firewall for your instance to control inbound and outbound traffic. When you launch an instance in a VPC, you can assign up to five security groups to the instance. Security groups act at the instance level, not the subnet level. Therefore, each instance in a subnet in your VPC could be assigned to a different set of security groups. If you don't specify a particular group at launch time, the instance is automatically assigned to the default security group for the VPC.

- EC2 Instances (Web Server): 
Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale cloud computing easier for developers.


# Run the follwoing command to create the Webserver into AWS public cloud

## Initialize a Terraform working directory
$ terraform init --var-file='terraform.tfvars'
## Generate and show an execution pla
$ terraform plan --var-file='terraform.tfvars'
## Builds or changes infrastructure
$ terraform apply --var-file='terraform.tfvars'
## Destroy Terraform-managed infrastructure
$ terraform destroy --var-file='terraform.tfvars'
