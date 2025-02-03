# ansible-aws

problème de droit fichier : sudo chmod 755 /workspaces/Ansible pour corriger dans vscode dans un container 

ansible -m setup servers
ansible -m command -a "whoami" servers 
ansible -m ping roivioli-server.eddi.cloud

ansible-playbook playbooks/apache2.yml



Si create ne se lance pas problème de droits chmod 777 /workspaces/ansible-aws pour corriger le problème 

Problème n'a pas les droits web.yml : chmod o-w /workspaces/ansible-aws pour corriger.


se connecter en ssh : ssh user@ip -i .ssh/labuser.pem

Commande linux 

tree -a -I .git

env | grep AWS
	AWS_CONFIG_FILE=.aws/config
	AWS_SHARED_CREDENTIALS_FILE=.aws/credentials
