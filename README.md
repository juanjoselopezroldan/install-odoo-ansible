# Install Odoo 11 of form automatic thanks the use of ansible (Recipe of ansible finished and completely functional, thoungh will recive updates future)
This repository is for perform the installation of Odoo 11 with your database postgreSQL in two nodes (one node for Odoo11 and one node for postgreSQL10) with ANSIBLE for that this installation is perform automatically (The nodes must have installated Debian 9).


## Structure
This repository is structured of the next shape:
* One file that will indicate whitch is the file to start (file ansible.cfg).
* One file that have the nodes that install the components need for that Odoo is run perfectly (file hosts.yaml).
* One file that will indicate the files that have to execute in order for that the installation is satisfactory (file playbook.yaml).
* Two directories that have the recipe for to do the installation of services of each node (directory node1 and node2).
* One directory that have the environment that will use in the installation of packages need for the installation of odoo (This directory is called by the recipes that are in the directory node1 and node2). The directory that has the environments is called vars.

![Alt Text](/image/ansible_scenario.png)