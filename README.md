# Terraform

  ## Terraform Templates

    - vpc.tf
    - ec2.tf
    
  ## VPC
    - I have create VPC, Subnet, Security Group, Internet Gateway, Route Table ect.

  ## EC2
    - For EC2 key_pair I have upload my public key in template. 
    - You can use your key pair or Delete "aws_key_pair" resource and update key_pair name in ec2.tf (line no. 16).

  ## Terraform Command 
    - terraform plan
    - terraform apply
    
    For Clean-up infra.
    - terraform destroy 
