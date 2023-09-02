# ansible modules

### About the repo

Exploring the various ansible modules to configure and manage the servers. 

- Config.yaml

  - This playbook configures the linux(ubuntu) server with some basic tools and applications.
  - It installs git, docker, apache2 kind of softwares which is required for application deployment.  


- Users.yaml

  - First we create a user, password, ssh keys and groups
  - Adding the user to the group, creating a directory in the home folder with restrictions.  

- webdeployment.yaml

  - Installing the nginx webserver on the remote machine.
  - Transferring the files from the local to the nginx server
  - In-addition using ansible docker module, an image is pulled started, stopped and removed.

### How to tweak it

Change the hosts and remote_user in each of the yaml files according to the inventory file and user you have.
it works fine!! :+1:
