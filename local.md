pyenv activate ansible-2.9.6

ansible-playbook -v site.yml -i inventory/rpi/hosts.ini -t update