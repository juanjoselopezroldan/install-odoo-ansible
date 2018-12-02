# install-odoo-ansible (Is yet in construction, when is terminated, this message will is change)
This repository is for perform the installation of odoo with your database postgreSQL in two nodes (one node for odoo and one node for postgreSQL) with ANSIBLE for that this installation is perform automatically.


## Structure
This repository is structured of the next shape:
* One file that will indicate whitch is the file to start (file ansible.cfg).
* One file that have the nodes that install the components need for that odoo is run perfectly (file hosts.yaml).
* One file that will indicate the files that have to execute in order for that the installation is satisfactory (file playbook.yaml).

![Alt Text][/image/ansible_scenario.png]