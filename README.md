# Install Odoo 11 of form automatic thanks the use of ansible (Is yet in construction, when is terminated, this message will is change)
This repository is for perform the installation of Odoo 11 with your database postgreSQL in two nodes (one node for Odoo and one node for postgreSQL) with ANSIBLE for that this installation is perform automatically (The nodes must have installated Debian 9).


## Structure
This repository is structured of the next shape:
* One file that will indicate whitch is the file to start (file ansible.cfg).
* One file that have the nodes that install the components need for that Odoo is run perfectly (file hosts.yaml).
* One file that will indicate the files that have to execute in order for that the installation is satisfactory (file playbook.yaml).

![Alt Text](/image/ansible_scenario.png)