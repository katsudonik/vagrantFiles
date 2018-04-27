## after vagrant up
```
git clone git@github.com:katsudonik/ansible.git; cd ansible
ansible-playbook -i localhost middleware.yml -k -v -t 'elastic_docker'
cd ~/docker; docker-compose up
```
