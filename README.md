# ansible_container

docker build -t vmartinvega/ansible-playbook:raspberry .

docker run --rm -v "/opt/domotic-services:/domotic-services:z" -v "$(pwd):/ansible/playbooks:z" vmartinvega/ansible-playbook:raspberry playbook.yml
