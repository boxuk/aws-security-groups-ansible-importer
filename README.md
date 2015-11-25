# AWS Security Groups to Ansible importer

1. aws ec2 describe-security-groups > security_groups
2. ./import > playbook.yml
3. Done

Notes:

1. Only works for one region at a time
2. If your not using eu-west-1 then you will have to modify the template
