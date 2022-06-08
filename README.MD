# Assignment 2

# Network Authomation With Ansible

# list of files
  ansible.cf: is the ansible configuration file
  application2.py: flask app running in the webservers. used to replay host name and time of the web server
  haproxy.j2: HAproxy configuration file
  hosts: inventory file
  site.yame: the ploybook that authomate the following tasks 
  README.MD: file that containes information about the playbook

   # This Ansible playpook does the following 

update cashe if not updated for at least two hours
install HAproxy if not installed 
configure HAproxy
install nginx if not installed 
configure nginx
install pip3 in the dev servers if not installed
install flask in the dev servers if not installed
install snmpd in the dev servers if not installed
deploy flask app into dev servers 
install gunicorn in the dev servers if not installed
run flask app in the dev servers 



# usage example

ansible-playbook site.yaml