# ansible-rails
Ansible playbooks to set up rails environment on CentOS 7

# How to use
## install ansible (OSX)
```
$ brew update
$ brew install ansible
```

## exec playbook
```
$ git clone git@github.com:forthelocal/ansible-rails.git
$ cd ansible-rails
$ cp hosts.example hosts
$ vi hosts # specify hosts you want to setup
$ ansible-playbook site.yml -i hosts
```
