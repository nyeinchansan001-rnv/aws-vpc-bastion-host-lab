AWS VPC Bastion Host Lab Notes

SSH Commands

Connect to Public EC2

   ssh -i <yourPen>.pem ec2-user@PUBLIC_IP

Connect to Private EC2 from Bastion Host

   ssh -i <yourPen>.pem ec2-user@PRIVATE_IP

Verification

Check Public IP

   curl ipinfo.io/ip

Test Connectivity

   ping PRIVATE_IP

Git Commands

Initialize Repository

   git init

Add Files

   git add .

Commit Changes

   git commit -m "AWS VPC Bastion Host Lab"

Push to GitHub

   git push origin main

Lessons Learned

- Created a custom VPC
- Configured public and private subnets
- Configured route tables and Internet Gateway
- Connected to a private EC2 through a Bastion Host
- Used Git and GitHub for project documentation
