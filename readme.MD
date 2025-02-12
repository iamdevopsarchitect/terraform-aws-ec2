# Terraform AWS EC2

## Arguments
ami_id - (mandatory), user must provide AMI id. thi9s is in string format.
Instance_type - (Optional), default is t3.micro
security_group_ids - (Mandatory), User muist prvide list of SG ID

## Outputs
public_ip - Public IP of the instance created
Private_ip - Private IP of the instance created
instance_id - Instance ID of the instance created