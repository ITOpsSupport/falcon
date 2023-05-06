# install falcon agent
last modified date: 6 May 2023
last modified by: raj.ayush@naukri.com
# description 
falcon sensor is used as XDR solution is our infrastructure
# to run playbook 
ansible-playbook -i hosts falcon_centos7.yaml -u user_name -k -e ansible_ssh_port=22

# cid= xxxxx 
ask your security admin or EIS  to share cid 

# ansible hosts 
[falcon]
xxxx.xxxx.xxxx.xxxx