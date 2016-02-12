Mesin
=====

an Ansible Playbooks  

###Assumptions

Ansible-playbook installed in your local.  
Run under vagrant, set public network  
Ubuntu 14.04 server  
Have already set up ssh public key authentication on it.  

# Task 1

## Create deployment script using Ansible.

Setup ip server in file hosts
```
$ cd ansible
$ vim hosts
$ ansible-playbook -i hosts dev-django.yml
```

# Task 2

## Create backup rotation.

```
$ cd ansible
$ ansible-playbook -i hosts backup.yml

``` 