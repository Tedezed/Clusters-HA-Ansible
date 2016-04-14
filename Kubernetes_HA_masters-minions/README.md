Ansible cluster kubernetes PCS
------------------------------

Structure:

	├── Vagrantconfig <- Directory of files of configuration for vagrant machines.
	│   ├── hostsnames
	│   └── keys
	│		├── id_rsa.pub
	│  		└── id_rsa
	│
	├── ansible.cfg <- Configuration of ansible.
	├── group_vars <- Define variables for hosts groups
	│   └── all
	│  
	├── hosts <- List of hosts.
	├── site.yml <- Playbook.
	└── roles <- Roles

Execution with:

	ansible-playbook -i hosts site.yml

