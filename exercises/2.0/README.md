To get access to tyhe aws account file at roles/ansible_role_create_tier1_server/defaults/main.yml should have the following defined:
* aws_acces_key 
* aws_secret_key defined
* key_pair:  

For key_pair the key pair must exist in AWS and the .pem file should be placed at the same level where the playbook is launched
