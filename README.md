# Terraform AWS CloudFormation Stack Deployment

## Overview

This beginner-friendly project demonstrates how to create a CloudFormation stack to deploy AWS resources using Terraform. It is designed to help new users understand how to integrate Terraform with AWS CloudFormation for resource management. This project involves setting up Terraform, creating and managing AWS resources through CloudFormation, and ensuring proper cleanup to avoid unnecessary costs.

## Prerequisites

1. **Terraform Installation**

   Install Terraform on your local machine by following the official guide by HashiCorp:
   - [Install Terraform using CLI](https://learn.hashicorp.com/tutorials/terraform/install-cli)
   - [Download Terraform](https://www.terraform.io/downloads.html)

2. **Visual Studio Code Installation**

   Download and install Visual Studio Code by following this guide:
   - [Download Visual Studio Code](https://code.visualstudio.com/download)

## Task Details

1. **Sign in to AWS Management Console**

   - Access the AWS Management Console at [AWS Console](https://aws.amazon.com/console/).

2. **Setup Visual Studio Code**

   - Open Visual Studio Code and configure it for your Terraform project.

3. **Create a `variables.tf` File**

   - Define your variables in a `variables.tf` file.

4. **Create a Key Pair for the EC2 Instance**

   - Add the key pair configuration for your EC2 instance in `main.tf`.

5. **Create a CloudFormation Stack**

   - Define your CloudFormation stack resources in `main.tf`. This includes setting up the necessary AWS resources through a CloudFormation template.

6. **Create an `output.tf` File**

   - Specify the output variables in an `output.tf` file to get useful information about the deployed resources.

7. **Confirm Terraform Installation**

   - Verify the installation by checking the version:
     ```bash
     terraform version
     ```

8. **Apply Terraform Configurations**

   - Execute the Terraform commands to apply the configurations:
     ```bash
     terraform init
     terraform apply
     ```

9. **Check AWS Resources**

   - Verify the resources created by the CloudFormation stack in the AWS Management Console.



10. **Delete AWS Resources**

   - Remove the resources by executing:
     ```bash
     terraform destroy
     ```

## Cost Considerations

Be aware that creating and running AWS resources may incur costs. Ensure you review and understand the pricing for the resources you are using. Always delete resources when they are no longer needed to avoid unnecessary charges.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Notes

- Ensure you follow best practices for managing AWS resources and Terraform configurations.
- For additional help, refer to the official [Terraform Documentation](https://www.terraform.io/docs) and [AWS Documentation](https://docs.aws.amazon.com/), or seek support from the community.
