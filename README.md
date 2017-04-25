# Ansible + CentOS Virtualmachine
Ansible provisioned VirtualMachine using Centos 6.7. Environment running on Apache, PHP 7.0 and MySQL 5.6

### Initialize
```shell
$ git clone https://github.com/alexhoma/ansible-centos-v6.7.git
$ cd ansible-centos-v6.7/vagrant
$ vagrant up --provision

# Remove git
$ cd ..
$ rm -rf .git*
```

### Add project
```shell
$ cd ansible-centos-v6.7/shared
$ git clone {PROJECT_REPOSITORY}
$ cp -R {PROJECT_REPOSITORY}/* www/
```
