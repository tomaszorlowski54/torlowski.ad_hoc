
# standard role execution
```
# ansible-playbook /etc/ansible/roles/torlowski.ad_hoc/site.yml -u root -t "standard" -l rocky
```

# backup configurations
```
ansible-playbook /etc/ansible/roles/torlowski.ad_hoc/backup_network_config.yml -u root -t backup_network -l ulf-k8s-1
```


# collect data from server
```
ansible-playbook /etc/ansible/roles/torlowski.ad_hoc/site.yml -u root -t "data_collection" -l ngn_nodes_all
```