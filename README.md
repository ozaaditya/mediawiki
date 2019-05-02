# mediawiki
Instructions:

1. Clone above git repo to any ec2 instance with rights to provision resources in IAM.
2. Change vpc-id,security group and other details in /var/main.yml as per your setup
3. Execute command
ansible-playbook mediawiki_deployment.yaml -i hosts --key-file "your-aws-key-pair" --ask-vault-pass
