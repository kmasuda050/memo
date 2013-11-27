```bash
# getenfroce 0
# setenforce 0
# vi /etc/selinux/config 
- SELINUX=enforcing
+ SELINUX=disabled
# visudo
root    ALL=(ALL)       ALL
+ chef    ALL=(ALL)       ALL
# useradd chef
# su - chef

$ sudo yum update
$ sudo yum -y install vim-enhanced screen # personal
$ sudo yum install git

$ curl -L http://www.opscode.com/chef/install.sh | sudo bash
$ git clone git://github.com/opscode/chef-repo.git
```
