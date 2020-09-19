# mongo replicaset in baremetall/vm



Run
```
ansible-playbook  -i inventory/hosts -l mongo mongo_cluster.yml -k -K -u $USER
ansible-playbook  -i inventory/hosts -l mongo mongo_cluster.yml  -u root
```

Version
```
ansible-playbook 2.9.6
python version = 3.6.8
```