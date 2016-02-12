Mesin
=====

an Ansible Playbooks  

###Assumptions

Run under vagrant, set public network  
Ubuntu 14.04 server  
Have already set up ssh public key authentication on it.  

# Task 1

## Create deployment script using Ansible.

```
$ cd ansible
```
setup ip server in file hosts

```  
$ ansible-playbook -i hosts provision.yml
```

# Task 2

## Create backup rotation.