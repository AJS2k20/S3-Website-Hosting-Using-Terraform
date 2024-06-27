# S3-Website-Hosting-Using-Terraform

##Steps to Create an EC2 Instance in AWS
Launching an EC2 Instance
· Navigate to the EC2 dashboard in the AWS Console.

· Select an appropriate AMI based on your requirements.

· Configure instance details like instance type, security groups, and key pairs.

##Setting up Networking for the EC2 Instance
· Choose a VPC for the instance to control networking settings.

· Assign an Elastic IP address for a static public IP.

· Set up security groups to define inbound and outbound traffic rules.

##Accessing the EC2 Instance
· Connect to the instance using SSH or RDP depending on the operating system.

· Install necessary software and configure the instance to meet your needs.

· Test the connectivity and functionality to ensure proper setup.

#Attaching an IAM Role to the EC2 Instance
##Creating an IAM Role
· Go to the IAM dashboard in the AWS Console.

· Create a new IAM Role with specific permissions based on your requirements.

· Understand the trust policy and access policy to control access to resources.

##Attaching IAM Role to the EC2 Instance
· Select the EC2 Instance to attach the IAM Role.

·Actions -> Security -> Modify role ->Attach Role

· Assign the IAM Role during the instance creation process.

· Verify successful attachment of the IAM Role to the EC2 Instance.

Testing IAM Role Permissions
· Run commands on the EC2 Instance to test IAM Role permissions.

· Monitor access to AWS services granted by the IAM Role.

· Troubleshoot any permission-related issues as needed.
