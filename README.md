Ansible Playbook for PostgreSQL 9.2 pldbgapi extension on CentOS 6.x
--------------------------------------------------------------------

This playbook requires Ansible 1.4

    TARGET_HOST=10.x.x.x
    ansible-playbook -i <(echo ${TARGET_HOST}) -u root -k site.yml
