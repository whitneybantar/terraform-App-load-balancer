
# Application Load Balancer (ALB) using Terraform

This repository contains Terraform code for provisioning an AWS Application Load Balancer (ALB). The ALB is a fully managed load balancer service that distributes incoming application traffic across multiple targets, such as Amazon EC2 instances.

## Prerequisites

Before you begin, make sure you have the following prerequisites:

1. **AWS Account**: You need an AWS account and credentials configured locally with the necessary permissions for Terraform to create resources.

2. **Terraform**: Ensure Terraform is installed on your local machine. You can download it from the [Terraform website](https://www.terraform.io/downloads.html).

3. **AWS CLI**: Make sure you have the AWS Command Line Interface (CLI) installed and configured with your AWS credentials.

## Getting Started

Follow these steps to provision an ALB using Terraform:

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
Initialize Terraform:

Run the following command to initialize the Terraform working directory:

bash
Copy code
terraform init
Review Configuration:

Open the main.tf file and review the Terraform configuration. Customize it according to your requirements, such as security groups, subnets, and target instances.

Plan:

Run terraform plan to see the resources Terraform will create or modify:

bash
Copy code
terraform plan
Apply:

If the plan looks good, apply it to create the ALB and associated resources:

bash
Copy code
terraform apply
Access the ALB:

Once the provisioning is complete, you can access your ALB by using the DNS name provided in the Terraform output.

Clean Up (Optional):

When you're done with the ALB and want to clean up the resources, run:

bash
Copy code
terraform destroy
Customization
You can customize the ALB configuration by editing the main.tf file. Modify the security group rules, listener rules, and target group settings to meet your specific use case.

Troubleshooting
If you encounter any issues or have questions, feel free to open an issue in this repository.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Special thanks to Terraform and AWS for their powerful tools and services.
vbnet
Copy code

Remember to replace `<repository-url>` and `<repository-directory>` with your ac
