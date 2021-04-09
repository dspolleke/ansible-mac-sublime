### Ansible Install Sumblime txt 3 on MacOSX

edit the vars in vars/main.yml
If you want to install in on another mac than the machine you run this from please edit the inventory file
You will find a list of Sublime packages there.

usage:
install role requirements:
ansible-galaxy install -r roles/requirements.yml

ansible-playbook main.yml
