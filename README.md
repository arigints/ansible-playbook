
# ansible-playbook

Simple ansible-playbook project menggunakan apache, mariadb, dan php.

Make sure there are no errors in the configuration file
```bash 
ansible-playbook --syntax-check playbook.yml
```

Deploy the configuration
```bash 
ansible-playbook playbook.yml
```