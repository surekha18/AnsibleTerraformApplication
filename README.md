# Terraform and Ansible Web application setup

Creating a instance with webserver which serves website, setup with ansible.

## File details

main.tf - Defined the AWS module and all the resources like subnets,security groups and auutoscaling configurations.
variables.tf -  Defined all the required variables insted of hard coading.

## Getting Started

Add all the required exports and variabled in the user_script.sh file and run the sh file.

First needs to run terraform with aws access key and secury key.

Terraform commands:

terraform init
 
terraform plan

terraform apply

terraform destroy

Then run ansible to provision webserver servers.

Ansible command: ansible-playbook aws_ec2.yml





