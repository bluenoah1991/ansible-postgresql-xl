# Ansible PostgreSQL-XL
PostgreSQL Cluster Ansible Playbook

### Config Manage Host  

1. Setting **allow_world_readable_tmpfiles = True** in ansible.cfg  
2. Setting **host_key_checking = False** in ansible.cfg  
3. Install python package **netaddr**  

### How to use?

	ansible-playbook site.yml --ask-pass --ask-sudo-pass  


