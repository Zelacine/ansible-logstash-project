# Install Filebeat
ansible-playbook -i inventory playbooks/site.yml -e filebeat_install_method=deb
OR
ansible-playbook -i inventory playbooks/site.yml -e filebeat_install_method=repo