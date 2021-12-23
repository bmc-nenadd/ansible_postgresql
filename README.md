Ansible postgresql
===================

1.    Execute the playbook by running:

    ```bash
    ansible-laybook -i inventory --extra-vars "postgresql_version=12 remote_user=nenad postgresql_backup_dir=/path/ postgresql_database_name=databases"  postgresql.yml
    ```

