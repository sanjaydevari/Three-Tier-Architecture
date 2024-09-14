# `Three-Tier-Architecture`

# `AWS 3-Tier Architecture with Terraform`

![Screenshot 2024-09-14 122906](https://github.com/user-attachments/assets/f393b1bd-1a14-4dc1-981d-aff80249bb28)

✔️ 1 Load Balancer

✔️ 2 EC2 Instances

✔️ Security Groups

✔️ RDS MySQL DataBase

✔️ 3 Route Tables

✔️ VPC

✔️ 9 Subnets for High availability

✔️ 1 NAT Gateway

✔️ 1 Internet Gateway

✔️ ap-south-1

This repository contains Terraform code for deploying a 3-tier architecture on AWS. The architecture consists of a web tier with a load balancer, an application tier with EC2 instances, and a data tier with a MySQL database deployed on RDS. The infrastructure is designed to be deployed in the ap-south-1 region. You can use autoscaling feature in the auto scaling branch

# `Prerequisites`

To use this terraform code, you need to have the following prerequisites:

1.Terraform Installed on your machine

2.AWS account credentials with appropriate permissions to provision resources.

# `Getting Started`

Follow the steps below to get started with this infrastructure as code using Terraform:

1.Clone this repository to your local machine:

2.AWS account credentials with appropriate permissions to provision resources.

# Getting Started

Follow the steps below to get started with this infrastructure as code using Terraform:

1.Clone this repository to your local machine:

2.Change to the cloned directory cd ~/Three-Tier-Architecture.git

3.Initialize Terraform by running the following command: terraform init

4.Run terraform plan to preview the changes that will be applied: terraform plan

5.If the plan looks good, you can apply the changes to provision the infrastructure: terraform apply

6.After the Terraform apply completes successfully, it will display the output variables containing information about the provisioned resources.

# `Architecture Overview`

This infrastructure provisions the following resources in the ap-south-1 region:

1.Web/Presentation Tier:
     Elastic Load Balancer (ELB) - Acts as the entry point for end users.
2.Application Tier:
    EC2 Instances - Deployed across multiple availability zones in private subnets.
3.Data Tier:
    Amazon RDS - MySQL database deployed on RDS, utilizing a subnet group with 3 private subnets across multiple availability zones.

# `Cleaning Up`

To clean up and delete the provisioned resources, run the following command: terraform destroy This will destroy all the resources created by Terraform. Please note that this action is irreversible and will permanently delete the resources.

# `Conclusion`

By using this Terraform code, you can easily provision a 3-tier architecture on AWS with a web tier, application tier, and data tier. Feel free to explore and modify the code to fit your specific needs. If you have any questions or issues, please don't hesitate to Reach out to me on Twitter.

Happy coding!

# `The project is completed with the terraform."But i will upload the mannual creation of each and every architecture using amazon web services - AWS"`










