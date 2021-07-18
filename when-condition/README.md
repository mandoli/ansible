#Conditionals based on ansible_facts
Often you want to execute or skip a task based on facts. Facts are attributes of individual hosts, including IP address, operating system, the status of a filesystem, and many more. With conditionals based on facts:

You can install a certain package only when the operating system is a particular version.

You can skip configuring a firewall on hosts with internal IP addresses.

You can perform cleanup tasks only when a filesystem is getting full.

https://docs.ansible.com/ansible/latest/user_guide/playbooks_conditionals.html

