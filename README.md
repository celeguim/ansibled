# Requirements
- sudo ntpdate us.pool.ntp.org
- sudo python -m pip install --user boto3
- ansible-vault --vault-password-file=~/.vault_pass [encrypt,edit,view] group_vars/all.yml
- echo 'my_vault_password' > ~/.vault_pass
- chmod 600 ~/.vault_pass


# Ansibled
This repository supports the "Automation with Ansible" series by Tom Wright on Medium.

https://medium.com/@tomwwright


### Articles

- [Automation with Ansible: Introduction] (https://medium.com/@tomwwright/automation-with-ansible-introduction-ccfa1baf8f5c)
- [Automation with Ansible: Building a VPC] (https://medium.com/@tomwwright/automating-with-ansible-building-a-vpc-c252944d3d2e)
- [Automation with Ansible: AWS Elasticsearch] (https://medium.com/@tomwwright/automation-with-ansible-aws-elasticsearch-service-8d862cdb4a68)
- [Automation with Ansible: Aurora RDS Clusters] (https://medium.com/@tomwwright/automating-with-ansible-aurora-clusters-7272364777dd)
- [Automation with Ansible: Logentries] (https://medium.com/@tomwwright/automation-with-ansible-logentries-53cf595c2002)

