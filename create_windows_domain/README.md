My first collection of playbooks - creates a Windows network within AWS.

# Create VPC in London
ansible-playbook create_vpc.yml --extra-vars="aws-region eu-west-2

# Get all EC2 instances - https://docs.ansible.com/ansible/latest/plugins/inventory.html#inventory-plugins
ansible-inventory -i all.aws_ec2.yml --graph
