# Ansible playbook for installation of Docker on Ubuntu and Debian servers

These simple playbooks will install Docker on machines in your inventory list. 
On Ubuntu, it will also add user ubuntu to the group docker, so there is no need to run it as root. 

You can tweak the playbooks to execute ```usermod``` to add the specific username to the docker group. 
Running Docker as root just as everything else is not advised. 

Happy and swift deployments ! 
