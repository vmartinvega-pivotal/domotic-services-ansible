# ansible_container

docker build -t vmartinvega/ansible-playbook:raspberry .

docker run --rm -v "$(pwd):/ansible/playbooks:z" vmartinvega/ansible-playbook:raspberry playbook.yml
