# Ansible_apache
This project focuses on creating an ansible playbook to automate the installation of apache on to an server instance.
#Description
Using Ansible to install apache2 web server for multiple server instances, and deploy a HTML file to both servers.

#Design decisions taken
Ansible is a tool for which we can write scripts that are used to automate processes. 
The decision for using an automation tool was the inevitable reality of software evolution. 
Ansible allows me to write simple scripts and will take care of the rest of the work. 
With its very simple to understand syntax, I am able to create a base for installing apache webserver, 
making sure the TCP is set to 80 and displaying a HTML page to convey to us the installation was successful.


#Instructions 
How to get set up.

These instructions are assuming that you have your SSH keys properly configured and added to you VPS servers for Ansible to work.

1. If you have not already, you would need to install and configure Ansible to be able to manage your servers.
2. Include your SSH keys to the webserver group. To do this you need to go to hosts and included each server key to the group [web].
3.	Run *ansible-playbook –I hosts playbook.yml* in the command line within the root directory
4.	Ansible should now run through the instructions we have given within the playbook and complete this task. Enjoy the prowess of Automation. *Drops Mic*
