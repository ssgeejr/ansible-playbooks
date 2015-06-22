# Ansible

#### Role bootstrap script
ansiblerole is a simple script to create an ansible playbook skeleton.
add the file to your path, enable execute (set +x /usr/local/bin/ansiblerole)

Default Role Directory Structure

```
/etc/ansible/\<role\>.yml
/etc/ansible/\<role\>/
  files/skeleton_file
  templates
  tasks / main.yml
  handlers / main.yml
  vars / main.yml
  defaults
  meta / main.yml
```

Directories and files created:

* /etc/ansible/roles/\<role\>
* /etc/ansible/roles/\<role\>/files
    * /etc/ansible/roles/\<role\>/files/skeleton_file
* /etc/ansible/roles/\<role\>/templates
* /etc/ansible/roles/\<role\>/tasks
    * /etc/ansible/roles/\<role\>/tasks/main.yml
* /etc/ansible/roles/\<role\>/handlers
    * /etc/ansible/roles/\<role\>/handlers/main.yml
* /etc/ansible/roles/\<role\>/vars
    * /etc/ansible/roles/\<role\>/vars/main.yml
* /etc/ansible/roles/\<role\>/defaults
* /etc/ansible/roles/\<role\>/meta
    * /etc/ansible/roles/\<role\>/meta/main.yml

   
   
   
#### To use: 
From the command line, *after the script is added to your path*, execute: ansiblerole <role_name>
**ansiblerole adduser**

```
----------------------------------------------
Creating Role  project structure for: adduser
Creating host file: /etc/ansible/adduser.yml
Creating directory: /etc/ansible/roles/adduser
Creating directory: /etc/ansible/roles/adduser/files
Creating file: /etc/ansible/roles/adduser/files/skeleton_file
Creating directory: /etc/ansible/roles/adduser/templates
Creating directory: /etc/ansible/roles/adduser/tasks
Creating file: /etc/ansible/roles/adduser/tasks/main.yml
Creating directory: /etc/ansible/roles/adduser/handlers
Creating file: /etc/ansible/roles/adduser/handlers/main.yml
Creating directory: /etc/ansible/roles/adduser/vars
Creating file: /etc/ansible/roles/adduser/vars/main.yml
Creating directory: /etc/ansible/roles/adduser/defaults
Creating directory: /etc/ansible/roles/adduser/meta
Creating file: /etc/ansible/roles/adduser/meta/main.yml
----------------------------------------------
[Success] role adduser created
```

#### Note:
If you have changed the default setting for roles in /etc/ansible/ansible.cfg you will need to update the 
