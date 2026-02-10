**Installation**

sudo apt update -y  
sudo apt upgrade -y  
sudo apt-add-repository ppa:ansible/ansible  
sudo apt update

&nbsp;

put private ssh key in ansible controller suing nano

ec2-instance-app1-reference name

ec2-instance-app1 ansible_host=54.216.167.100 ansible_user=ubuntu ansible_ssh_private_key_file="~/.ssh/se-luke-key-pair.pem

&nbsp;

ansible.cf:  
\[defaults\]  
host_key_checking = False

```
interpreter_python = auto_silent
```

&nbsp;

![fd7bf33354cbd523cf7711ce5932dfe8.png](../../_resources/fd7bf33354cbd523cf7711ce5932dfe8.png)