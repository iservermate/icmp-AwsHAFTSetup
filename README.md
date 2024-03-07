#For AWS automation
Aws - Setup Amazon's Highlty available and fault tolerance infrastructure 

# On my MAC
ansible-playbook -i invenotry/all AwsSetupOnLocalHost.yml --ask-vault-pass -b -K

ToDo:
 - VOLUMES NAME
 - My ip for SG
 - Add security group and Bastion host id in PrintIds.yml
