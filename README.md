# terraform-aws-ec2-instance-tests-md

A Terraform module for creating EC2 instances with integration tests.

## Usage

```hcl
module "ec2_instances" {
  source = "app.terraform.io/policy-as-code-training/ec2-instance-tests-md/aws"
  
  instance_count = 2
  instance_type  = "t2.micro"
}