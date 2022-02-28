# database_as_system_service

Deploy mariadb container using ansible playbook with podman service and configure it as system service

```
$ ansible-playbook -i hosts.ini mariadb_container.yml --ask-vault-pass
```