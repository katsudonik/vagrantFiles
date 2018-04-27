## after vagrant up, docker-compose up
```
git clone git@github.com:katsudonik/ansible.git; cd ansible
ansible-playbook -i localhost middleware.yml -k -v -t 'elastic_docker'
cd ~/docker; docker-compose up
```
## access
* kibana http://localhost:5656
* elasticsearch java client http://localhost:8081/els

# box
kikeda/elastic_cluster
