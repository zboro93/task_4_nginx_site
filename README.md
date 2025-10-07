## nginx_site
task4 - Set up Nginx site with Ansible
---

**About**

My path to DevOps role.
As preparation and learning to be a DevOps Engineer, I began to perform practical tasks that will help and document my development.  
This task is to build simple Nginx site using Ansible.

---

**Build with**
 - Ansible
 - Nginx

---

**How it works**

Ansible file playbook.yml contains Ansible tasks to prepare and setup simple Nginx site on remote Ubuntu server. It updates apt, installs Nginx service, configures Nginx and firewall to start website.


---

**Usage**

1. Copy files
    - copy playbook.yml to the destination folder
    - copy index.html to /tmp/task-nginx/
    - copy webpage to /tmp/task-nginx/
2. Configure Ansible
    - configure ansible.cfg file
    - prepare hosts file
4. Apply Ansible playbook
    - ansible-playbook playbook.yml
5. Visit website
    - Open web browser and enter IP address of your remote Ubuntu server

---
