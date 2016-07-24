# Ansible playbook

Ansible playbook for setting up load balancer, web servers, nfs server & mysql server

Machines:
- load balancer
- web server(s)
- nfs server
- mysql server

You can change in ansible.cfg default remote user, also you need to change ip address in hosts file.

Example running this playbook:

```
ansible-playbook run.yml -i hosts --ask-pass
```